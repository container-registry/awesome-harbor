
# Awesome Harbor [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Awesome List for Harbor Container Registry related projects, libraries and articles.
## Contents

- [Harbor Project](#harbor_project)
- [Articles](#articles)
- [Project](#projects)
- [Adopters](#adopters)

## Harbor Project

- [Harbor Project Website](https://goharbor.io/)
- [The Harbor Project Blog](https://goharbor.io/) with release notes, tutorials.

## Articles

Awesome Harbor related articles, blog posts.

- [Presentation about Harbor project](https://github.com/ruzickap/k8s-harbor-presentation)
- [Monitoring Harbor](https://github.com/goharbor/perf/wiki/How-to-setup-a-monitoring-environment) - How to guide on monitoring Harbor with cadvisor, prometheus, grafana, jaeger with docker-compose.


## Projects

Harbor related projects and tools.

- [Harbor Operator](https://github.com/goharbor/harbor-operator) - Deploy and also operate Harbor on Kubernetes with this operator.
- [harbor-automation-4k8s](https://github.com/szlabs/harbor-automation-4k8s) - Operator to makes Kubernetes integrate deeper with Harbor with functionalities like auto-inject secrets, mapping between project and namespaces, or rewriting all pull requests to proxy cache.
- [Harbor Sync](https://github.com/moolen/harbor-sync) - Harbor Sync allows you to synchronize your Harbor robot accounts with your Kubernetes cluster.
- [docker-pushrm](https://github.com/christian-korneck/docker-pushrm) - Update your Harbor project README with a simple CLI.
- [GitHub Action for docker-pushrm](https://github.com/christian-korneck/update-container-description-action) - GitHub Action on top of to docker-pushrm allowing you to update the README of a container repo.
- [Mittwald Harbor Operator](https://github.com/mittwald/harbor-operator) - Kubernetes Operator for automated management of Harbor instances
- [harbor-container-webhook](https://github.com/indeedeng-alpha/harbor-container-webhook) - Mutating webhook for Kubernetes, which rewrites container images to use Harbor's proxy cache.
- [Harbor Scanner Adapter for Trivy](https://github.com/aquasecurity/harbor-scanner-trivy) - Allows Harbor to use [Trivy](https://github.com/aquasecurity/trivy) for providing static analysis of vulnerabilities in container images. (It is the default static vulnerability scanner in Harbor >= 2.2.)
- [Harbor Scanner Adapter for Aqua Enterprise](https://github.com/aquasecurity/harbor-scanner-aqua) - Allows Harbor to use Aqua Enterprise ad hoc scanning feature for providing static analysis of vulnerabilities in container images. (Requires licensed Aqua Enterprise platform installation.)
- [Terraform Harbor provider](https://github.com/BESTSELLER/terraform-provider-harbor) - Configure and manage your Harbor instance declaratively with terraform
- [Using Kyvero and Harbor to safeguard production systems](https://github.com/jvanzyl/kyverno-registries) Allow an approved set of external registries to be used by our developers, where the image references are rewritten to use an internal Harbor proxy cache we have for the given external registry.

### SDKs For Harbor

- [Python](https://github.com/container-registry/harbor-python-client-api) Client API, generated from OpenAPI
- [Go](https://github.com/goharbor/go-client) "Official" Client library with golang for accessing Harbor API.
- [Mittwald Goharbor Client](https://github.com/mittwald/goharbor-client) (golang) Client API generated from OpenAPI specifications

## Adopters

Companies and organizations who use Harbor.

- [Mittwald](https://github.com/mittwald) - CMS and Online hosting providers from Germany.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
