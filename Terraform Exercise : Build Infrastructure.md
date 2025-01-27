## TERRAFORM EXCERCISE – BUILD INFRASTRUCTURE

### Exercise: Provision an EC2 Instance with Terraform 

By the end of this exercise, you will have provisioned an EC2 instance on AWS using Terraform. 

 
### Prerequisites 

1. Terraform CLI (1.2.0+) installed. 

2. AWS CLI installed. 

3. An AWS account with appropriate permissions to create resources. 

4. AWS Toolkit installed in VS Code extensions


## Steps: 

### 1. Set Up Environment Variables: 


Before starting, ensure your IAM credentials are set up correctly, search for cmd in windows and enter the following:

![image](https://github.com/user-attachments/assets/2fda0e56-3eb3-4ef1-a872-53fb508c9144)


### 2. Create a directory called ‘learn-terraform-aws’ for your Terraform configuration and navigate into it (You can do this on VS Code)

### 3. Create Configuration File 


- Create a new file named `main.tf` 

- Open `main.tf` in your preferred text editor and type the following configuration – not paste, type!

![image](https://github.com/user-attachments/assets/f114a18b-3329-42fc-9ef3-4a298d4da5e7)


### 4. Initialize Terraform 


Initialize your Terraform working directory with terraform init to download the necessary providers. You should get these files and output:  

![image](https://github.com/user-attachments/assets/d8deb713-b8b3-46fc-b4e5-4bd8e87e51c0)

![image](https://github.com/user-attachments/assets/81eaac4f-563a-4372-a6c0-003479a656df)


### 5. Format and validate configuration 


- Format the configuration with terraform fmt for readability and consistency 

- Validate the configuration with terraform validate to ensure it is syntactically correct 

![image](https://github.com/user-attachments/assets/35cef18a-7359-4a84-b5dd-e2e833745cf1)


### 6.  Apply the configuration with terraform apply to provision the EC2 instance: 


- Terraform will show an execution plan and prompt for confirmation. Type ‘yes’ to confirm and proceed. 

![image](https://github.com/user-attachments/assets/b0671a7b-fa91-4660-9ea5-abadcff4f368)

- You should also have a new file show up in your learn-terraform-aws directory:

![image](https://github.com/user-attachments/assets/2d0299c2-eff1-49c5-ad04-99983040498d)

 

### 7. After the instance is created, you can inspect the current state with terraform show: 


![image](https://github.com/user-attachments/assets/0af558a4-8618-4e6e-bd92-0a2753c1cc5c)


### 8. List all resources in your Terraform state with terraform state list:


![image](https://github.com/user-attachments/assets/65e1b55e-25b5-4d4c-bbfb-eecd2a9f92f5)


### 9. If you've successfully provisioned an EC2 instance using Terraform. You can now visit the AWS EC2 console to see your new instance. It should look something like this:


![image](https://github.com/user-attachments/assets/0347f92a-feaf-423e-b78f-630e09a5c350)


### 10. To avoid unnecessary charges, you can destroy the resources you created with the command terraform destroy:

![image](https://github.com/user-attachments/assets/76f108fd-ca1e-4ca4-8ce7-704d8343424a)


- Check your AWS EC2 console. There be no instance running!
  

![image](https://github.com/user-attachments/assets/ba10047f-8c21-4c14-ad59-80a6ceaade3c)





