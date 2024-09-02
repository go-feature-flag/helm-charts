# GO Feature Flag Helm Charts

This repository contains Helm charts for deploying the GO Feature Flag project within a Kubernetes environment.

## Installation

1. **Add the Helm repository:**
   ```bash
   helm repo add go-feature-flag https://charts.gofeatureflag.org
   ```
2. **Update the repository index:**
   ```bash
   helm repo update
   ```
3. **Install the chart:**
   ```bash
   helm install <release-name> go-feature-flag/relay-proxy
   ```

## Configuration
Refer to the `values.yaml` file for customizable options.

## Documentation

For more information, please visit the official GO Feature Flag documentation: https://gofeatureflag.org/docs

## Contributing
We welcome contributions! Please follow the guidelines in the [CONTRIBUTING.md](https://github.com/thomaspoignant/go-feature-flag/blob/main/CONTRIBUTING.md) file.
