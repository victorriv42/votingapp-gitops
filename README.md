# votingapp-gitops

Dépôt de configuration (GitOps) de l'application example-voting-app.

- `base/` : manifests communs (Deployments, StatefulSet, Services, Ingress, générateur de ConfigMap)
- `overlays/dev/` : namespace vote-dev, 1 réplica, hôtes *-dev.local
- `overlays/prod/` : namespace vote-prod, 2 réplicas de vote, hôtes vote.local / result.local
- `apps/` : Applications Argo CD (ajouté au TP5, étape 6)

