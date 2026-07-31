# Project Context

When working with this codebase, prioritize readability over cleverness. Write the code so that is easy to have a mental image of the system. Ask clarifying questions before making architectural changes. Project is managed using pixi. Ask for confirmation before installing any package with pixi. All commands should be execute with pixi run. Any time you ask me for clarification when building PLAN.md, please update PLAN.md accordingly.

## About This Project

Use core python modules as much as possible, like for sqlite. Assume I am using herdr, claude-cli and neovim.

## Key Directories

- `src/vine_reduce/` - core python module
- `examples/` - examples of uses of vine_reduce

## Standards

- pytest for testing (fixtures in `tests/conftest.py`)
- PEP 8 with 100 character lines
- format with black

## Common Commands
```bash
pixi run -e dev pytest tests/ -v   # run tests
pixi run -e dev black .            # format
pixi run -e dev flake8             # lint
```

## Notes

