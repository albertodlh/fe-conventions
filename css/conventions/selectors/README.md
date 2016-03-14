# CSS Conventions

## Selectors

We use [B.E.M. (Block, Element, Modifier)](http://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/) methodology for modules.

This methodology help us avoid selectors that are dependant on the parent container:

    # Bad
    <div class="widget">
      <h1 class="title">Hello World</h1>
    </div>

    .widget .title {} 

    # Good
    <div class="widget">
      <h1 class="widget__title">Hello World</h1>
    </div>

    .widget__title {}

It also reduces selector nesting and specificity issues:

    # Bad
    <header class="main-header">
      <nav>
        <ul>
          <li><a href="">Home</a></li>
        </ul>
      </nav>
    </header>

    .main-header nav li {}

    # Good
    <header class="main-header">
      <nav class="main-nav">
        <ul>
          <li class="main-nav__item"><a href="">Home</a></li>
        </ul>
      </nav>
    </header>
    
    .main-nav__item {}

However, it must not be overused:

    # Bad
    .widget {}
    .widget__header {}
    .widget__header__title {}
    .widget__header__title__icon {}

    # Good
    .widget {}
    .widget__header {}
    .widget__title {}
    .widget__title-icon {}

Or use unnecessarily with SASS:

    # Bad
    .widget {
      .widget__title {}
    }

    # Good
    .widget {}
    .widget__title {}

Also, avoid selectors that do too much:

    # Bad
    .button--success--large {}

    # Good
    .button--success {}
    .button--large {}

Use verbs for module states:

    .is-hover {}
    .is-open {}
    .has-sidebar {}

For JavaScript hooks, use the `.js-` prefix. These hooks must not have any styles attached to them. Likewise, selectors without the `.js-` prefix must not be referenced in the JavaScript:

    .js-datepicker
    .js-modal-trigger
    .js-close