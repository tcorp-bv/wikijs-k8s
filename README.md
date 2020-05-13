# wikijs-k8s
Our kubernetes manifests for our wiki. The wiki should be accessible from either https://wiki.tcbv.be or https://wiki.tcorp.me.

## Deployment
The virtualservice.yaml manifest is specific to our architecture. The deployment manifest currently uses sqlite all though we will likely move to postgresql.

The master branch of this repository is synced with our argocd controller into its own namespace.
