# github-actions-common

[![[C]ontinuous [I]ntegration](https://github.com/percebus/github-actions-common/actions/workflows/always.yml/badge.svg)](https://github.com/percebus/github-actions-common/actions/workflows/always.yml)
[![Pull Request](https://github.com/percebus/github-actions-common/actions/workflows/pull_request.yml/badge.svg?event=pull_request)](https://github.com/percebus/github-actions-common/actions/workflows/pull_request.yml)

[`LICENSE`](./LICENSE.md) | [`TODO`s](./TODO.md)

GitHub re-usable Workflows and Actions

## GitHub

### Actions

| action                                                   | tests                                                                                                                                                                                                                                   |
| -------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [checkout](./.github/actions/checkout)                   | [![Test actions/checkout](https://github.com/percebus/github-actions-common/actions/workflows/test_actions__checkout.yml/badge.svg)](https://github.com/percebus/github-actions-common/actions/workflows/test_actions__checkout.yml)    |
| [ssh-agent](./.github/actions/ssh-agent)                 | [![Test actions/ssh-agent](https://github.com/percebus/github-actions-common/actions/workflows/test_actions__ssh-agent.yml/badge.svg)](https://github.com/percebus/github-actions-common/actions/workflows/test_actions__ssh-agent.yml) |
| [artifact-upload](./.github/actions/artifact-upload)     | [![Test actions/artifact-*](https://github.com/percebus/github-actions-common/actions/workflows/test_actions__artifact.yml/badge.svg)](https://github.com/percebus/github-actions-common/actions/workflows/test_actions__artifact.yml)  |
| [artifact-download](./.github/actions/artifact-download) | [![Test actions/artifact-*](https://github.com/percebus/github-actions-common/actions/workflows/test_actions__artifact.yml/badge.svg)](https://github.com/percebus/github-actions-common/actions/workflows/test_actions__artifact.yml)  |

### Workflows

TBD

## References

- [GitHub: Contexts reference](https://docs.github.com/en/actions/reference/workflows-and-actions/contexts#github-context)

### Medium

- [Adding a unique build number to GitHub Actions](https://medium.com/attest-product-and-technology/adding-a-unique-github-build-identifier-7aa2e83cadca)
