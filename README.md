
# Solution: turbogitops

Please return to [your solution](https://builder.cloudnativetoolkit.dev/solutions/7443ba01-27e2-40ab-8612-da19e49d644f) to make changes.

This collection of terraform automation bundles has been crafted from a set of Terraform modules created by Ecosytem Lab team part of the IBM Strategic Partnership.

If you have any question please reach out to us on [Discord](https://discord.gg/7sSY9W2cZf).

## Change Log

- **Thu Sep 08 2022** - Initial version

## Description

Solution based on Turbonomic in Quick-Start reference architecture deployed on IBM Cloud with OpenShift Data Foundation as storage option.

## Bill Of Materials

The following is a list of the bill of materials used as part of this solution:

### Infrastructure

| ID | Name | Description | 
| -- | ---- | ----------- |
| 105-ibm-vpc-openshift | [105 - IBM VPC OpenShift QuickStart](https://builder.cloudnativetoolkit.dev/boms/105-ibm-vpc-openshift) | IBM VPC and public Red Hat OpenShift server |
| 210-ibm-portworx-storage | [210 - IBM - Portworx Cluster Storage](https://builder.cloudnativetoolkit.dev/boms/210-ibm-portworx-storage) | Installs Portworx in an IBM cluster |

### Software

| ID | Name | Description | 
| -- | ---- | ----------- |
| 200-ibm-openshift-gitops | [200 - IBM OpenShift GitOps Bootstrap](https://builder.cloudnativetoolkit.dev/boms/200-ibm-openshift-gitops) | Provisions OpenShift GitOps into an existing IBM cluster and bootstraps it to a gitops repository |
| 200-openshift-gitops | [200 - OpenShift GitOps Bootstrap](https://builder.cloudnativetoolkit.dev/boms/200-openshift-gitops) | Provisions OpenShift GitOps (ArgoCD) into an existing cluster and bootstraps it to a gitops repository |
| 202-turbonomic-ibmcloud-storage-class | [202 - Turbonomic Storage Class for IBM Cloud](https://builder.cloudnativetoolkit.dev/boms/202-turbonomic-ibmcloud-storage-class) | GitOps deployment of Storage Class for IBM Cloud OpenShift environment |
| 220-dev-tools | [220 - OpenShift development tools](https://builder.cloudnativetoolkit.dev/boms/220-dev-tools) | Provisions development tools in an OpenShift cluster |
| 250-turbonomic-multicloud | [250 - Turbonomic on OpenShift for Multi Cloud](https://builder.cloudnativetoolkit.dev/boms/250-turbonomic-multicloud) | GitOps deployment of Turbonomic on Multi Cloud environments AWS, Azure and IBM Cloud |


This solution was built with the [Techzone Accelerator Toolkit](https://builder.cloudnativetoolkit.dev/).

    