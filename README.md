# ds-iscsi

This patch adds a DaemonSet ensures the iSCSI daemon is started on every nodes of the cluster

The DS has been tested against GKE, Rancher and Kubernetes vanilla on top of Centos 7

The two patches are minor fixes to the csi-powermax installer to work with GKE :
* `0001-Support-gke.patch` applies to [csi-powermax v1.1.0](https://github.com/dell/csi-powermax/tree/v1.1.0) for Anthos 1.1 & 1.2
* `0001-Support-gke-1.3.patch` applies to [csi-powermax v1.2.0](https://github.com/dell/csi-powermax/tree/v1.2.0) for Anthos 1.3
