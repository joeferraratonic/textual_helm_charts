# solar-helm
Helm chart repository for deployment of Solar

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add solar https://tonicai.github.io/solar-helm

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
solar` to see the charts.

To install the solar chart:

    helm install solar solar/solar

To uninstall the chart:

    helm delete solar