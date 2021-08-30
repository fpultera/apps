## Need install kubernetes clster
## Need install argcd

- Run this command with the argcd cli and automatic install three components of argo-event.
url: https://argoproj.github.io/argo-events/installation/

argocd app create argo-events --repo https://github.com/fpultera/apps.git --path "argo-events" --dest-namespace argo-events --dest-server https://kubernetes.default.svc
