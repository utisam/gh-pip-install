# `gh pip-install`

[GitHub CLI](https://github.com/cli/cli) extension in order to
install python package released on GitHub release assets.

## Installation

```sh
gh extension install utisam/pip-install
```

This extension depends on `pip` command.

## Usage

```sh
# Install the latest released package of the current repository
gh pip-install
# Install the latest package of OWNER/REPO
gh pip-install --repo OWNER/REPO
# Install the package tagged as v1.0 of OWNER/REPO
gh pip-install v1.0
# Use pip3 command
gh pip-install --pip pip3
```

Use `--help` option for more details.
