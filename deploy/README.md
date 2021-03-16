# Wordpress Rancher Example

```yaml
kind: GitRepo
apiVersion: fleet.cattle.io/v1alpha1
metadata:
  name: simple
  namespace: fleet-default
spec:
  repo: https://github.com/roberto-farias/wp-rancher
  paths:
  - deploy
```
