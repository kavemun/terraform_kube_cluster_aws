
To update kubeconfig after creation of Kube cluster on AWS, Run:-

aws eks update-kubeconfig --name terraform-eks-demo  --region ap-southeast-1 --kubeconfig ~/.kube/config
