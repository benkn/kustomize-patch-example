# kustomize-patch-example
Example of patching resources using Kustomize

## How to see manifest
To see the raw manifests, run: 
```sh
kustomize build base
```

To see the overlay manifests, run:
```sh
kustomize build overlays/no-network
```

## Examples 
- The [no-network overlay](./overlays/no-network/) removes networking resources.