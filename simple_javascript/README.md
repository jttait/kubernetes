1. sudo systemctl start docker
1. minikube start
1. eval $(minikube docker-env)
1. docker build . -t myapp/testnodeapp
1. kubectl create -f deployment.yaml
1. kubectl get pods
1. kubectl create -f service.yaml
1. minikube tunnel
1. Open another terminal
1. kubectl get service
1. Open the CLUSTER-IP for test-app-service in a browser
1. It will print hello, world
