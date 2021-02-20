# My Codespace

[Twitter: @stvansolano](https://twitter.com/stvansolano)

## Do you like it? Give a Star! :star:

If you like or are using this project to learn or start your own solution, please give it a star. I appreciate it!

A ready-to-use, templated GitHub Codespace that I regularly use for VS Code on GitHub (Codespaces).

## Batteries included

- Docker
- Kubernetes (WIP)
- NodeJS
- .NET

Extensions

- Docker
- Kubernetes

## k3d commands

```
k3d cluster create mycluster \
    && k3d kubeconfig merge mycluster --kubeconfig-switch-context
```

## Grab some AKS samples!
- https://github.com/stvansolano/azure-voting-app-redis
- Deploy an AKS Cluster - [Microsoft Docs](https://docs.microsoft.com/en-us/azure/aks/kubernetes-walkthrough/?&WT.mc_id=DT-MVP-5002082)
- AKS Workshop - [Microsoft Learn - https://docs.microsoft.com/en-us/learn/modules/aks-workshop](https://docs.microsoft.com/en-us/learn/modules/aks-workshop/?&WT.mc_id=DT-MVP-5002082)