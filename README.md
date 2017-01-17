kubeadm
===============

Setup a kubernetes cluster and tools using kubeadm according to the guide at
http://kubernetes.io/docs/getting-started-guides/kubeadm/

Role Variables
--------------

    kubeadm_network_plugin: Optional. The network plugin to use among the ones present in tasks/network (default: flannel).
    kubeadm_k8s_version: Optional. The kubernetes version to install (default: v1.5.1).
    kubeadm_master_ip: Optional. The ip on which the k8s api server will listen (default: the ip used by ansible to connect).

License
-------

GPLv3

Author Information
------------------

Daniel Zozin
