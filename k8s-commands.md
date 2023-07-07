### kubectl apply commands in order

    kubectl apply -f surveysolution.yaml

### kubectl get commands
     
    kubectl get pod --watch
    kubectl get pod -o wide
    kubectl get service
    kubectl get secret
    kubectl get all | grep mongodb

### kubectl debugging commands

    kubectl describe pod <podname>
    kubectl describe service <servicename>
    kubectl logs <pod name>

### give a URL to external service in minikube

    minikube service surveysolutionservice