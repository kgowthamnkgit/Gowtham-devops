# Gowtham-devops

# node-todo-cicd

 Run these commands:

 mkdir Development
 cd Development
 git clone node-todo-cd
 cd node-todo-cicd
 vi Dockerfile
 docker btild -t adarsh8818/node-todo-cicd
 docker run -it -p 8000:8000 "image id"
 docker pull  adarsh8818/node-todo-cicd
 mkdir k8s
 cd k8s
 vi deploy.yml
 minikube start
 kuectl apply -f deploy.yml
 kubectl get pods
 kubectl get pods -o wide
 minikube ssh
 curl -L http://clusterIP:8000
 install helm
 install prometeus
 kubectl expse service --type=NodePort --target-port=9090
 install  grafana
connect to grafana for prometues
create dashbord use mertice cruster ip 
