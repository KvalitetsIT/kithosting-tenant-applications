# Applications for your new tenant?
This repo contains a template for a repo holding applications for a tenant.
The repo contains Helm chart config used by Argo to deploy services.

## What should this be used for?
By following the guide here https://github.com/KvalitetsIT/kithosting-k8s/tree/master/deployment/multitenancy you should end up at this repository at some point.

This repo contains:
- test-website (this is just to show how to add a simple application - This should be deleted)

## Get started
- Use this template-repository to create a new git-repository for the new tenants own applications
- Run the script `sh setup.sh <<tenant>>`. This will replace all places with test-kunde, with the provided tenant.
