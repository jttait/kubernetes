1. sudo systemctl start docker
1. minikube start
1. eval $(minikube docker-env)
1. docker build . -t myapp/testnodeapp
1. helm install test-app .
1. kubectl get pods
1. There should be 2 pods
1. Change replicaCount to 3 in values.yaml
1. helm upgrade test-app .
1. kubectl get pods
1. There should be 3 pods
1. helm uninstall test-app
1. kubectl get pods
1. There should be 0 pods
