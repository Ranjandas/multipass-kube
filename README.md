# multipass-kube

Use multipass to setup Kubernetes clusters for learning.

## Usage

Spin up multipass vm instances using the cloud-init file provided to ease the setup of hosts.

```
multipass launch -n <node_name> -c 2 --cloud-init cloud-init.yaml bionic
```

> NOTE: The cloud-init is written for Ubuntu Bionic
