Project page is [here](https://metallb.universe.tf) .

Install MetalLB v0.13+ (CRD-based config) — check the [official docs](https://metallb.universe.tf/installation/) for the latest manifest URL.

`kubectl apply -f https://raw.githubusercontent.com/metallb/metallb/<version>/config/manifests/metallb-native.yaml`

then apply `config.yaml` which creates `IPAddressPool` and `L2Advertisement` resources.
