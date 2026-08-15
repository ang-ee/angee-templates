# angee-templates

The Copier templates the Angee operator renders — projects, stacks,
workspaces, and services. `angee init` resolves its default templates from
this repository; `templates/README.md` is the map to the kinds and the stack
layouts.

The template contract tests live in `tests/` (pytest + PyYAML, no framework
install): `uv run pytest -q`.
