# fleet-infra

```shell
flux bootstrap github --owner=takokun778 --repository=fleet-infra --branch=main --path=./clusters/my-cluster --personal
```

```shell
gitops create dashboard ww-gitops --password=password --export > ./clusters/my-cluster/weave-gitops-dashboard.yaml
```
