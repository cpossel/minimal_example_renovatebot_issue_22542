Minimal example for renovatebot issue [#22542](https://github.com/renovatebot/renovate/discussions/22542).

# Current behavior
Using [rangeStrategy](https://docs.renovatebot.com/configuration-options/#rangestrategy) with option `bump` (or any other range strategy) results in renovatebot not updating the dependencies listed in [pyproject.toml](.pyproject.toml).

# Expected behavior
The dependencies should be updated with range specifiers `>=` and `>` similar to the caret `^` and tilde `~` range specifiers that are supported by renovatebot for other file types.
