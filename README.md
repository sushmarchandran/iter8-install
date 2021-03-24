# iter8-install

## Iter8
Iter8 documentation is available [here](https://iter8.tools).

## Iter8 install manifests
This repo provides Kustomizable Iter8 install manifests and supports the following goals.

- [x] Multi domain install
- [x] Multi-db install (note: nothing special is needed to support this, since this is supported by Iter8 v2alpha2 API by design)
- [x] Easy install using `kubectl`
  - [x] must not require Kustomize as a pre-req for installation
  - [x] must enable Iter8 tutorials
- [x] Support Kustomizable install (list is in the order of importance)
  - [x] Optional Prometheus add-on
  - [x] Kustomizable Prometheus URL
  - [x] Kustomizable namespace
  - [x] Optional Kubernetes stacks
  - [x] Kustomizable RBAC
