# XL ML Test

Cloud **Accel**erated **M**achine **L**earning Tests

To generate and deploy Kubernetes YAMLs from the templates, run the following:

```bash
jsonnet -S templates/build.jsonnet -m k8s/gen
kubectl apply -f k8s/gen
```