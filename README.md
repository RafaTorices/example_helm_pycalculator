## Example Repo Helm Chart `pycalc`

## RafaelTorices

This is an example repo for a helm chart for a simple python flask app.

### Resources charts creates

- Deployment
- Service
- Ingress Nginx

### Usage

```bash
helm install example-repo ./pycalc
```

> **NOTE:**
>
> The name os helm chart is `pycalc`.
>
> Values.yaml contains the default values for the chart. You can override these values.

## Helm Chart Repository

This repo is also a helm chart repository named `pycalc`

To add this repo to your helm client, run the following command:

```bash
helm repo add pycalc https://rafaeltorices.github.io/example_helm_pycalculator/
```

You can then install the chart by running:

```bash
helm install demo/pycalc
```

> NOTE:
> This Helm Chart Repository is hosted on GitHub Pages for use with ArgoCD and others CI/CD tools.
