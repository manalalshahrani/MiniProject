# MiniProject


Unfortunately, the project is not fully deployed. There are some problems with the connectivity inside Kubernetes. 
The only working component inside the Kubernetes is the sa_frontend using this URL: http://34.69.3.165/
The following URLs are the docker images I pushed to the Docker hub:
1. https://hub.docker.com/repository/docker/malshahr92/sentiment-analysis-frontend
2. https://hub.docker.com/repository/docker/malshahr92/sentiment-analysis-web-app
3. https://hub.docker.com/repository/docker/malshahr92/sentiment-analysis-logic



In order to complete this project, I have tried several deployment settings,
1. deploying and exposing using the YAML files that GKE creates.
2. deploying and exposing using the YAML files that GKE creates with modifying them to resembles what they have in k8s-mastery.
3. deploying and exposing using the YAML files that are in the GitHub repository https://github.com/rinormaloku/k8s-mastery/tree/master/resource-manifests using the Kubernetes command shell.
