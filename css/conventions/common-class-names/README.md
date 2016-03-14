# CSS Conventions

## Common Class Names

The following class names are used in almost every project, and are commonly reused for building new modules or making small style adjustments. For these reasons, we should maintain consistency in the way we name them across projects, so everyone involved can rapidly use them without having to check for how they were named:

### Helpers

    .clearfix {}

    .float--right {}
    .float--left {}
    .float--none {}

    .text--left {}
    .text--center {}
    .text--right {}

    .weight--light {}
    .weight--normal {}
    .weight--bold {}

    .color--success {}
    .color--error {}
    .color--warning {}
    .color--muted {}

    font-size-large {}
    font-size-small {}

    .alpha {}
    .beta {}
    .gamma {}

    .push {}          # Margin on all 4 sides
    .push--top {}
    .push--bottom {}
    .push--left {}
    .push--right {}
    .push--ends {}    # Margin only on top and bottom
    .push--sides {}   # Margin only on left and right

    .push-half
    .push-half--top {} # And so on for other variations

    .flush {}         # Margin zero on all 4 sides
    .flush--top {}    # And so on for other variations

    .bleed            # Negative margin on all 4 sides
    .bleed--top {}    # And so on for other variations

    .soft {}          # Padding on all 4 sides
    .soft--top {}     # And so on for other variations

    .hard {}          # Padding zero on all 4 sides
    .hard--top {}     # And so on for other variations

    .accessibility {} # For hidden elements

### Main Layout

    .main-wrapper {}
    .main-header {}
    .main-content {}
    .main-nav {}
    .main-footer {}

### Icons

    .icon {}          # Base for all icons
    .icon--user {}
    .icon--team {}

### Buttons

    .button {}        # Base for all buttons
    .button--default
    .button--primary
    .button--success
    .button--error
    .button--link
    .button--disabled

    .button--small
    .button--large
    .button--flat

### Lists

    .list--bullet
    .list--decimal
    .list--vertical
    .list--horizontal

### Tables

    .table--striped
    .table--clean

### Forms

    .form {}
    .label {}
    .text-input {}
    .select-input {}
    .file-input {}
    .option-input
    .option-input--checkbox
    .option-input--radio
    .option-input__label

### Media

    .media {}
    .media__object {}
    .media__object--rev {}
    .media__body {}

### Other

    .panel {}
    .island {}
    .islet {}

