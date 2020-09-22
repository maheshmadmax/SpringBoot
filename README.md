# SpringBoot

kubectl apply -f rds-secret.yaml

kubectl apply -f app-deployment.yaml

kubectl expose deployment/springboot --external-ip=<cluster ip> --port=8080 --target-port=8080
