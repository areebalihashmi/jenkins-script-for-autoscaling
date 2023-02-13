# jenkins-script-for-autoscaling
To create an autoscaling group and adding nodes to existing cluster

The jenkins stages are as below:

Stage 1: Stage Terraform Apply to create new node

Stage 2: Register Nodes with EKS which will register a newly created node
