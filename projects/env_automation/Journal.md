## VCP Settings

This are VPC setting that we'll use in our cloudn enviroment in AWS:
VPC IPv4 CIDR: 10.200.124.0/24
IPv6 CIDR Block: No 
Numeber of AZs: 1 
Number of public subnets: 1 
Number of Private Subnets: 1
NAT GW: none
VPC endpoints: none
DNS: Enable DNS host Names & Enable DNS Resolution 


## Generated and Review CFN Template

I used ChatGPT to generate the template according to instructor's provided sestings

## Generated deploy script

Using ChatGPT generated deploy script, made it platfrom agnostic 


## Visualisation in Inftastructure Composer

Generated version is not what was expected: 
![](assets/aws_infra_composer.png)

## Install AWS CLI

Prior to runnig the script we need to install AWS CLI
Please use AWS instructions: https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

## Actual VPC resoures map 

![](assets/aws_vpc_resoures_map.png)