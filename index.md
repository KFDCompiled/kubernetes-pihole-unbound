# Pi-Hole helm chart

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo and install as follows:

```console
helm repo add KFDCompiled https://mojo2600.github.io/kubernetes-pihole-unbound/
helm upgrade -i pihole KFDCompiled/pihole -f values.yaml
```

