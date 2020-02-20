# openshift-learn

## openshift 3.11

- [manage_nodes](https://docs.openshift.com/container-platform/3.11/admin_guide/manage_nodes.html)

```
禁用调度 oc adm manage-node node1.example.com --schedulable=false

启用调度 oc adm manage-node <node1> <node2> --schedulable
```