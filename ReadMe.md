#EC2
1. EC2_multiple_ENI_and_EIP.yaml - Create EC2 instance with 4 x ENI with each attached EIP

2. EC2_3ENI_1EIP_Tag.yaml - Creates EC2 with 3ENI + 1 EIP with Tag key:Name <Value> on an AWS Outposts subnet

3. SSMDocument_EC2Bootstrapping_Tag.yaml - Creates SSM Document for bootstrapping EC2 with used of Tagging Key:Name <Value> 

        - Bootsrapping includes Interface Bridging 
        
        - GRE tunnel
        
        - Enable UE Pool CIDR to Internet
        
