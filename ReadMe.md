# Bootstrapping commands
## single node
    kubectl apply -k https://github.com/daringcalf/argo-cd-kustomiza
##
    kubectl apply -f https://raw.githubusercontent.com/daringcalf/argo-cd-kustomiza/main/margocd-app.yaml
## ha
    kubectl apply -k https://github.com/daringcalf/argo-cd-kustomiza//ha
##
    kubectl apply -f https://raw.githubusercontent.com/daringcalf/argo-cd-kustomiza/main/margocd-ha-app.yaml
