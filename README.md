# gbs-gitops

This repo is monitored by kapp-controller at the "config" path to apply any manifests that show up there on the main branch.

Click [here](https://github.com/cdelashmutt-pivotal/gbs-gitops/new/main?filename=config/new-namespace.yaml&message=New%20Developer%20Namespace&value=apiVersion%3A%20v1%0Akind%3A%20Namespace%0Ametadata%3A%0A%20%20labels%3A%0A%20%20%20%20apps.tanzu.vmware.com%2Ftap-ns%3A%20%27%27%0A%20%20name%3A%20new-namespace) to add a new namespace for development.