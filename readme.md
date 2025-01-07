# this is a demo helm chart to integrate with ArgoCD
-->>> we are using Minikube cluser to deploy the ArgoCD.
# Steps to install and configure :

1. Install ACD on k8s cluster.
2. Confire argo cd with application crd file (maintain in git )
    1. Isme sab mention kana hai.
    2. Link to gitrepo.
    3. Self healing and all the features you want.
3. Make changes in any appln file (eg. deployment file ) and Test if argocd is using the correct manifest vesrion

###############################################################
Installing ArgoCD in minikube
1. Create a new namespace : kubectl create namespace argocd
2.  Uska Menifest use krke install the ACD
3.  Do port forwarding to access the UI of argocd.
4.  Get username pass from k8s secrets.
    1. Username : admin
    2. Pass : decode base 64 from k8s secret pass.

##################
# create a sample helm chart in your git , 
