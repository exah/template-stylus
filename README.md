# Stylus template (for khaos)

Some stylus staff that I use in my everyday projects. Like grids, resets and utility classes.

Doesn't have any depedencies and vendor prefixes. You need manualy install stylus, and setup it in your project.

I recommend to use it with following PostCSS plugins: `autoprefixer`, `rucksack-css`, `cssnano`.


## Quick start

Install [khaos](https://github.com/segmentio/khaos):

```sh
$ npm i -g khaos
```

Use template:

```
$ khaos create exah/template-stylus path/to/project/styles
```

This will create `path/to/project/styles` directory inside yours project.


## Naming

[Using BEMIT naming convention](http://csswizardry.com/2015/08/bemit-taking-the-bem-naming-convention-a-step-further/)


## Structure

- Settings
    - breakpoints
    - colors
    - general
    - grid
    - typography
- Mixins
    - spacing
    - resets
    - flexbox helpers
    - flexbox grid
- Base (without prefixes)
    - defaults (and resets)
    - document
    - typography
- Layout (`.l-`,`.o-` prefixes)
    - grid
    - media
- Components (`.c-` prefix)
- Utility classes (`.u-` prefix)
    - display
    - floats (+ clearfix)
    - hacks
    - margin
    - overflow
    - padding
    - position
    - responsive
    - text


## TODO

- [ ] Aspect Ratio mixin and layout object
- [ ] More breakpoint specific utils
- [ ] Enable/disable short/long classes
- [x] Spacing & Grid settings
- [x] Grid mixin
- [x] Media object (layout)
- [x] Grid object (layout)
- [x] Colors
- [x] Position utils
