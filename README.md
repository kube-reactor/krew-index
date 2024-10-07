# Zimagi Krew Index

Temporary Krew Index repository until we get Reactor integrated into the official Krew Index.

## Requirements

This repository requires Krew installed into your local kubectl installation.

See [Installing Krew](https://krew.sigs.k8s.io/docs/user-guide/setup/install/) for information on how to install Krew or your OS

## Usage

```bash
#
# Add Zimagi Krew Index to the local Krew installation
#
kubectl krew index add zimagi https://github.com/zimagi/krew-index.git

#
# Install the Reactor Kubectl plugin
#
kubectl krew install reactor
```