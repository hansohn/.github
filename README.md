<div align="center">
  <h1>.github</h1>
  <p>Default community health files for hansohn repositories.</p>
  <p>
    <!-- License -->
    <a href="LICENSE"><img alt="License" src="https://img.shields.io/github/license/hansohn/.github?style=for-the-badge"></a>
  </p>
  <p>
    <a href="#files">Files</a> •
    <a href="#how-it-works">How It Works</a> •
    <a href="#contributing">Contributing</a>
  </p>
</div>

## Overview

GitHub uses the files in this repository as defaults for every repository
owned by `hansohn` that does not have its own copy. One change here updates
the contributing guide, policies and issue forms across all of them.

## Files

| Path | Purpose |
| ---- | ------- |
| `CODE_OF_CONDUCT.md` | Contributor Covenant 2.1 |
| `CONTRIBUTING.md` | Contribution workflow and standards |
| `SECURITY.md` | How to report a vulnerability |
| `PULL_REQUEST_TEMPLATE.md` | Pull request description and checklist |
| `ISSUE_TEMPLATE/` | Bug, feature and support issue forms |
| `ISSUE_TEMPLATE/config.yml` | Turns off blank issues and links the security policy |

## How It Works

- A repository uses its own file when it has one. Otherwise it uses the file
  from this repository.
- Issue templates are all or nothing. If a repository has any file in
  `.github/ISSUE_TEMPLATE/`, none of the templates here apply to it.
- GitHub does not inherit `LICENSE`, `CODEOWNERS`, `release.yml` or workflows.
  Each repository needs its own copy.

> [!IMPORTANT]
> For a public repository, turn on private vulnerability reporting, which
> [`SECURITY.md`](SECURITY.md) refers to:
>
> ```bash
> gh api -X PUT repos/hansohn/<name>/private-vulnerability-reporting
> ```

## Security

To report a vulnerability, see the [Security Policy](SECURITY.md).
Do not open a public issue.

## Contributing

Contributions are welcome. See the [Contributing Guide](CONTRIBUTING.md)
for the full workflow, and follow the [Code of Conduct](CODE_OF_CONDUCT.md).

## License

MIT. See [LICENSE](LICENSE).
