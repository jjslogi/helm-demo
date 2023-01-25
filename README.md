# Intro

This chart allows to create a namespace and some other associated resources that usually come along with the creation of the namespace such as:
- RoleBindings
- ServiceAccounts
- NetworkPolicies
- Velero Backup Schedules 

# Cheatsheet

```sh
# Dry-run Execution using a different values.yaml
helm install demo-project-test1 \
    ./demo-project-chart \
    -f ./configs/test1.yaml \
    --dry-run
```
