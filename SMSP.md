<!-- SMSP.md -->

Stories, MVP, Specs, and Pseudocode
==========================================================================

## User Stories

1. Easy to add to any project I can use Sass (SCSS) in
2. Provides useful Sass functions, animations/transitions, mixins, and helpers
3. The files are tied together in a practical manner, but easily detachable
4. Modular design
  - Separate files
  - Separate folders

--------------------------------------------------------------------------

## Minimum Viable Product

- Sections/Folders
  + `utilities/`
  + `extends/`
- Files
  + Functions
    * `_funkulators.scss`
  + Animations/Transitions
    * `_animatronics.scss`
  + Mixins
    * `_mixology.scss`
  + Helpers
    * `_henchmen.scss`
  + Config
    * `_famh-config.scss`

--------------------------------------------------------------------------

## Overlaps

``` scss
// `_famh-config.scss` and RAPTORSMACSS' `_config.scss` overlaps
$clear
$gallery
$ebony
$primary-trans
$secondary-trans
$html-font-size
$body-font-size
$body-bg-color
```

``` scss
// `_funkulators.scss` and RAPTORSMACSS' `_functions.scss` overlaps
@function pxrem(){}
@function pxem(){}
```

``` scss
// `_henchmen.scss` and RAPTORSMACSS' `_helpers.scss` overlaps
.center-align, %center-align
.clearfix, %clearfix
.no-bullets, %no-bullets
```
