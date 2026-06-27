`kubectl create namespace pihole`

`kubectl apply -f misc/pihole/statefulset.yaml`

PiHole runs as a StatefulSet with 3 replicas, each with its own PVC (longhorn). Adlists and whitelist are managed via the ConfigMap embedded in `statefulset.yaml`.
