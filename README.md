## tomcat-server

#### To expose container port to external service

kubectl expose deployment tomcat-deployment --type=NodePort

#### To display port ip address

minikube service tomcat-deployment --url

