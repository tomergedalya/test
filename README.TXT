helm install finpart-app finpartap/ --values finpartap/values.yaml
kubectl port-forward svc/finpart-chart 8080:8080
