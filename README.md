# DriftHound Helm Chart
## Description

This repository contains helm chart to deploy [DriftHound](https://github.com/treezio/drifthound)

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Release Charts](https://github.com/treezio/helm-chart-drifthound/actions/workflows/chart-releaser.yaml/badge.svg?branch=main)](https://github.com/treezio/helm-chart-drifthound/actions/workflows/chart-releaser.yaml)

## Requirements

- [Helm](https://helm.sh)

## Usage

```console
helm repo add drifthound https://treezio.github.io/helm-chart-drifthound
```

You list the charts running `helm search repo drifthound`.

## Install Chart

```console
helm install [RELEASE_NAME] treezio/drifthound
```

## Uninstall Chart

```console
helm uninstall [RELEASE_NAME]
```

## Configuring

Check [values.yaml](./charts/drifthound/values.yaml) file or run:

```console
helm show values drifthound/drifthound
```
