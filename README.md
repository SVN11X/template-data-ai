# CHANGE-ME

TODO(owner): What this is, in one sentence.

## For whom

TODO(owner): Who uses it and in what situation.

## Use it

TODO(owner): How to install or open it, with a minimal example.

## Status

Draft.

## Layout

- `data/`: Data, or pointers to where data lives. Inside: `bronze/`, `silver/`, `gold/`.
- `src/`: Pipeline, analysis and model code.
- `notebooks/`: Exploration only.
- `tests/`: Tests and data checks.
- `scripts/`: Developer scripts. Optional.
- `docs/`: goals, glossary, assumptions, decisions and specs.

## Contributing

Tasks use the Task issue form. Pull requests follow `.github/pull_request_template.md`. Rules for people and AI tools are in `AGENTS.md`.

## Standard

This repository follows `SVN11X/standards@v1` with the `data-ai` profile. `AGENTS.md` is generated, so do not edit it by hand. To regenerate it or run the check locally:

```bash
pip install pyyaml
git clone --depth 1 --branch v1 https://github.com/SVN11X/standards .standards
python .standards/scripts/standard.py agents .
python .standards/scripts/standard.py check .
```

## License

MIT. See LICENSE.
