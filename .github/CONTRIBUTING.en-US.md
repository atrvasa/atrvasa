# Atrvasa Contributing Guide

Hi! Thank you for choosing Atrvasa.

Atrvasa is a java based library for developers and product managers.

We are excited that you are interested in contributing to Atrvasa. Before submitting your contribution though, please make sure to take a moment and read through the following guidelines.

## Issue Guidelines

- Issues are exclusively for bug reports and feature requests. Other questions may be closed directly. If any questions come up when you are using Atrvasa, please hit [Gitter](https://gitter.im/atrvasa-com/community) for help.

- Before submitting an issue, please check if similar problems have already been issued.

- Please specify which version of `Atrvasa` you are using, and provide OS information.

## Pull Request Guidelines

- Fork this repository to your own account. Do not create branches here.

- Commit info should be formatted as `[Plugin Name]: Info about commit.` (e.g. `Parameter: Fix xxx bug`)

- Rebase before creating a PR to keep commit history clear.

- Make sure PRs are created to `dev` branch instead of `master` branch.

- If your PR fixes a bug, please provide a description about the related bug.

- Merging a PR takes two maintainers: one approves the changes after reviewing, and then the other reviews and merges.

## Prerequisites

`JDK 1.8`, `JBoss 10.0.0 Final` and `Maven 3.2.3` are required.

```shell
git clone git@github.com:atrvasa/[Plugin Name]

```
To build:

```shell
XXX
```

## Plugin Developing Guidelines

- Run `mvn new <plugin-name>` to create project directory for a new component. Test codes, entry file and documentation are included.
