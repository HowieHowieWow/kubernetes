# kubernetes files


Create cluster:
kops create cluster --name=howiehowiewow.dns-cloud.net --state=s3://kops-state-h --zones=us-east-2a --node-count=2 --node-size=t2.micro --master-size=t2.micro --dns-zone=howiehowiewow.dns-cloud.net


Configure your cluster:
kops update cluster --name howiehowiewow.dns-cloud.net --yes --state=s3://kops-state-h
