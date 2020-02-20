# openshift-learn

## openshift 3.11

- [管理节点](https://docs.openshift.com/container-platform/3.11/admin_guide/manage_nodes.html)

```
禁用调度 oc adm manage-node node1.example.com --schedulable=false

启用调度 oc adm manage-node <node1> <node2> --schedulable
```

- [管理证书](https://docs.openshift.com/container-platform/3.11/install_config/certificate_customization.html#using-certificate-chains)
- [重新部署证书](https://docs.openshift.com/container-platform/3.11/install_config/redeploying_certificates.html)