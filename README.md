# k8s-homelab

My Kubernetes learning journey, week by week, on a single-node **k3s** cluster (Debian 13).
Each `weekNN/` folder holds the manifests I wrote that week, and the log below says what I learned.

## Log

### Week 01: Fundamentals
- Installed k3s on Debian 13
- Wrote an nginx **Deployment** (2 replicas) and a **NodePort Service** (`week01/`)
- Completed the Killercoda "Kubernetes 101" labs

## Try it

```bash
kubectl apply -f week01/
kubectl get pods,svc
```

## Related

My larger project, where I deploy a Django app to k3s with a Helm chart I wrote, Traefik ingress and Prometheus/Grafana monitoring: [django-cicd-pipeline](https://github.com/hussainshaqsi/django-cicd-pipeline).
