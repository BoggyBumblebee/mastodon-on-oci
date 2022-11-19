# Mastodon on OCI (Oracle Cloud Infrastructure) Template

The purpose of this project is to lay down a complete, secure, installation of Mastodon on Oracle Cloud Infrastructure (OCI). I'm happy to accept contributions to this project. I first made sure that there wasn't anyone else doing this at the current time.

## Antecedents & Acknowledgments

There is a project to do the same on AWS by [Andreas Wittig](https://github.com/andreaswittig), which you can find at https://github.com/widdix/mastodon-on-aws, I've used that as a guide for this.

## Dependencies

- An OCI account https://cloud.oracle.com

The services required under OCI:

- VCN
  - Internet Gateway
  - NAT Gateway
  - Load Balancer
- Compute Instances
- OKE
- Object Storage
- ...

The Open Source components we will use:

- Terraform
- PostgreSQL
- Redis
- Elastic
- ...

## Useful Links

These are some of the documentation I'm using to pull this together:

- [OCI - Deploy a PostgreSQL database](https://docs.oracle.com/en/solutions/deploy-postgresql-db/index.html)
- [OCI - Deploy a highly available, distributed cache using Redis](https://docs.oracle.com/en/solutions/deploy-redis-cluster/)
- [Deploying Elasticsearch on Oracle Cloud Infrastructure Using a Terraform Template](https://blogs.oracle.com/cloud-infrastructure/post/deploying-elasticsearch-on-oracle-cloud-infrastructure-using-a-terraform-template)

## Installation

TBD

## Technical Debt Badges

TBD
