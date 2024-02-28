# Install EKS

Please follow the prerequisites doc before this.

## Install using Fargate

```
eksctl create cluster --name demo-cluster-three-tier-1 --region us-east-1
```

## Delete the cluster

```
eksctl delete cluster --name demo-cluster-three-tier-1 --region us-east-1
```

# Create GKE Cluster using CLI
```
gcloud container clusters create my-cluster --num-nodes=3 --machine-type=n1-standard-1 --zone=us-central1-a
```


