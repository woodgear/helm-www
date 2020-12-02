---
title: "Helm Completion - zsh"
---

## helm completion zsh

generate autocompletions script for zsh

### Synopsis


Generate the autocompletion script for Helm for the zsh shell.

To load completions in your current shell session:
$ source <(helm completion zsh)

To load completions for every new session, execute once:
$ helm completion zsh > "${fpath[1]}/_helm"


```
helm completion zsh
```

### Options

```
  -h, --help   help for zsh
```

### Options inherited from parent commands

```
      --debug                       enable verbose output
      --kube-apiserver string       the address and the port for the Kubernetes API server
      --kube-as-group stringArray   Group to impersonate for the operation, this flag can be repeated to specify multiple groups.
      --kube-as-user string         Username to impersonate for the operation
      --kube-context string         name of the kubeconfig context to use
      --kube-token string           bearer token used for authentication
      --kubeconfig string           path to the kubeconfig file
  -n, --namespace string            namespace scope for this request
      --registry-config string      path to the registry config file (default "~/.config/helm/registry.json")
      --repository-cache string     path to the file containing cached repository indexes (default "~/.cache/helm/repository")
      --repository-config string    path to the file containing repository names and URLs (default "~/.config/helm/repositories.yaml")
```

### SEE ALSO

* [helm completion](helm_completion.md)	 - generate autocompletions script for the specified shell

###### Auto generated by spf13/cobra on 29-Oct-2020