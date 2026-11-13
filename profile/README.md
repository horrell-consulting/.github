# Christopher Horrell

**Staff DevOps Engineer: CI/CD, build and release, and developer productivity.**

I build the systems engineering teams use to build, test and ship software,
and make them faster and cheaper to run. I'm based in Toronto and available for
full-time, contract and fractional work.

## Track record

- **Nymi (2017–2020, 2023–2024):** designed and built the company's Jenkins
  CI/CD platform on AWS from scratch, then returned as DevOps Architect to lead
  the team running it. Self-service pipelines served 20–30 developers and test
  engineers across Rust, Elixir, C++, .NET and Swift. Cut CI infrastructure
  costs by about 50% with on-demand build agents, made builds 30% faster, cut
  S3 costs by 50%, and automated the audit and validation documents for every
  release.
- **Nylas (2020–2022):** Staff Site Reliability Engineer on a production API
  platform serving thousands of developers: AWS cost reduction, Elasticsearch
  operations, and Ansible across auto-scaling EC2 fleets.
- **Joyent (2012–2017):** Lead QA and Release Engineer for every container and
  VM image on the Joyent Public Cloud, with an automated build, test and
  release pipeline.
- **Node.js Docker Working Group (2015–2019):** original member and maintainer
  of the [official Node.js Docker image](https://github.com/nodejs/docker-node),
  including its slim and alpine variants. Presented the work at DockerCon 2015.

## How I can help

- **CI/CD platforms:** design, build or rescue pipelines in Jenkins and GitHub
  Actions, with self-service for developers and shared, versioned workflows.
- **Faster, cheaper builds:** on-demand build agents, caching and dependency
  management, so builds wait less and idle capacity costs nothing.
- **Release engineering:** repeatable, auditable releases, with compliance
  documents, scanning and artifact retention automated.
- **Container and machine images:** small, tested Docker images and Packer-built
  AMIs, published automatically.
- **Fractional DevOps:** a few days a month of senior ownership of your build
  and delivery infrastructure, for teams not yet ready for a full-time hire.

## Work you can look at

| Repository | What it shows |
| --- | --- |
| [github-settings](https://github.com/horrell-consulting/github-settings) | Developer productivity as code: every repository here is configured, protected and onboarded by Terraform on HCP Terraform, with a Sentinel deletion guard and a GitHub App bot |
| [packer-aws-windows-openssh](https://github.com/chorrell/packer-aws-windows-openssh) | The open version of the Windows build-agent images I built at Nymi: Packer (HCL2) AMIs for Windows Server 2022 and 2025 using OpenSSH instead of WinRM, built and tested in CI |
| [docker-node-minimal](https://github.com/chorrell/docker-node-minimal) | A `FROM scratch` Node.js image with a static binary compiled from source, multi-arch, rebuilt automatically for every supported release |
| [workflows](https://github.com/chorrell/workflows) and [template-repo](https://github.com/chorrell/template-repo) | Shared, versioned GitHub Actions workflows and the template every new repository starts from |

### In progress

| Repository | What it will show |
| --- | --- |
| [eks-spot-runners](https://github.com/chorrell/eks-spot-runners) | Ephemeral GitHub Actions runners on EKS spot instances (amd64 and arm64/Graviton) for cheap multi-platform Docker builds |
| [doks-runners](https://github.com/chorrell/doks-runners) | A low-cost, always-available self-hosted runner fleet on DigitalOcean Kubernetes |

## Get in touch

- **LinkedIn:** [christopherhorrell](https://www.linkedin.com/in/christopherhorrell/)
- **Website and blog:** [horrell.ca](https://horrell.ca)
- **GitHub:** [chorrell](https://github.com/chorrell)
