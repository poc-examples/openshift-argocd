# openshift-argocd

Steps

- Create namespace
- Create docker secret
- Create github secret
- Install ARGOCD
- Install ARGOCD Image updater
- Create autoupdate branch
- Create Application
- Check logs with 
    - oc logs deploy/test-website-deployment -n openshift-gitops
