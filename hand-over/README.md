Asset Handover
===

Design Review
---

When receiving design comps, review to make sure they include:

- Versions of full screen backgrounds that are either 1920px wide or fade/repeat gracefully to fill the entire screen
- Tablet and phone versions of background images
- Content for every Carousel slide
- Files for all fonts used
- Favicon and Apple touch icons in BMP or PNG formats:
  - Favicon sizes: 16x16, 32x32, 48x48 (24x24, 64x64 are optional) 
  - Apple touch icons sizes: 57x57, 72x72, 114x114, 120x120, 144x144, 152x152
- Behavior and states for every UI module (popups, pullovers, etc)
- Hover and active states for clickable items like links and buttons
- Empty states for all views
- Form validation and error messages that are informative and user friendly
- Form states (active, disabled) for every form element in use
- Forgot password views and related emails
- Registration related emails
- Flash and notification messages that are informative and user friendly for:
  - Log in
  - Log out
  - Global errors
  - Form confirmation
- Error pages with at least a link back to the previous page and to the home page
- Base color palette
- Descriptive color palette with at least:
  - Primary font color
  - Heading font color
  - Link color
  - Success, warning, info and error colors
  - Gray colors
- Icon manifest
- Typography guidelines
  - Font sizes, weigths and line heights for headings (h1 to h6)
  - Font sizes, weigths and line heights for body text
- Reponsive behavior for each component on main breakpoints (if possible)

Also, check the following:

- The use of filters such as multiply and overlay are limited to elements with a non-transparent background
- All fonts used are either web safe or can be embed with @font-face
- All fonts used are free to use or have the required license
- If possible, no more than 3 custom fonts are used. Otherwise, check with the designer
- Pages exist for all the links in the design

Front End Review
---

Before delivering a project, feature or assets to production, a client or a team member, make sure the following requirements are met:

- Browser compatibility has been tested
- Responsive behaviour has been tested
- Large backgrounds scale gracefully on large screen resolutions
- Unused and commented code has been removed
- Image sizes and compression have been optimized
- Unused assets have been removed
- Favicon and/or app icons are included
- All pages have a proper title
- Hover and active states for buttons and links are included
- Empty states, no result states, error states and confirmation states for data tables and forms are included
- Error pages are included
- There are no broken links
- There is no missing or placeholder content
- Analytics/Metrics code is included (if applicable)


Also, include a style guide containing documentation of at least the base styles, which include:

- Grid system
- Layout patterns
- Helper classes
- Typography
- Forms
- Buttons
- Icons
- Tables
