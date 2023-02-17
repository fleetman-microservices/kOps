# Setup a k8s cluster with kOps

kOps (Kubernetes Operations) is an open source tool, designed to ease and automate the creation, deletion, upgrades, and the maintenance of production-grade Kubernetes (k8s) cluster. Additionally, kOps also provisions the necessary cloud infrastructure for the cluster. 

## kOps Configuration

### kOps Prerequisites
* Domain for the required k8s DNS records
* Local environment with: kOps, kubectl and AWS CLI
* IAM user with API credentials
* AWS S3 bucket to store cluster state

