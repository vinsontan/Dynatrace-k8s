# Setting up your Google Kubernetes Environment (GKE)

### 1. Sign up for a Google Cloud Platform Account

Head over to https://cloud.google.com/free/ and sign up for a free GCP account with your existing Google account. 

You can also signup for a new Google Account if you don't have one

Upon signup, you will have free credits tied to your GCP account. (12 months + 400AUD)

![alt text](https://github.com/Nodnarboen/HOT-k8s/blob/master/assets/Picture1.png)

### 2. Enable Kubernetes Engine API 

You will also need to <b>Enable your API Billing</b> with Kubernetes Engine API 

![alt text](https://github.com/Nodnarboen/HOT-k8s/blob/master/assets/Picture3.png)

Search for it in the top search menu if you don't see the <b>Enable your API Billing</b> option

### 3. Activate Cloud Shell

![alt text](https://github.com/Nodnarboen/HOT-k8s/blob/master/assets/Picture4.png)

Click on the Terminal Icon on the top right

A Cloud based Terminal lookalike will appear at the bottom of the page

We will start setting up our GKE Cluster 

### 3. Create your GKE Cluster

![alt text](https://github.com/Nodnarboen/HOT-k8s/blob/master/assets/Picture5.png)

Choose your GKE cluster based on https://cloud.google.com/compute/docs/regions-zones/#available

For example for Australia Southeast, the command will be <b>gcloud config set compute/zone australia-southeast1-a</b>

Create your GKE cluster named <b>apacbootcamp2019</b> with the following command

<b>gcloud container clusters create apacbootcamp2019 --no-enable-legacy-authorization</b>

:arrow_up: [Back to TOC](/README.md)
