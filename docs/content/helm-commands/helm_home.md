+++
title = "helm home"
weight = "15"

tags = ["commands"]
section = "helm-commands"
categories = ["helm-commands"]
type = "page"

slug = "helm-home"

[menu.main]
  url = "helm-home"
  parent = "helm-commands"

+++

## helm home

displays the location of HELM_HOME

### Synopsis



This command displays the location of HELM_HOME. This is where
any helm configuration files live.


```
helm home
```

### Options inherited from parent commands

```
      --debug                     enable verbose output
      --home string               location of your Helm config. Overrides $HELM_HOME (default "~/.helm")
      --host string               address of tiller. Overrides $HELM_HOST
      --kube-context string       name of the kubeconfig context to use
      --tiller-namespace string   namespace of tiller (default "kube-system")
```

### SEE ALSO
* [helm](#helm)	 - The Helm package manager for Kubernetes.