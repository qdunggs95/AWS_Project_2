## Website Link : http://udagramloadbalancer-1091610137.us-east-1.elb.amazonaws.com/

## Script Create CloudFormation:

### VPC
	./create.sh dungnq21VPC Infrastructure/dungnq21VPC.yaml Infrastructure/Parameters/dungnq21VPC.json

### SecurityGroup
	./create.sh dungnq21SecurityGroup Infrastructure/dungnq21SecurityGroup.yaml Infrastructure/Parameters/dungnq21SecurityGroup.json

### IAMRole
	./create.sh dungnq21IAMRole Infrastructure/dungnq21IAMRole.yaml Infrastructure/Parameters/dungnq21IAMRole.json

### S3
	./create.sh dungnq21S3 Infrastructure/dungnq21S3.yaml Infrastructure/Parameters/dungnq21S3.json

### Bastion
	./create.sh dungnq21Bastion Infrastructure/dungnq21Bastion.yaml Infrastructure/Parameters/dungnq21Bastion.json

### AutoScalingGroup
	./create.sh dungnq21AutoScaling Infrastructure/dungnq21AutoScalingGroup.yaml Infrastructure/Parameters/dungnq21AutoScalingGroup.json

### LoadBalancer
	./create.sh dungnq21LoadBalancer Infrastructure/dungnq21LoadBalancer.yaml Infrastructure/Parameters/dungnq21LoadBalancer.json
	
## Script Update CloudFormation:

### VPC
	./update.sh dungnq21VPC Infrastructure/dungnq21VPC.yaml Infrastructure/Parameters/dungnq21VPC.json

### SecurityGroup
	./update.sh dungnq21SecurityGroup Infrastructure/dungnq21SecurityGroup.yaml Infrastructure/Parameters/dungnq21SecurityGroup.json

### IAMRole
	./update.sh dungnq21IAMRole Infrastructure/dungnq21IAMRole.yaml Infrastructure/Parameters/dungnq21IAMRole.json

### S3
	./update.sh dungnq21S3 Infrastructure/dungnq21S3.yaml Infrastructure/Parameters/dungnq21S3.json

### Bastion
	./update.sh dungnq21Bastion Infrastructure/dungnq21Bastion.yaml Infrastructure/Parameters/dungnq21Bastion.json

### AutoScalingGroup
	./update.sh dungnq21AutoScaling Infrastructure/dungnq21AutoScalingGroup.yaml Infrastructure/Parameters/dungnq21AutoScalingGroup.json

### LoadBalancer
	./update.sh dungnq21LoadBalancer Infrastructure/dungnq21LoadBalancer.yaml Infrastructure/Parameters/dungnq21LoadBalancer.json

## Script Delete CloudFormation:

### VPC
	./delete.sh dungnq21VPC Infrastructure/dungnq21VPC.yaml Infrastructure/Parameters/dungnq21VPC.json

### SecurityGroup
	./delete.sh dungnq21SecurityGroup Infrastructure/dungnq21SecurityGroup.yaml Infrastructure/Parameters/dungnq21SecurityGroup.json

### IAMRole
	./delete.sh dungnq21IAMRole Infrastructure/dungnq21IAMRole.yaml Infrastructure/Parameters/dungnq21IAMRole.json

### S3
	./delete.sh dungnq21S3 Infrastructure/dungnq21S3.yaml Infrastructure/Parameters/dungnq21S3.json

### Bastion
	./delete.sh dungnq21Bastion Infrastructure/dungnq21Bastion.yaml Infrastructure/Parameters/dungnq21Bastion.json

### AutoScalingGroup
	./delete.sh dungnq21AutoScaling Infrastructure/dungnq21AutoScalingGroup.yaml Infrastructure/Parameters/dungnq21AutoScalingGroup.json

### LoadBalancer
	./delete.sh dungnq21LoadBalancer Infrastructure/dungnq21LoadBalancer.yaml Infrastructure/Parameters/dungnq21LoadBalancer.json
