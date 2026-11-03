# Contributing guide

This guide applies to each repository of the `gsuquet` account that has no `CONTRIBUTING.md` of its own. A repository with its own `CONTRIBUTING.md` uses its own rules.

## Welcome

Thank you for your interest. The repositories accept these contributions:

- bug reports and questions, as issues;
- corrections to the code and the documentation, as pull requests (PRs).

The repositories do not accept these contributions:

- a vulnerability report in a public issue or PR. Obey the [security policy](SECURITY.md);
- a large change with no issue first.

## Ground rules

Obey the [code of conduct](CODE_OF_CONDUCT.md).

## Share ideas

1. Search the issues of the repository for the same idea.
2. If no issue has it, open an issue. Tell the goal and the problem that it solves.

## Before you start

Make sure that you have:

- a GitHub account;
- Git;
- the tools that the `README.md` of the repository lists.

## Contribution workflow

### Fork and clone repositories

Fork the repository on GitHub, then clone your fork.

### Report issues and bugs

Open an issue. Tell the command that you ran, the output and the result that you expected. Do not put secrets or private addresses in an issue.

### Commit messages

Use [Conventional Commits 1.0.0](https://www.conventionalcommits.org/en/v1.0.0/), for example `fix(parser): accept empty lines`.

### Branch creation

Create a branch from the default branch. Use the name `<type>/<short-title>`, where `<type>` is a Conventional Commits type, for example `fix/empty-lines`.

### Pull requests

1. Run the checks of the repository before you push.
2. Open a PR that tells what changed and why.
3. Write `Closes #<issue>` in the description, when an issue exists.
4. Answer each review comment with a change or a reason.

## Get help

Refer to the [support file](SUPPORT.md).
