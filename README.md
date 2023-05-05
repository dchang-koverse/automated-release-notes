# automated-release-notes

Repo for testing how to automate release notes

## Instructions

1. Clone this repo
2. Run `sudo chmod +x .git/hooks/prepare-commit-msg` to allow the `git hook` to run an interactive CLI for formatting the commit message using [Commitizen](http://commitizen.github.io/cz-cli/)
3. Change this file
4. Run `git add README.md`
5. Run `git commit` and go through the prompts
6. Run `git push` to start the [Release Please](https://github.com/googleapis/release-please) GitHub Workflow

## Bug Fixes

Use the CLI prompt and choose `fix:`

## Feature Branches

Using GitFlow strategy, this change is introduced on `JIRA-001` and merged into the `develop` branch.

### v1.0.3

This should hopefully trigger v1.0.3 to get released.
