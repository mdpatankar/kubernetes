# Advance Cloud Workshop 


## 0. Register on IBM Cloud

https://ibm.biz/BdzPaf


After successful registration Login into your account. 


## 1. Convert the IBM Cloud Lite account to Trial account

You will be provided with PROMO Code. 
Account -- Apply Promo Code

For instructions on how to apply the codes, 
review this page
[IBM Cloud Sign up and PROMO Code](https://cloud.ibm.com/docs/account?topic=account-codes#codes)


## 2. Provision a Kubernetes Cluster on IBM Cloud

From Dashboard menu, select Kubernetes.

<img src="./img/k8s-1.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 5px;" />

After that click on "Create Cluster", you will be asked following details to enter.
a - Select Free Cluster
b - Give a cluster name
c - Select Geography as North America and Select Dallas with default resource group
     
<img src="./img/k8-2.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />
     
Once the cluster is provisioned, Cluster will be shown in Normal State. 
     
<img src="./img/k8-3.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />     


## 3. Access Kubernetes Cluster using Web Terminal

Once the cluster is provisioned, the kubernetes client CLI `kubectl` needs to be
configured to talk to the provisioned cluster.

This can also be done using your local desktops. You will have to install IBM Cloud Plugin Tools for doing that.

For this lab, you will be using Web Terminal, to work with your cluster. So installations on client machines is not required.
This feature is in beta currently. 

a. Access the Cluster, and go to Cluster details
<img src="./img/webterm1.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />   

b. Click on "Web terminal(beta) "
<img src="./img/webterm2.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" /> 

c. Web based terminal opens at the bottom of the browser.     
<img src="./img/webterm3.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />       
     
     
Once your open the Web based terminal, you are ready to deploy your first application, `guestbook`.

