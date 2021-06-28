# Applications for your new tenant?
This repo contains a template for a repo holding applications for a tenant.
The repo contains Helm chart config used by Argo to deploy services.

## What should this be used for?
As a template for a new repo containing Helm charts for Argo.

This repo contains:
- test-website (this is just to show how to add a simple application - This should be deleted)

## Structure of a application
- Folder 'apps' contain a list of all the application Argo should take care of.
- All applications have there one folder (like test-website)
  - This folder contains 
    - Chart.yaml - Info about the Helm Chart to use
    - values.yaml - Common values config of the Helm Chart
    - values-prod.yaml - Values only used in PROD like ingress URLs
    - values-test.yaml -  Values only used in TEST like ingress URLs

## Get started
- Use this template-repository to create a new git-repository for the new tenants own applications
- Run the script `sh setup.sh <<tenant>>`. This will replace all places with test-kunde, with the provided tenant.
