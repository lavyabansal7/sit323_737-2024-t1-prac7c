### Interacting with Kubernetes

#### Overview
This guide continues from the previous task (6.1P) and focuses on interacting with the deployed application on the Kubernetes cluster.

**1. Create Kubernetes Cluster**
   - Follow the instructions in the repository `sit323_737-2024-t1-prac7p` to create a Kubernetes cluster.

**2. Interact with the Deployed Application**
   - Verify that the application is running by checking the pods and services:
     ```bash
     kubectl get pods
     kubectl get services
     ```
   - Access the application in a web browser by navigating to `localhost:<local port>`

