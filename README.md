# home-controller

[![Documentation](https://pkg.go.dev/badge/github.com/go-zen-chu/golang-template)](http://pkg.go.dev/github.com/go-zen-chu/golang-template)
[![Actions Status](https://github.com/go-zen-chu/golang-template/workflows/main/badge.svg)](https://github.com/go-zen-chu/golang-template/actions)
[![Actions Status](https://github.com/go-zen-chu/golang-template/workflows/check-pr/badge.svg)](https://github.com/go-zen-chu/golang-template/actions)
[![GitHub issues](https://img.shields.io/github/issues/go-zen-chu/golang-template.svg)](https://github.com/go-zen-chu/golang-template/issues)

Kubernetes controller for doing all stuffs for home environment.

## init

```console
kubebuilder init --domain amasuda.xyz --repo github.com/go-zen-chu/home-controller

kubebuilder create api --group telemetry --version v1 --kind SwitchBot
```
