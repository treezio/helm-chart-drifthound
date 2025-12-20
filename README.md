# DriftHound Helm Chart
## Description

This repository contains helm chart to deploy [DriftHound](https://github.com/drifthoundhq/drifthound)

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Release Charts](https://github.com/drifthoundhq/helm-chart/actions/workflows/chart-releaser.yaml/badge.svg?branch=main)](https://github.com/drifthoundhq/helm-chart/actions/workflows/chart-releaser.yaml)

## Requirements

- [Helm](https://helm.sh)

## Usage

```console
helm repo add drifthound https://drifthoundhq.github.io/helm-chart/
```

You list the charts running `helm search repo drifthound`.

## Install Chart

```console
helm install [RELEASE_NAME] drifthoundhq/drifthound
```

## Uninstall Chart

```console
helm uninstall [RELEASE_NAME]
```

## Configuring

Check [values section](./charts/drifthound/README.md/#values) in drifthound chart README

or run:

```console
helm show values drifthound/drifthound
```
