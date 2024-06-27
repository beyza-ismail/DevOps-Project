# DevOps-project
Project for the course Continuous Integration and Continuous Delivery

  Building the docker image: docker build -t="beyza201511/devops-project:latest" .
  Docker Orchestration: docker compose up
  Kubernetes commands:
* k3d cluster create devopscluster -p "8080:80@loadbalancer"
* kubectl apply -f namespace.yml
* kubectl apply -f mongo.yml
* kubectl apply -f springboot-app.yml
* kubectl config set-context --current --namespace=devops
