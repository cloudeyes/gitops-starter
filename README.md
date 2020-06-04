Gitops with Flux - A Starter Project
====================================

This project assumes you have 2 seprate k8s environments
- Local k8s cluster for developers (test purpose only) 
- EKS production clusters (include a staging cluster)

In addtion, you will have 3 different branches 
- dev : will be synchronized to the local k8s clusters.
- stage : will be synchronized to the EKS `staging` cluter.`
- prod : will be synchronized to the EKS 'prod' cluster.

