# mini-olx

> A simple introduction to Kubernetes using Minikube

## How to setup
* Clone the project
* Start minikube with `minikube start`
* Apply all k8s/* files using `kubectl apply -f <filename>` starting with `kubectl apply -f k8s/namespaces/mini-olx.yaml` first
* Check if environment variables (`IMAGE_PATH` and `REACT_APP_API_BASE`) are correct using `minikube service backend --url -n mini-olx`
* Run your favorite browser into `minikube service frontend --url -n mini-olx` and wait a little

## References

[OLX Women Workshop 2022](https://github.com/isapms/olx-women-workshop-2022-all)  
[OLX Women Workshop 2022 Frontend](https://github.com/franfaccin/olx-women-workshop-2022-frontend)  
[OLX Women Workshop 2022 Backend](https://github.com/isapms/olx-women-workshop-2022-backend)  
[Mini OLX](https://git.naspersclassifieds.com/isabel.santos/mini-olx)