# GeoEpi Lab Book

This repository builds the [GeoEpi Lab Book](https://geoepi.github.io/geoepi-notebook/), a practical guide for GeoEpi scientists and collaborators.

The Lab Book focuses on organizing collaborative geographical epidemiology: project and subproject structure, reproducibility, data stewardship, scientific computing, collaboration, and transferable analytical work. It documents the planned GeoEpi Hub operating model without creating the Hub or implementing cross-repository automation.

## Render locally

Install [Quarto](https://quarto.org/), then run from the repository root:

```powershell
quarto render
```

Use `quarto preview` while editing. The complete rendered site is written to `_site/`, which is ignored by Git.

## Contributing

Propose changes through a focused branch and pull request. Explain the practical GeoEpi use case, preserve useful project-specific flexibility, and distinguish conventions from genuine scientific, security, contractual, or institutional requirements. Render the full site and run `python scripts/validate_site.py` before opening a pull request. See [CONTRIBUTING.md](CONTRIBUTING.md).

The current site is published at [geoepi.github.io/geoepi-notebook](https://geoepi.github.io/geoepi-notebook/). Historical lifecycle-oriented pages and superseded templates remain under [`archive/`](archive/README.md) for future reuse and are excluded from active navigation and rendering.
