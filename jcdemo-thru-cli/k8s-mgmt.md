kubectl get componentstatuses
kubectl get nodes
kubectl describe nodes [NODE]

## Kubernetes Proxy
kubectl get daemonSets --namespace=kube-system kube-proxy

## Kubernetes DNS
kubectl get deployments --namespace=kube-system kube-dns
kubectl get services --namespace=kube-system kube-dns

## Kubernetes UI
kubectl get deployments --namespace=kube-system kubernetes-dashboard
