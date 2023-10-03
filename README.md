# Phonebook k8s | HELM Chart

This repo contains a Helm chart which hosts FLASK - MySQL based phonebook application. 

To learn more about the release, try:

helm status phonebook-chart

To use own images execute as below:

## Deployment
To deploy the Helm repo you need to install helm on your cluster

### Install HELM
Website:
```https://helm.sh/docs/intro/install/```

Run the bash command below

```bash 
curl https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3 | bash 
```

### Checking any repo on your cluster

helm repo ls

### Add the remote repo to your cluster.
```bash
helm repo add <your_repo> https://raw.githubusercontent.com/Golge/phonebook-repo/main 
```

### Final step to make the repo run! 

```bash 
helm install <your_app_name> <your_repo>/phonebook-chart
```
