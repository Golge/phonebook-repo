# Phonebook k8s | HELM Chart

This repo contains a Helm chart which hosts FLASK - MySQL based phonebook application. 

To learn more about the release, try:

helm status phonebook-chart

To use own images execute as below:

## Deployment

Run this command to install the chart

```bash
helm upgrade --install myapp phonebook-repo/phonebook-chart --set webserver_image=<image-name> --set resultserver_image=<image-name>  
```
