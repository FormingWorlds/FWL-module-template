# ABASSI

ABASSI is a volatile delivery and planetary accretion model designed for integration into
PROTEUS. Named after the [Ibibio god of creation](https://en.wikipedia.org/wiki/Abassi_(spirit)).

!!! info "PROTEUS framework"
    ABASSI is a module of the PROTEUS framework, a modular Python framework that simulates
    the coupled evolution of the atmospheres and interiors of rocky planets and exoplanets.
    The documentation for PROTEUS is [here](https://proteus-framework.org/PROTEUS).

## Documentation

These pages are built with [zensical](https://zensical.org/) and carry the shared PROTEUS
theme, so every module site reads as one product. `docs/stylesheets/extra.css` is a verbatim
copy of the theme stylesheet released by
[proteus-visual-language](https://github.com/FormingWorlds/proteus-visual-language); do not
edit it, so that taking a later release stays a plain copy. Anything this site needs on top
of it goes in `docs/stylesheets/layout.css`, whose first section is shared across the module
sites and whose second is for rules only this site uses.

To work on the pages locally:

```bash
pip install zensical markdown-include pymdown-extensions mkdocstrings mkdocstrings-python
zensical serve
```

## License

See [the included license](https://github.com/FormingWorlds/ABASSI/blob/main/LICENSE.txt).
