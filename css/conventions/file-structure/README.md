# CSS Conventions

## File Structure

For each layout:
    
    # Main file
    application.scss
    # This folder has the styles for the application layout
    application/
      core/
        _core.scss
        _layout.scss
        _typography.scss
        _fonts.scss
        _grid.scss
        _helpers.scss
        _normalize.scss
        _mixins.scss
        mixins/
        objects/
          # Abstract patterns
          _media.scss
          _island.scss
          _clearfix.scss
      modules/
        _panel.scss
        _dropdown.scss
        _card.scss
        base/
          _icons.scss
          _buttons.scss
          _forms.scss
          _lists.scss
          _tables.scss
      settings/
        _settings.scss
      vendor/
        _flexslider.scss
        _jqueryui.scss
      main.scss

For multi-layout sites:

    application.scss
    application/
      # Same structure as above
    marketing.scss
    marketing/
      # Same structure as above
    shared/
      # Include all shared styles between layouts