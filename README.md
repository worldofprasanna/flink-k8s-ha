# flink-k8s-ha

[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

Flink 1.13 on Kubernetes with HA mode enabled

## Table of Contents

- [Install](#install)
- [Usage](#usage)
- [Maintainers](#maintainers)
- [Contributing](#contributing)
- [License](#license)

## Install

```
# Install helm and kubectl to connect to kubernetes cluster. Then,

helm install flink-ha-test .
```

## Usage

```
# To view the Dashboard UI, use port forwarding
k port-forward <POD-NAME> 8081
```

## Maintainers

[@worldofprasanna](https://github.com/worldofprasanna)

## Contributing

PRs accepted.

Small note: If editing the README, please conform to the [standard-readme](https://github.com/RichardLitt/standard-readme) specification.

## License

MIT © 2021 Prasanna V
