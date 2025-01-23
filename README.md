# Python/cuda template

Quick template so I can easily set up new personal project repos with the settings/extensions I want.

Includes:
* gpu devcontainer which uses the base pytorch + cuda ubuntu image. Also installs the local repo editably, installs pre-commit hooks, and does git cred setup inside the container on creation/rebuild
* readme
* pyproject.toml including settings for some precommit hooks
* some standard precommit hooks I use
* editorconfig
* gitignore
* an empty src directory
