# Wordpress GitOps Rancher

```yaml
kind: GitRepo
apiVersion: fleet.cattle.io/v1alpha1
metadata:
  name: wp-rancher
  namespace: fleet-default
spec:
  repo: https://github.com/roberto-farias/wp-rancher
  paths:
  - deploy
```
