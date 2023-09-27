# observability-openshift

observability-openshift

# commands

kubectl apply -f deployment.yml

kubectl create -f service.yml

# Local

kubectl port-forward service/hexagonal-arch-poc-go-service 8080:8080
