## setu aws credentials
aws configure

export AWS_ACCESS_KEY_ID=...
export AWS_SECRET_ACCESS_KEY=...

## EKS Create cluster

eksctl create cluster \                                              
--name test-cluster \
--version 1.22 \
--region eu-central-1 \
--nodegroup-name linux-nodes \
--node-type t2.micro \
--nodes 2
