PiHole runs as a StatefulSet with 3 replicas, each with its own PVCs provisioned automatically by Longhorn.
Adlists and whitelist are managed via the ConfigMap embedded in `misc/pihole/statefulset.yaml`.

## Deploy

`kubectl create namespace pihole`

`kubectl apply -f misc/pihole/statefulset.yaml`
