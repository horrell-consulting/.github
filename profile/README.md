# Horrell DevOps Consulting

Independent DevOps consulting and contract infrastructure work by
[Christopher Horrell](https://www.linkedin.com/in/christopherhorrell/), based in
Toronto. I help early-stage engineering teams spend less on AWS, ship faster
through better CI/CD, and put their infrastructure on a footing that scales.

## What I do

- **AWS cost optimization:** spot and Graviton capacity, right-sizing, and
  build fleets that only run while there's work to do.
- **CI/CD modernization:** fast, secure pipelines with shared workflows,
  pinned dependencies, and self-hosted runners where they pay off.
- **Infrastructure as code:** Terraform and HCP Terraform with guard rails:
  policy checks, apply-on-merge, and nothing deleted by accident.
- **DevOps leadership:** setting direction, writing the golden path, and
  mentoring the team that runs it.

## Work you can look at

| Repository | What it shows |
| --- | --- |
| [github-settings](https://github.com/horrell-consulting/github-settings) | Governance as code: every repository in this organization is configured, protected and onboarded by Terraform on HCP Terraform, with a Sentinel deletion guard and a GitHub App bot |
| [packer-aws-windows-openssh](https://github.com/chorrell/packer-aws-windows-openssh) | Packer (HCL2) templates for encrypted, key-only-SSH Windows Server 2022 and 2025 AMIs with Fast Launch, built and tested in CI |
| [docker-node-minimal](https://github.com/chorrell/docker-node-minimal) | A `FROM scratch` Node.js image with a static binary compiled from source, multi-arch, rebuilt automatically for every supported release |

### In progress

| Repository | What it will show |
| --- | --- |
| [eks-spot-runners](https://github.com/chorrell/eks-spot-runners) | Ephemeral GitHub Actions runners on EKS spot instances (amd64 and arm64/Graviton) for cheap multi-platform Docker builds |
| [doks-runners](https://github.com/chorrell/doks-runners) | A low-cost, always-available self-hosted runner fleet on DigitalOcean Kubernetes |

The CI behind all of these comes from shared, versioned workflows in
[chorrell/workflows](https://github.com/chorrell/workflows), and new
repositories start from [chorrell/template-repo](https://github.com/chorrell/template-repo).

## Get in touch

- **LinkedIn:** [christopherhorrell](https://www.linkedin.com/in/christopherhorrell/)
- **Website and blog:** [horrell.ca](https://horrell.ca)

Available for contract and fractional DevOps leadership work.
