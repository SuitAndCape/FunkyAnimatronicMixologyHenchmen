<!-- README.md -->

FunkyAnimatronicMixologyHenchmen
==========================================================================

FunkyAnimatronicMixologyHenchmen, or FAMH for boring, is a Sass (SCSS) library, providing functions, animations/transitions, mixins, and helpers.

## Contents

- [Title](#funkyanimatronicmixologyhenchmen)
- [Requirements](#requirements)
- [Generating Stylesheets](#generating-stylesheets)
  + [Sass Watch](#sass-watch)
- [Overlaps](#overlaps)
- [ToDos](#todos)
- [User Stories, MVP, Specifications, and Pseudocode](#user-stories-mvp-specifications-and-pseudocode)
- [Team Members](#team-members)
- [Humans.txt](#humanstxt)
- [License](#license)
- [Connect](#connect)

## Requirements

- [Ruby](https://www.ruby-lang.org/en/) 1.8.7+
- [Sass](https://github.com/sass/sass) 3.4.0+

## Generating Stylesheets

### Sass Watch
Before making any modifications to the SCSS files, change to the root directory of your project, and run one of the following commands...

- To compile minified CSS:

``` sh
sass --watch source/scss/famh.scss:public/assets/stylesheets/famh.min.css --style compressed
```

- To compile standard CSS:

``` sh
sass --watch source/scss/famh.scss:public/assets/stylesheets/famh.css
```

## Overlaps

- Make note of FunkyAnimatronicMixologyHenchmen and RAPTORSMACSS overlap

``` scss
// `_famh-config.scss` and RAPTORSMACSS' `_config.scss` overlaps
$clear
$gallery
$ebony
```

``` scss
// `_famh-variables.scss` and RAPTORSMACSS' `_variables.scss` overlaps
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

## ToDos

- Decide whether to continue using `@mixin prefixer`, [Autoprefixer](https://github.com/postcss/autoprefixer), or [Gulp-Autoprefixer](https://github.com/sindresorhus/gulp-autoprefixer)
- Write thorough documentation or instructional `.md` file(s) explaining how to use everything
- Develop more animations and functions
- Include logo, when developed
- Include favicon, when developed (maybe)
- Create separate Animatronics repo
- Create [RAPTORSMACSS](https://github.com/SuitAndCape/RAPTORSMACSS) tie-in repo

--------------------------------------------------------------------------

## User Stories, MVP, Specifications, and Pseudocode

To see the process that has been documented for this project, [click here](https://github.com/SuitAndCape/FunkyAnimatronicMixologyHenchmen/blob/master/SMSP.md).

## Team Members:

- **Ali Esmaili** _(Developer)_: [AESM](https://github.com/AESM)

## Humans.txt

[We Are People.  Get to Know Us.](https://github.com/SuitAndCape/FunkyAnimatronicMixologyHenchmen/blob/master/humans.txt)

The humans.txt movement is all about getting to know the people behind a website or project.  To find out more, visit [humanstxt.org](http://humanstxt.org/).

## License

This [project](#funkyanimatronicmixologyhenchmen) is copyright © 2015 Ali Esmaili | SuitAndCape.  It is free software that may be redistributed under the terms specified in the [LICENSE](https://github.com/SuitAndCape/FunkyAnimatronicMixologyHenchmen/blob/master/LICENSE).

This is based on [The MIT License (MIT)](http://opensource.org/licenses/MIT).  For more information, visit the [Open Source Initiative](http://opensource.org/) website.

## Connect

|              :tophat:             |              :rocket:             |
| --------------------------------- | --------------------------------- |
**_SuitAndCape GitHub_** | https://github.com/SuitAndCape
**_Personal GitHub_**    | https://github.com/AESM
**_Website_**            | https://SuitAndCape.github.io/
**_LinkedIn_**           | https://www.linkedin.com/in/SuitAndCape
**_Dribbble_**           | https://dribbble.com/SuitAndCape
**_Twitter_**            | https://twitter.com/SuitAndCape
