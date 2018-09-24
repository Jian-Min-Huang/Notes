##### command
* kubectl version

* kubectl config view
* kubectl config current-context
* kubectl config get-contexts
* kubectl config use-context xxx

* kubectl cluster-info

* kubectl create namespace develop
* kubectl get namespace

* kubectl get pods --namespace=kube-system
* kubectl get pod -o wide
* kubectl get services --namespace=kube-system
* kubectl get deployments --namespace=kube-system

* kubectl get nodes

* kubectl port-forward kubernetes-dashboard-7798c48646-ctrtl 8443:8443 — namespace=kube-system
* kubectl run hello-nginx --image=nginx --port=80

* kubectl describe pods hello-nginx-5d47cdc4b7-wxf9b --namespace=default
* kubectl describe services hello-nginx --namespace=default

* kubectl delete pods hello-nginx-5d47cdc4b7-wxf9b --namespace=default

* kubectl scale --replicas=3 deployment/hello-nginx

* kubectl apply -f [resources file/folder][namespace]
* kubectl create -f [resources file/folder][namespace]
