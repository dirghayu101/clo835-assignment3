## Deploying a Simple Node.js Application on Kubernetes with ConfigMap

# Objective:
- Deploy a simple Node.js application on a Kubernetes cluster using a ConfigMap to manage environment variables.

# Instructions:
- Step 1: Setup Your Kubernetes Environment
- Start your Kubernetes cluster using Minikube.
- Step 2: Create the Node.js Application
- Write a simple Node.js application in a file named app.js.
- Create a Dockerfile to containerize your Node.js application.
- Build your Docker image and push it to Docker Hub.
- Step 3: Create a Kubernetes Deployment and ConfigMap
- Write a ConfigMap manifest node-app-config.yaml and apply it to create a ConfigMap.
- Write a deployment manifest node-app-deployment.yaml to deploy the Node.js application using the ConfigMap.
- Expose the application using a NodePort service.
- Step 4: Verify the Deployment
- Check the application logs to ensure it is running correctly.
- Access the application using the URL provided by Minikube and verify it displays the correct interval value.

# Submission:
- Submit a brief report that includes:
- A summary of the steps you took as a PDF file containing the following content.
- The URL to your Docker Hub repository.
- The ConfigMap and Deployment YAML files you created.
- A YouTube link with 5 minute presentation, you have to explain all you did in this assignment.

# Evaluation Criteria:
- Correctness: The application should correctly display the interval value set by the ConfigMap.
- Docker and Kubernetes Configurations: The Dockerfile, ConfigMap, and Deployment manifests should be correctly configured.
- Documentation: The report should clearly document the process.


You can use the following Github repository for the codes you need to complete this assignment:

https://github.com/sojoudian/nApp