# k8s-ollama
microk8s.enable dns hostpath-storage ingress nvidia
microk8s.kubectl create ns ollama
microk8s.kubectl apply -f .
