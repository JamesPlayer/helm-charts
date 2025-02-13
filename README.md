# helm-charts

## Usage

[Helm](https://helm.sh) must be installed to use the charts. Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

helm repo add jamesplayer-helm-charts https://jamesplayer.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages. You can then run `helm search repo
jamesplayer-helm-charts` to see the charts.

To install the hello-k8s chart:

    helm install my-hello-k8s jamesplayer-helm-charts/hello-k8s

To uninstall the chart:

    helm uninstall my-hello-k8s
