# Bootstrapping commands

## single node

    kustomize build https://github.com/daringcalf/argo-cd-kustomiza | kubectl apply -f -
##
    curl --silent https://raw.githubusercontent.com/daringcalf/argo-cd-kustomiza/main/margocd-app.yaml | kubectl apply -f -

## ha

    kustomize build https://github.com/daringcalf/argo-cd-kustomiza//ha | kubectl apply -f -
##
    curl --silent https://raw.githubusercontent.com/daringcalf/argo-cd-kustomiza/main/margocd-ha-app.yaml | kubectl apply -f -
