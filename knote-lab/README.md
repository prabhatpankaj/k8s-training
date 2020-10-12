* Create an EBS

For the Static provisioning first, we need to create a storage device, in this case, it will be AWS EBS,and then we will create a PersistentVolume that will use this EBS.

```
aws ec2 --region us-east-1 create-volume --availability-zone us-east-1a --size 10

```
