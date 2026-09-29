# Cryptlex Helm Charts (deprecated)

> **This repository is no longer maintained.** It receives no new chart versions, fixes, or security updates.

The Cryptlex Helm chart is now distributed as an OCI artifact from Docker Hub:

```
oci://registry-1.docker.io/cryptlex/cryptlex-enterprise
```

Installation and upgrade instructions are in the [Kubernetes guide](https://github.com/cryptlex/cryptlex-on-premise/tree/master/kubernetes) of the [cryptlex-on-premise](https://github.com/cryptlex/cryptlex-on-premise) repository.

## Migrating from this repository

If you installed the chart with `helm repo add https://cryptlex.github.io/helm-charts/`, log in to Docker Hub with `helm registry login` and switch your `helm upgrade` commands to the OCI reference above, as described in the [Kubernetes guide](https://github.com/cryptlex/cryptlex-on-premise/tree/master/kubernetes). Keep your release name and namespace; your existing values file keeps working.

For help, [contact us](https://cryptlex.com/contact).
