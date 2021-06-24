create_cluster:
	eksctl create cluster -f cluster.yaml

delete_cluster:
	eksctl delete cluster -f cluster.yaml

describe_cluster:
	eksctl utils describe-stacks --region=us-east-2 --cluster=robin-personal-cluster

aws_identity:
	aws sts get-caller-identity

set_context:
	eksctl utils write-kubeconfig --cluster=prasoon-eks-cluster --set-kubeconfig-context=true


------------------------------
eksctl not found 
	
curl --silent --location "https://github.com/weaveworks/eksctl/releases/latest/download/eksctl_$(uname -s)_amd64.tar.gz" | tar xz -C /tmp
sudo mv /tmp/eksctl /usr/local/bin
eksctl version
----------------------------------
pip install

curl "https://bootstrap.pypa.io/get-pip.py" -o "get-pip.py"
sudo python3 get-pip.py
--------------------------------
sudo pip install awscli
aws configure --Put access key of create cluster
---------------------------------
Error: cannot find EC2 key pair "~/.ssh/id_rsa.pub"
cd /home/ubuntu/.ssh
ssh-keygen -t rsa
-----------------------------Link followed----------------------------------
https://www.youtube.com/watch?v=cB0fCMPIj1Y&list=PLudFIcRiWNWQFy7EGw3kW_9n9woamu8r7&index=2&t=1645s
-------------------Installkubectl-------------------------------------------------

curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl
