<!-- GitHub Organization Profile -->
<p align="center">
  <img src="https://raw.githubusercontent.com/tailsec-com/branding/main/github-banner.png" alt="Tailsec" width="100%">
</p>

<h1 align="center">Tailsec</h1>

<p align="center">
  Free, open source security scanners for everyone
</p>

<p align="center">
  <a href="https://tailsec.io"><img src="https://img.shields.io/badge/website-tailsec.io-6366f1?style=flat-square"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-6366f1?style=flat-square"></a>
  <a href="https://github.com/tailsec-com?tab=repositories"><img src="https://img.shields.io/github/stars/tailsec-com?style=flat-square"></a>
</p>

## scanners

| Scanner | Description | npm |
|---------|-------------|-----|
| [@tailsec/scan-code](https://github.com/tailsec-com/scan-code) | Unified CLI — all scanners in one | ![npm](https://img.shields.io/npm/v/@tailsec/scan-code?style=flat-square) |
| [@tailsec/scan-k8s](https://github.com/tailsec-com/scan-k8s) | Kubernetes manifest security | ![npm](https://img.shields.io/npm/v/@tailsec/scan-k8s?style=flat-square) |
| [@tailsec/scan-terraform](https://github.com/tailsec-com/scan-terraform) | Terraform IaC scanning | ![npm](https://img.shields.io/npm/v/@tailsec/scan-terraform?style=flat-square) |
| [@tailsec/scan-docker](https://github.com/tailsec-com/scan-docker) | Dockerfile best practices | ![npm](https://img.shields.io/npm/v/@tailsec/scan-docker?style=flat-square) |
| [@tailsec/scan-secrets](https://github.com/tailsec-com/scan-secrets) | Secret detection in code | ![npm](https://img.shields.io/npm/v/@tailsec/scan-secrets?style=flat-square) |
| [@tailsec/scan-deps](https://github.com/tailsec-com/scan-deps) | Dependency vulnerabilities | ![npm](https://img.shields.io/npm/v/@tailsec/scan-deps?style=flat-square) |
| [@tailsec/scan-license](https://github.com/tailsec-com/scan-license) | License compliance | ![npm](https://img.shields.io/npm/v/@tailsec/scan-license?style=flat-square) |
| [@tailsec/scan-cfn](https://github.com/tailsec-com/scan-cfn) | CloudFormation scanning | ![npm](https://img.shields.io/npm/v/@tailsec/scan-cfn?style=flat-square) |
| [@tailsec/scan-sast](https://github.com/tailsec-com/scan-sast) | Advanced SAST | ![npm](https://img.shields.io/npm/v/@tailsec/scan-sast?style=flat-square) |
| [@tailsec/scan-container](https://github.com/tailsec-com/scan-container) | Container analysis | ![npm](https://img.shields.io/npm/v/@tailsec/scan-container?style=flat-square) |

## Cloud Provider Scanners

| Scanner | Description |
|---------|-------------|
| scan-aws | Native AWS security scanner |
| scan-azure | Native Azure security scanner |
| scan-gcp | Native GCP security scanner |
| scan-helm | Helm chart scanner |
| scan-kustomize | Kustomize overlay scanner |

## Quick Start

```bash
# Install any scanner
npm install -g @tailsec/scan-k8s

# Run a scan
npx @tailsec/scan-k8s ./manifests

# Or scan everything at once
npx @tailsec/scan-code ./ --all
```

## Ecosystem

| Project | Description |
|---------|-------------|
| [vscode-extension](https://github.com/tailsec-com/vscode-extension) | VS Code extension |
| [scan-python](https://github.com/tailsec-com/scan-python) | Python SDK |
| [scan-go](https://github.com/tailsec-com/scan-go) | Go SDK |
| [scan-ruby](https://github.com/tailsec-com/scan-ruby) | Ruby SDK |
| [ci-templates](https://github.com/tailsec-com/ci-templates) | GitLab, Jenkins, Tekton |
| [homebrew-tap](https://github.com/tailsec-com/homebrew-tap) | Homebrew formulas |
| [benchmarks](https://github.com/tailsec-com/benchmarks) | OWASP-style test suite |
| [rule-sync](https://github.com/tailsec-com/rule-sync) | Weekly CVE sync |
| [tailwindcss.com](https://github.com/tailsec-com/tailsec.io) | Documentation site |

## Contributing

See [CONTRIBUTING.md](./.github/profile/CONTRIBUTING.md) for how to contribute rules, report issues, or submit PRs.

## License

All projects are MIT licensed. Built with by the community.

[![advertisement](https://ads.servead.net/i/c22bcc19-be5f-49c2-a2eb-55c55052f197.svg)](https://ads.servead.net/c/c22bcc19-be5f-49c2-a2eb-55c55052f197)
