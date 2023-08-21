# kubernetes

captain log du 21 aout 2023 :

https://storage.googleapis.com/minikube/releases/latest/minikube-installer.exe

kubectl pour windows: https://dl.k8s.io/release/v1.28.0/bin/windows/amd64/kubectl.exe


curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
sudo install kubectl /usr/local/bin/kubectl

curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube

kubectl run nginx --image=nginx --restart=Never
kubectl get pods
