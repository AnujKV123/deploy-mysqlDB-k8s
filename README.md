# Deploying MySQL on Kubernetes Cluster.
in this repo we learn about how to deploy MySQL Database on kubernetes cluster with persistent volume & persistent volume claim.
#### 1. install kubectl
#### 2. run command : kubectl apply -f mysql-secret.yaml
#### 3. run command : kubectl apply -f pv.yaml
#### 4. run command : kubectl apply -f pvc.yaml
#### 5. run command : kubectl apply -f deployment-db.yaml
#### 6. run command : kubectl apply -f service-db.yaml
#### 7. run command : kubectl exec --stdin --tty <pod_name> -- /bin/bash
#### 7. run command : mysql -p
#### 7. run command : Enter the DB password
### and finally your Database is ready to use ...
