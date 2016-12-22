kubeadm
===============

Setup a kubernetes cluster and tools using kubeadm according to the guide at
http://kubernetes.io/docs/getting-started-guides/kubeadm/

Role Variables
--------------

    network_plugin: Optional. The network plugin to use among the ones present in tasks/network (default: flannel).
    flannel_arch: Optional. The architecture on which flannel will be installed (default: amd64).
    k8s_version: Optional. The kubernetes version to install (default: v1.5.1).

License
-------

GPLv3

Author Information
------------------

Daniel Zozin
