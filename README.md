# KDL dotfiles

This repository contains configuration files for common development environments.

## Dev Containers

The `devcontainers` directory contains configuration files for
[Dev Containers](https://containers.dev/). Each subdirectory contains a
`devcontainer.json` file that defines a default container for a specific
technology.

To use a dev container, copy the `devcontainer.json` file to a `.devcontainer`
directory in the root of the project you want to use it in.

## Git

### Message Format

The `git/.gitmessage` file contains a default message format for git commits.

To use it, add it to the root of a project and run
`git config commit.template .gitmessage`.
