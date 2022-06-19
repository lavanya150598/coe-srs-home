# coe-repo-home

**Home Repo - Accumulated Information on all the other repos in the Org**

![image](https://user-images.githubusercontent.com/100637276/174426470-144d0129-1fbf-426c-9d7e-2966da2192b0.png)

**CI/CD Flow Diagram**

![image](https://user-images.githubusercontent.com/100637276/174463169-6d6c5b3f-0981-4211-b024-9e36680ab903.png)

***How to Setup Workload Identity Federation? ***
(A Secure Invisible way of authentication external applications to GCP Services)
https://cloud.google.com/iam/docs/configuring-workload-identity-federation#gcloud

***How to Connect to GCP from your Terminal***
1. Install GCloud CLI

https://cloud.google.com/sdk/docs/install#linux

2. Authenticate your Terminal/Laptop to connect to GCP
```
gcloud auth login
```
A Browser will be opened, select the user id and then allow permissions to connect

3. Set the project to "Your Project ID", in the case here it is "coe-srs-2022"

```
gcloud config set project coe-srs-2022
```
4. Check the Config

***HOW to Install Docker helpers and connect to GCP and then Push to GAR***

https://cloud.google.com/artifact-registry/docs/docker/pushing-and-pulling
