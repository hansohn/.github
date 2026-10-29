# Contributing

Thank you for your interest in contributing to this project! This document provides guidelines and instructions for contributing.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Development Setup](#development-setup)
- [Workflow](#workflow)
- [Coding Standards](#coding-standards)
- [Pull Requests](#pull-requests)
- [Reporting Issues](#reporting-issues)
- [Security](#security)
- [License](#license)

## Code of Conduct

This project adheres to a [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [conduct@hansohn.io](mailto:conduct@hansohn.io).

## Development Setup

See the project's README for prerequisites and setup steps. It also lists the commands that build, lint and test the project.

## Workflow

1. Check the project's existing issues and pull requests first.
2. Fork and clone the repository.
3. Create a branch from `main`:

   ```bash
   git checkout -b feat/your-feature-name
   ```

4. Make your changes following our [coding standards](#coding-standards).
5. Run the project's lint and test commands.
6. Commit using [Conventional Commits](https://www.conventionalcommits.org/):

   ```bash
   git commit -m "feat(scope): describe the change"
   ```

7. Push to your fork and open a pull request.

## Coding Standards

- Follow the existing style of the code you change.
- Make sure your changes pass the project's linters and tests.

### GitHub Actions Workflows

- Pin actions to a full commit SHA with a version comment (`@<sha>  # v1.2.3`). Renovate keeps them updated.
- Add timeout protection to jobs
- Include descriptive job and step names

## Pull Requests

- Fill in the [pull request template](PULL_REQUEST_TEMPLATE.md), including its checklist.
- Use a [Conventional Commits](https://www.conventionalcommits.org/) PR title.
- Link related issues using `closes #123` or `relates to #456`.
- A maintainer reviews the PR.
- Address the review feedback.
- A maintainer labels the PR (`bug`, `enhancement` or `documentation`) and merges it. The label sets the release notes section.

## Reporting Issues

Open a new issue in the project and choose the form that fits your request:

- 🐛 **Bug Report**: something does not work as expected
- ✨ **Feature Request**: an idea or improvement
- 💬 **Support Request**: questions about usage or configuration

## Security

Do not create a public issue for a security vulnerability. Follow our [Security Policy](SECURITY.md).

## License

By contributing to this project, you agree that your contributions will be licensed under the same license as the project (see the project's `LICENSE` file).

Thank you for contributing! 🎉
