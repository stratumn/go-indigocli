# Stratumn CLI

[![Build Status](https://semaphoreci.com/api/v1/stratumn/cli/branches/master/shields_badge.svg)](https://semaphoreci.com/stratumn/cli)
Command-line interface for projects leveraging Stratumn's technology.

## Usage

Run `stratumn-cli generate <project name>` to start a new project.

## Advanced

The Stratumn CLI uses generator templates to create projects that are ready to run.
We provide generator templates at <https://github.com/stratumn/generators>.
By default, the CLI will use the generators that are tagged with the same version,
but you can provide custom generators using the `--generators-*` command-line switches.
