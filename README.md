# publish

A Chart that can be used to publish markdown files as a static website using [Quartz v4](https://github.com/jackyzha0/quartz) and nginx.

## Build

```bash
helm registry login ghcr.io -u felixZmn
helm package .
helm push *.tgz oci://ghcr.io/felixzmn/helm
```
