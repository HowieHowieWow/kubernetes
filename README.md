# kubernetes files


Create cluster

kops create cluster --name=howiehowiewow.tk --state=s3://kops-state-h --zones=us-east-2a --node-count=2 --node-size=t2.micro --master-size=t2.micro --dns-zone=howiehowiewow.tk


Configure your cluster

kops update cluster --name howiehowiewow.tk --yes --state=s3://kops-state-h
