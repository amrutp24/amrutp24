# Amrut Pagidipally

Senior CloudOps & DevOps engineer · AWS Community Builder · Texas

I test what cloud vendors claim, then write down what I found.

AWS, GCP and Terraform for the day job. Outside of it I poke at new releases, break things in my own account, and publish the results — including the parts that didn't work. One of those write-ups got AWS to fix its own documentation eight days later. Lately it has been Lambda durable functions, Bedrock AgentCore, and Terraform providers for services that didn't have one.

Site: [amrutp24.github.io](https://amrutp24.github.io)

### Selected writing

- [I blogged about an AWS docs gap. Eight days later, AWS closed it.](https://amruteng.medium.com/i-blogged-about-an-aws-docs-gap-eight-days-later-aws-closed-it-f335d81d8a7e) — Medium, Aug 2026
- [I wrote a linter for a bug that can't be unit tested](https://amruteng.medium.com/i-wrote-a-linter-for-a-bug-that-cant-be-unit-tested-e296245eb39d) — Medium, Sep 2026
- [AWS says a production agent is now two API calls. I tested that.](https://builder.aws.com/content/3BnCQ3tNlxDCGakjdtowPexN1dJ/aws-says-a-production-agent-is-now-two-api-calls-i-tested-that) — AWS Builder Center, Jul 2026
- [I put an embedding model in a Lambda container. A year later, here's what I got wrong.](https://amruteng.medium.com/i-put-an-embedding-model-in-a-lambda-container-a-year-later-heres-what-i-got-wrong-bcc1dc6995f4) — Medium, Aug 2026

Everything else is on [Medium](https://amruteng.medium.com) and [AWS Builder Center](https://builder.aws.com/community/@apagidip).

### On the Terraform Registry

Providers

- [fireworks](https://registry.terraform.io/providers/amrutp24/fireworks/latest) — GPU inference deployments, datasets and fine-tuning jobs on Fireworks AI. The only Fireworks provider on the registry.
- [dataiku](https://registry.terraform.io/providers/amrutp24/dataiku/latest) — Projects, code environments, connections, users and groups inside a Dataiku DSS instance.

Modules

- [durable-agent-pipeline](https://registry.terraform.io/modules/amrutp24/durable-agent-pipeline/aws/latest) (aws) — Human-in-the-loop AI agent pipeline on Lambda durable functions, including the two non-obvious IAM grants they need.
- [pubsub-bq-pipeline](https://registry.terraform.io/modules/amrutp24/pubsub-bq-pipeline/google/latest) (google) — Pub/Sub → Cloud Run → BigQuery ingestion with OIDC push auth, dead-lettering and alerting.
- [dss](https://registry.terraform.io/modules/amrutp24/dss/aws/latest) (aws · google · azurerm) — Run Dataiku DSS on EC2, Compute Engine or an Azure VM with the same interface. [dss-bootstrap](https://registry.terraform.io/modules/amrutp24/dss-bootstrap/null/latest) renders the shared install script.

### Tools

- [toil-radar](https://github.com/amrutp24/toil-radar) — Estimates how much time a team loses to toil from git history and GitHub Actions, and ranks what to automate first. `pip install toil-radar`
- [replayguard](https://github.com/amrutp24/replayguard) — Determinism checker for Lambda durable functions: static analysis for Python, TypeScript, Java and Rust, plus a replay-divergence harness.
- [scp-preflight](https://github.com/amrutp24/scp-preflight) — Test an AWS service control policy against your workloads before you attach it. Fails the PR if reality disagrees.

### Credentials

| | |
|---|---|
| AWS | Community Builder, since March 2026 |
| Google Cloud | Professional Cloud Architect · Associate Cloud Engineer |
| Linux Foundation | Certified Kubernetes Administrator · Prometheus Certified Associate |
| HashiCorp | Terraform Associate |
| Microsoft | Azure Fundamentals |

Badges on [Credly](https://www.credly.com/users/amrut-pagidipally).

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/amrut-pagidipally-bb4244180/) · [Medium](https://amruteng.medium.com) · [AWS Builder Center](https://builder.aws.com/community/@apagidip) · amrut.pagidipally@gmail.com
