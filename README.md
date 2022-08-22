# action-eks-connect

Github Action that setup Kubectl, Helm, Helmfile and connect to an EKS cluster

| **Input**               | Description                           | Default     |
| ----------------------- | ------------------------------------- | ----------- |
| `kubectl-version`       | Kubectl version to install            | `v1.22.6`   |
| `helm-version`          | Helm version to install               | `v3.7.0`    |
| `helmfile-version`      | Helmfile version to install           | `v0.144.0`  |
| `aws-access-key-id`     | AWS access key ID                     |             |
| `aws-secret-access-key` | AWS secret access key                 |             |
| `aws-region`            | AWS region                            | `eu-west-1` |
| `eks-cluster-name`      | Name of the EKS cluster               |             |
| `kube-context-name`     | Name of the kubectl context to create |             |
