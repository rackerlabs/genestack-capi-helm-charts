# genestack-capi-helm-charts
capi-helm-charts helm repo for genestack helm packages for capi-helm-charts


The charts are available from the `rackerlabs.github.io/genestack-capi-helm-charts` repository:

```sh
helm repo add capi https://rackerlabs.github.io/genestack-capi-helm-charts
helm install my-release capi/openstack-cluster [...options]
```

To list the available versions for the charts:

```sh
helm search repo capi --versions
```

Currently, the following charts are available:

| Chart | Description |
| --- | --- |
| [openstack-cluster](./charts/openstack-cluster) | Deploys a Kubernetes cluster on an OpenStack cloud. |
