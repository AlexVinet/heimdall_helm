# heimdall_helm
Heimdall helm chart.

**heimdall_helm**

## installing heimdall_helm

Install heimdall service with the following commands:
>You need to install [nfs.csi.k8s.io](https://github.com/kubernetes-csi/csi-driver-nfs) driver to use NFS before proceeding with the deluge installation, or use your own nfs driver.

```
git clone https://github.com/AlexVinet/deluge_helm.git
cd heimdall_helm/heimdall/
Modify the pv.
helm install heimdall -f values.yaml .
```

>\*\*Note: You need to modify the pv.yaml with your own config.\*\*