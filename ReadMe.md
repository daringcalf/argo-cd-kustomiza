# Bootstrapping commands
## single node
    kubectl apply -k https://github.com/daringcalf/argo-cd-kustomiza
##
    curl --silent https://raw.githubusercontent.com/daringcalf/argo-cd-kustomiza/main/margocd-app.yaml | kubectl apply -f -
## ha
    kubectl apply -k https://github.com/daringcalf/argo-cd-kustomiza//ha
##
    curl --silent https://raw.githubusercontent.com/daringcalf/argo-cd-kustomiza/main/margocd-ha-app.yaml | kubectl apply -f -
