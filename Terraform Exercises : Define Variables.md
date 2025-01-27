# TERRAFORM EXCERCISE – DEFINE INPUT VARIABLES 

### Exercise: Parameterizing AWS Configurations with Terraform Variables 


## Objective: 


By the end of this exercise, you will be able to: 

- Define and use input variables in Terraform to parameterize AWS configurations. 

- Override default variable values using a terraform.tfvars file. 

- Understand the benefits of using variables to make Terraform configurations reusable and flexible.
  

## Prerequisites: 

- Basic knowledge of Terraform and AWS. 

- Terraform and AWS CLI installed and configured on your machine.
  

## Steps: 

### 1. Edit your main configuration file (main.tf) that will contain the basic configuration for provisioning an AWS EC2 instance.



![image](https://github.com/user-attachments/assets/4217b123-d932-48ba-8947-c0163930355a)

### 2. Create a variables.tf file in the same learn-terraform-aws directory to define the variables used in the main.tf file:
   

![image](https://github.com/user-attachments/assets/66101c5b-0f32-4862-99a5-ad160b06438e)


### 3. Create a terraform.tfvars file to provide values for the variables. 

Use this ID  “ami-08d70e59c07c61a3a” instead. 



![image](https://github.com/user-attachments/assets/58d972bf-1b5c-4619-a3a4-20ae60a12173)


### 4.  Initialize the Terraform configuration and apply it. Show outputs:
   


![image](https://github.com/user-attachments/assets/39c0da92-b99b-4938-ab0f-32776fb521fa)


### 5. After applying the configuration, verify that the EC2 instance is created in your AWS account.
   


![image](https://github.com/user-attachments/assets/53d2d99e-6e9e-405d-a544-95a491f5340c)




