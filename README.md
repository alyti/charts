## Usage [![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/alyti)](https://artifacthub.io/packages/search?repo=alyti)

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add alyti https://alyti.github.io/charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
alyti` to see the charts.

To install the misskey chart:

    helm install my-misskey alyti/misskey

To uninstall the chart:

    helm delete my-misskey
