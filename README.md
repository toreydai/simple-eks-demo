# Simple Amazon EKS Demo

## 创建Nginx Deployment及对应Service
<br>kubectl create -f https://github.com/toreydai/simple-eks-demo/blob/master/nginx-deployment.yml
<br>kubectl create -f https://github.com/toreydai/simple-eks-demo/blob/master/nginx-service-nlb.yml

## 获取NLB DNS进行访问
kubectl get service nginx-service
