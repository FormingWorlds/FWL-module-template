# ABASSI
Volatile delivery and planetary accretion model designed for integration into PROTEUS.

Named after the [Ibibio god of creation](https://en.wikipedia.org/wiki/Abassi_(spirit)).

## Documentation

The `docs/` tree is a working documentation site carrying the shared PROTEUS theme, so a
module built from this template is on-brand from its first commit. `zensical serve` previews
it; pushing to `main` publishes it through `.github/workflows/docs.yaml`.

Rename `ABASSI` to your module throughout `mkdocs.yml`, `docs/index.md` and
`docs/Community/contact.md`, and leave `docs/stylesheets/extra.css` alone: it is a verbatim
copy of the stylesheet released by
[proteus-visual-language](https://github.com/FormingWorlds/proteus-visual-language), and
keeping it untouched is what makes taking a later release a plain copy. Put anything your
site needs on top of it in `docs/stylesheets/layout.css`.
