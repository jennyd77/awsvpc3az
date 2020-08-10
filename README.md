# awsvpc3az
Build out a VPC in AWS across 3 AZs. Each AZ will have a private and a public subnet. Include IGW, NAT Gateways, and all necessary routing

## Usage
E.G. To deploy in ap-southeast-2 with your default profile:
aws cloudformation create-stack --stack-name vpc3az --template-body file://vpc-3azs-template.yaml --parameters file://vpc-3azs-parameters.json --region ap-southeast-2
