# automate provisioing eks with terraform 

## steps

##### 1. Create EKS IAM role on AWS and link to  prject using "aws configure"
##### 2. create VPC for worker nodes
##### 3. create EKS cluster (master nodes)
##### 4. connect kubectl with the EKS cluster
##### 5. connect EC2 IAM role for the node group
##### 6. create node group and attachto the EKS cluster
##### 7. configure auto-scaling 
##### 8. deploy application to EKS cluster


### Next Steps

### Update Kubeconfig (/Users/username/.kube/config) gets updated
    aws eks update-kubeconfig --name myapp-eks-cluster --region eu-west-2

#### to get a list of deployed nodes from aws 

    kubectl get pod

#### apply nginx-config.yaml 

    kubectl apply -f nginx-config.yaml