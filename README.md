# Reactor Krew Index

Temporary Krew Index repository until we get Reactor integrated into the official Krew Index.

This repository is automatically updated on tagged releases to the [Reactor](https://github.com/kube-reactor/core) project.

## Requirements

This repository requires Krew installed into your local kubectl installation.

See [installing Krew](https://krew.sigs.k8s.io/docs/user-guide/setup/install/) for information on how to install Krew for your OS.

## Usage

```bash
#
# Add Reactor Krew Index to the local Krew installation
#
kubectl krew index add reactor https://github.com/kube-reactor/krew-index.git

#
# Install the Reactor Kubectl plugin
#
kubectl krew install reactor/reactor
```