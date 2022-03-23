# Anthos Config Management Essentials

This repository contains a recommended baseline configuration
for using [Anthos Config Management](https://cloud.google.com/anthos/config-management) (ACM).

You can configure [Config Sync](https://cloud.google.com/anthos-config-management/docs/config-sync-overview) with this repo to get:

- [CIS Constraints](https://github.com/GoogleCloudPlatform/acm-policy-controller-library/tree/master/bundles/cis-k8s-v1.5.1) for Policy Controller

For exploring ACM in more depth, numerous [other samples](https://github.com/GoogleCloudPlatform/anthos-config-management-samples) are available.

## Requirements

This repository requires [Policy Controller](https://cloud.google.com/anthos-config-management/docs/how-to/installing-policy-controller) to be installed on your cluster,
with [referential constraints](https://cloud.google.com/anthos-config-management/docs/how-to/creating-constraints#referential) and the [constraint template library](https://cloud.google.com/anthos-config-management/docs/reference/constraint-template-library) enabled.
