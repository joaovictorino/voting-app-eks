# Sample voting application hosting with Elastic Kubernetes Services (EKS)

Requirements

- EKS cluster (https://github.com/joaovictorino/terraform-eks)

Deploy web application

```sh
kubectl apply -f k8s
```

Get HTTP application ports and external IPs

```sh
kubectl get svc -n laboratorio
```

And then access the application in browser!
