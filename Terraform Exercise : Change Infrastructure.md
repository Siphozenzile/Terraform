# TERRAFORM EXCERCISE – CHANGE INFRASTRUCTURE 

 
### Exercise: Updating an EC2 Instance 

Based on the tutorial provided, here's an exercise to help you practice modifying your infrastructure using Terraform. 

### Objective :

Modify the existing Terraform configuration to update the AMI of your EC2 instance and apply the changes. 

 

## Prerequisites 

- Terraform CLI (1.2.0+) 

- AWS CLI (configured with a default profile) 

- An existing Terraform configuration for an EC2 instance, as described in the tutorial 


## Steps:  

1.  Initialize your Terraform configuration to download the necessary providers with the command terraform init. 

2. Apply the initial configuration for the main.tf file you created in the last exercise with terraform apply to create the EC2 instance.  

3. In your main.tf created in the previous exercise, update the file to use a new AMI. Replace the current AMI ID (ami-830c94e3) with ami-08d70e59c07c61a3a.


![image](https://github.com/user-attachments/assets/6be649ca-4607-4ab2-93e3-15ef7680423c)


3.  Apply the updated configuration with the command terraform apply.  

4. Use the terraform show command to verify the new values associated with the instance! 


![image](https://github.com/user-attachments/assets/292b916e-d756-486e-84f1-5a1c2b6965d4)


