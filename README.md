# k8s-tp6

```sh
kubectl run  webapp  --image=kodekloud/webapp-color --port 8080 --env APP_COLOR=red

kubectl create deployment nginx-dp --image nginx:1.21.3 --port 80 --replicas=2
kubectl set image deployment/nginx-dp nginx=nginx:latest

kubectl delete deployment/nginx-dp
```
