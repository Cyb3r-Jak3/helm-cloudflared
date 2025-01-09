# Cloudflared Helm Chart

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/cyberjake)](https://artifacthub.io/packages/search?repo=cyberjake)

My Helm chart for Cloudflared.
Inspired from [Cloudflare's Helm Chart](https://github.com/cloudflare/helm-charts) but with a few modifications such as:

- Ability to change the image registry
- Ability to use an existing secret for the tunnel credentials
- Ability to add custom arguments to the tunnel command

## Setup

```bash
helm repo add cyberjake https://helm-charts.cyberjake.xyz
helm repo update
```

## Install

```bash
helm search repo cyberjake
helm install cloudflared cyberjake/cloudflared
```
