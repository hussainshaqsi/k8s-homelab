# k8s-homelab

Mon parcours d'apprentissage de Kubernetes, semaine par semaine, sur un cluster **k3s** à un seul nœud (Debian 13).
Chaque dossier `weekNN/` contient les manifestes écrits cette semaine-là, et le journal ci-dessous résume ce que j'y ai appris.

## Journal

### Semaine 01 : Les bases
- Installation de k3s sur Debian 13
- Écriture d'un **Deployment** nginx (2 réplicas) et d'un **Service NodePort** (`week01/`)
- Labs Killercoda « Kubernetes 101 » terminés

## Essayer

```bash
kubectl apply -f week01/
kubectl get pods,svc
```

## Voir aussi

Mon projet principal, où je déploie une application Django sur k3s avec un chart Helm écrit par moi, un Ingress Traefik et une supervision Prometheus/Grafana : [django-cicd-pipeline](https://github.com/hussainshaqsi/django-cicd-pipeline).
