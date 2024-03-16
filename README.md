# Kubernetes Lab Homework

## Description
This project is a homework assignment. It includes configuration files for deploying a FastAPI application on a Kubernetes cluster using a Deployment and a NodePort Service.

## How to Run

1. Apply the deployment configuration:
    ```bash
    kubectl apply -f fastapi-deployment.yaml
    ```
2. Apply the NodePort service configuration:
    ```bash
    kubectl apply -f fastapi-nodeport-service.yaml
    ```
3. Check the status of the pods:
    ```bash
    kubectl get pods
    ```


## Explanation
I did the homework, the NodePort service should look something like this, but I can't test it because I'm getting an ImagePullBackOff error when I run 'kubectl get pods'. I know you've mentioned how to solve this previously, but I forgot and couldn't resolve it. Sorry for the trouble. I would be happy to discuss this further after your review. Best of luck!
