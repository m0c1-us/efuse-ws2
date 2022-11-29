# ef-ws2
#install using kubectl files
kubectl apply -f whoami-deployment.yaml
kubectl apply -f whoami-service.yaml
kubectl apply -f whoami-ingress.yaml
#
#
#install with helm
helm repo add traefik https://helm.traefik.io/traefik
helm repo update
helm install traefik traefik/traefik
