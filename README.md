# Simple Example

This example will deploy the [Kubernetes sample guestbook](https://github.com/kubernetes/examples/tree/master/guestbook/) application.
The app will be deployed into the `default` namespace.

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
