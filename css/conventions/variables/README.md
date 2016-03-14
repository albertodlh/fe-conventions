# CSS Conventions

## Variables

### Colors

Define first your basic color palette. These are plain colors without any defined purpose:

    $purple: #2D2D3C;
    $orange: #FF833F;
    $green : #0C0;
    $red   : #900;
    
    $gray-lighter: #EEE;
    $gray-light  : #CCC;
    $gray        : #999;
    $gray-dark   : #666;
    $gray-darker : #333;

Then, define specific purpose colors:

    $color-text-link      : $purple;
    $color-text-default   : $gray-dark;
    $color-brand-success  : $green;
    $color-brand-error    : $red;
    $background-color-main: $gray-lighter;
    $border-color-input   : $gray-light;

### Typography

    $font-family-serif     : Times, serif;
    $font-family-sans-serif: Helvetica, sans-serif;
    $font-family-base      : $font-family-sans-serif;
    $font-family-icons     : "Dashable Iconset";

    $font-size-base: 16px;

    $font-size-small : rem($font-size-base * 0.8);
    $font-size-medium: rem($font-size-base);
    $font-size-large : rem($font-size-base * 1.2);

    $font-size-alpha: rem($font-size-base * 3);
    $font-size-beta : rem($font-size-base * 2.5);
    $font-size-gamma: rem($font-size-base * 2);
    $font-size-delta: rem($font-size-base * 1.5);

    $font-size-giga: rem($font-size-base * 6);
    $font-size-mega: rem($font-size-base * 5);
    $font-size-kilo: rem($font-size-base * 4);

    $line-height-base : 18px;
    $line-height-ratio: $line-height-base / $base-font-size;

    $base-spacing-unit: $line-height-base;
    $half-spacing-unit: $base-spacing-unit / 2;

### Responsive Breakpoints

    $small : 481px !default;
    $medium: 769px !default;
    $large : 1025px !default;
    $wide  : 1281px !default;

### Other

    $border-radius-default: 4px;
    $text-shadow-default  : 0 1px black;
