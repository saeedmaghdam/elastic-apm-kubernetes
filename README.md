# Deploy Elastic ECK in your Kubernetes cluster

### Install custom resource definitions
`kubectl create -f https://download.elastic.co/downloads/eck/2.6.1/crds.yaml`

### Install the operator with its RBAC rules
`kubectl apply -f https://download.elastic.co/downloads/eck/2.6.1/operator.yaml`

### Deploy yaml files
- [elk-stack.yaml](./elk-stack.yaml)
- [kibana-ingress.yaml](./kibana-ingress.yaml)
- [elasticsearch-ingress.yaml](./elasticsearch-ingress.yaml)
- [apm-ingress.yaml](./apm-ingress.yaml)

## Reference
[Deploy ECK in your Kubernetes cluster](https://www.elastic.co/guide/en/cloud-on-k8s/current/k8s-deploy-eck.html) 