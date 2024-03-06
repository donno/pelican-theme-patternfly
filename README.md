pelican-patternfly-theme
========================

A theme for the Python based static generator [Pelican][0] using
[PatternFly][1]. PatternFly is an open source design system that enables teams
to create consistent and scalable enterprise products. PatternFly is sponsored
and maintained by Red Hat, but is open to all.

## What is Pelican?

* Static site generator that supports Markdown and reST syntax.
* Written in Python.
* Completely static output which is simple to host anywhere.

## Project Status

* The project is pre-alpha.
* Consider everything a work-in-progress or not yet implemented.

## Testing
The theme is tested against the sources of the following sites/projects:

* [samples project][1] from pelican.
* [this-week-in-rust][2] from [https://this-week-in-rust.org/][4]
    * Includes multiple index pages.
    * Only uses a single author - TWiR Contributors.
    * Only includes three tags - programming, rust and this-week-in-rust.


### Commands
* `py -3 -m pelican --theme-path R:\pelican-patternfly-theme\pelican\themes\patternfly S:\this-week-in-rust\content`

## Future

### Packaging
The idea is to make this pip-installable and redistributable through PyPI
however Pelican itself doesn't quite support that as an option.


[0]: https://getpelican.com/
[1]: https://www.patternfly.org/
[2]: https://github.com/getpelican/pelican/tree/master/samples
[3]: https://github.com/rust-lang/this-week-in-rust
[4]: https://this-week-in-rust.org/