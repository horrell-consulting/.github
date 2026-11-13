# AGENTS.md

The `horrell-consulting` organization's `.github` repository. GitHub shows
`profile/README.md` on the organization page, and only while this repository is
public. It's a portfolio page for full-time, contract and fractional work, so
keep it accurate: every number in "Track record" comes from the CV in
career-ops (`cv.md`), each project is described as its own README does, and
unfinished projects go under "In progress". The headline matches LinkedIn,
the CV and the `chorrell` profile; change them together.

## Structure

```text
├── profile/README.md           # The organization profile
├── .pre-commit-config.yaml     # gitleaks, markdownlint-cli2 (Docker), hygiene hooks, zizmor
└── .github/workflows/          # Stubs calling chorrell/workflows@v1: markdownlint, pre-commit, zizmor, dependabot-automerge
```

## Rules

- **Link repositories where they live now.** When a repository moves from
  `chorrell` to `horrell-consulting`, update its link here.
- **Repository settings aren't configured here.** Rulesets and required checks
  are managed by Terraform in
  [horrell-consulting/github-settings](https://github.com/horrell-consulting/github-settings).
- Run `prek run --all-files` before pushing (the markdownlint hook needs
  Docker). `zizmor / zizmor` is a required check, so keep the zizmor stub.
- Commits and PR titles use conventional commits (`feat: ...`, `docs: ...`).
  PRs are squash-merged.
