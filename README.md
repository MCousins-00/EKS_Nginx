# EKS_Nginx

Step 1 Pull respository #git clone https://github.com/MCousins-00/EKS_Nginx.git

Step 2 #cd EKS_Nginx.git

Step 3 Run #terraform init

Step 4 Run command below to verifiy the infractucture that will be created VPB, Secuirity groups and an EKS cluster
#terraform Plan

Step 5 Deploy the environment with:
#terraform apply

Step 6 Accessing cluster run command.
#aws eks update-kubeconfig \
    --region <region-code> \
    --name <cluster_name> \
    --role-arn arn:aws:iam::<aws_account_id>:role/<role_name>
