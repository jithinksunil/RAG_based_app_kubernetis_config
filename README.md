<!-- Add the environment variable for the nest and python services in the /infra/secrets/nest-backend-secret.yaml and /infra/secrets/python-backend-secret.yaml -->
<!-- Apply secrets -->
kubectl apply -f infra/secrets/


<!-- Apply rest of the deployments and services -->
kubectl apply -k infra/
