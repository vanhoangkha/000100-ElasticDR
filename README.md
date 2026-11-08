# AWS Elastic Disaster Recovery Workshop

> Disaster recovery with AWS Elastic Disaster Recovery.

A hands-on workshop from the [AWS First Cloud Journey](https://github.com/vanhoangkha/aws-first-cloud-journey) series, available in English and Vietnamese.

**Read the workshop online:** https://vanhoangkha.github.io/000100-ElasticDR/

## Overview

AWS Elastic Disaster Recovery (AWS DRS) helps minimize downtime and data loss with the ability to quickly and reliably recover applications on-premises and in the cloud using available storage. Reasonable cost, minimal computing resources, and point-in-time recovery.

This lab simulates an on-premises environment that allows customers to replicate disaster recovery to AWS.

## Workshop contents

1. Introduction
2. Preparations
   - Prepare the infrastructure
3. Connect to the Bastion Host
4. Configure DRS Settings
5. Configure DRS Agent
6. Installing the Agent
7. Configure Launch Settings
8. Failing Over
9. Clean up resources

## Prerequisites

- An AWS account with permissions to create the resources used in the labs
- Basic familiarity with the AWS Management Console
- [Hugo](https://gohugo.io/installation/) (extended edition) if you want to run the site locally

## Run locally

```bash
git clone --recurse-submodules https://github.com/vanhoangkha/000100-ElasticDR.git
cd 000100-ElasticDR
hugo server
```

Then open http://localhost:1313 in your browser.

## Repository structure

| Path | Purpose |
| --- | --- |
| `content/` | Workshop pages (`*.md` English, `*.vi.md` Vietnamese) |
| `static/` | Images and other static assets |
| `layouts/` | Hugo layout overrides |
| `themes/` | Hugo theme |
| `config.toml` | Site configuration |

## Cost and cleanup

The labs create AWS resources that may incur charges. Complete the **Clean up** chapter when you finish to remove them.

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

To report a security issue, see [SECURITY.md](SECURITY.md).

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
