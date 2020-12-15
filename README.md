README

This solution is based on cloudformation completely.

Cloudformation is creating the 

--VPC
--Three subnet

--InternetGateway
--Three security groups
-- Three Ec2 instances
-- Creating route table and setting up route entries

-- Setting up user data on web instance

-- Mapping security group to instance.

Command:

aws cloudformation create-stack --template-body file://createStack.yaml (Here give the exact path of file)