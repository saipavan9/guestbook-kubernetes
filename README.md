# guestbook-kubernetes
Deploying guestbook using kubernetes in Google Cloud

## Step-1 : Deploying Google Cloud cluster
Create a default kubernetes cluster in google cloud.
Use this link to create a kubernetes cluster: https://cloud.google.com/kubernetes-engine/docs/how-to/creating-a-cluster
## Step-2: Creating Deployments and Services
Clone this repo to the VM instance. Go to the repo directory.
Run the following command
 `kubectl create -f .` (Don't forget the period at the end)

This creates all the deployments and services in the cluster

Go to ```Services & Ingress``` in the GCP console under kubernetes engine:
Click on the endpoint link provided by guestbook-service.

Guest Book application is done.

