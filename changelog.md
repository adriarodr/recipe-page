# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.1] - 2024-02-17
### Added
- README.md
- screenshot of the webpage in images folders

### Changed
- some td tag to th tag on table in nutrition section to add to accessibility
- some of the table style rules for the tables to reflect the changes to changing the td tag to th tag
- fixed a mistake with --c-neutral-400 variable not having the right color.
- font weight on h2 heading
- adjusted the margin between the bullets on unordered and ordered list
- padding on the main selector

### Removed
- README-template.md

## [1.2.0] - 2024-02-17
### Added
- font weight to body selector of normal
- font size to h1, h2 and h3 headings
- margin to h2 heading
- color to markers on unordered list and ordered lists 
- font weight to markers on unordered list and ordered lists to very bold
- font size on order list markers selector
- comments to media queries to indicate which media query is for tablet and laptop/desktop screens
- bolded test to instruction section by using span element with bold class
- border bottom to ingredients and instruction sections
- ID value to nutrition_value to table within nutrition section
- class="external_link" to anchor tags within attribution section 
- link to github profile
- target to anchor tag to open my profile in a new tag
- new variable to underline color on the external link
- black text color variable
- padding-bottom on #instructions selector
- style rules for nutrition_value table
- style rules for footer section/attributions
- type attribute to stylesheet link in index.html

### Changed
- Adjusted spacing on style.css to improve readability
- font weight on h3 selector to very bold
- margin on ul and ol selectors
- padding left on ul li and ol li selectors
- second ul li:not(:last-child) selector to ol li:not(:last-child) so one selector is for unordered list and another for ordered lists 
- padding on main selector inside tablet screen media query
- font weight on the bold class to very bold
- creator to my github profile name 
- spacing on styles.css 
- font-weight on h1 and h2 headings to be bold
- font size on h1 heading 
- margin on h2 heading to margin-block 
- margin on ul and ol selectors to margin-left 
- margin on last items in ul and ol to margin-block
- padding on #container selector to percentage 
- padding on #prep_time selector
- color of the border-bottom on #instructions selector
- moved media queries to bottom of the styles.css file
- min-widths on the media queries
- switched the ordering of the headings
- added id with value attribution to the footer tag
- name of the --c-neutral-300 variable to --c-neutral-200 in styles.css
- --c-neutral-800 variable to be black in styles.css
- switched the styles of h2 and h3 style rules

### Removed
- comment on styles.css on the widths of the screen sizes
- width on main selector
- style sheet in the head of index.html
- section in the footer 

## [1.1.0] - 2024-02-12
### Added
- external style sheet for google fonts
- intro section to index.html
- universal selector style rule for box-sizing to border-box
- font family outfit to the body
- style rules for all images to be responsive
- heading styles rules for h1, h2, h3 with font-family, font-weight and color
- styles rules for order and unordered list for markers and spacing
- media queries for phone, tablet and desktop views for main, img and containers selectors
- style rules for prep_time section 
- font-weight style rules for bold span 

### Changed
- comment for style.css
- Moved the omelette image iutside the container div
- (--c-neutral-200) variable to (--c-accent-200)
- switched plently of #container style rules to main
- color on the list markers in prep_time 

## [1.0.0] - 2024-02-05
### Added
- Style Rules for #container
- Style Rules for the body tag
- Style Rules for the Omelette image

### Removed
- height and width attributes on Omelette image tag

## [Initial Release] - 2024-02-04
### Added
- .gitignore 
- README-template.md 
- index.html
- css, fonts, and images folder
- favicon-32x32.png and image-omelette.jpeg images in images folder
- styles.css in css folder 