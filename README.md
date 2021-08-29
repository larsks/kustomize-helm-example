This is an example of:

- Using the `--enable-helm` flag to `kustomize` to inflate a Helm
  chart as part of the `kustomize build` process, and

- Using patches to modify the resulting output.

This repository requires `kustomize` version 4.3.0 or later. To build
the output:

```
cd overlays/ocp-prod
kustomize build --enable-helm
```
