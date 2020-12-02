---
title: "Helm Get Values"
---

## helm get values

download the values file for a named release

### Synopsis


This command downloads a values file for a given release.


```
helm get values RELEASE_NAME [flags]
```

### Options

```
  -a, --all             dump all (computed) values
  -h, --help            help for values
  -o, --output format   prints the output in the specified format. Allowed values: table, json, yaml (default table)
      --revision int    get the named release with revision
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

* [helm get](helm_get.md)	 - download extended information of a named release

###### Auto generated by spf13/cobra on 29-Oct-2020