# kube-dashboard
Setup kubernetes dashboard - [https://github.com/kubernetes/dashboard/blob/master/docs/user/access-control/creating-sample-user.md]

### Getting a Bearer Token for ServiceAccount
```
kubectl -n kubernetes-dashboard create token admin-user
```
