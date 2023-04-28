1. kubectl apply -f mysql-secret.yaml
2. kubectl apply -f mysqldatabase.yaml
3. kubectl apply -f mysqlservice.yaml
4. kubectl get deployment
5. kubectl get pods
6. kubectl exec --stdin --tty my-sql-deployment-569b9cccc6-jbwz2 -- /bin/bash
7. kubectl exec --stdin --tty <pod_name> -- /bin/bash
8. mysql -p
9. show databases;
