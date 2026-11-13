# .github

[![markdownlint](https://github.com/horrell-consulting/.github/actions/workflows/markdownlint.yml/badge.svg)](https://github.com/horrell-consulting/.github/actions/workflows/markdownlint.yml)

The organization profile for
[Horrell DevOps Consulting](https://github.com/horrell-consulting).

| Path | Purpose |
| --- | --- |
| [`profile/README.md`](profile/README.md) | The profile shown on the organization's GitHub page |

Repository settings and rulesets for this organization are managed by Terraform
in [horrell-consulting/github-settings](https://github.com/horrell-consulting/github-settings).

## Local development

Install [prek](https://github.com/j178/prek) (`brew install prek`) and run the
hooks before pushing. The markdownlint hook runs in Docker.

```sh
prek install
prek run --all-files
```

## License

[MPL-2.0](LICENSE)
