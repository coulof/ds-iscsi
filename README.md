# ds-iscsi

This patch adds a DaemonSet ensures the iSCSI daemon is started on every nodes of the cluster

The DS has been tested against GKE and Kubernetes vanilla on top of Centos 7

The rest of the patch is minor fixes to the csi-powermax installer to work with GKE or Rancher. It applies to [csi-powermax v1.1.0](https://github.com/dell/csi-powermax/tree/v1.1.0)
