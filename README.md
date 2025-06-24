**Task 1: Automated Instance Management Using AWS Lambda and Boto3
Objective: Create a Lambda function that will automatically manage EC2 instances based on their tags.**

Creating 2 EC2Instances
 ![image](https://github.com/user-attachments/assets/def58726-5c3b-4497-9abd-4cd68c05aae4)

 ![image](https://github.com/user-attachments/assets/06a5d9d5-b836-40d6-8632-4f3c50df6754)

2 EC2 instances have been created with the appropriate tags. 

IAM Role Created
 ![image](https://github.com/user-attachments/assets/3ed71dc2-6682-4f42-bc02-abcd4acf3da2)

Lambda Function created. 
![image](https://github.com/user-attachments/assets/c372501a-f475-47b4-baf6-56a8decbed74)

 
On Running the function, the end summary clearly shows an instance being stopped.

![image](https://github.com/user-attachments/assets/4e5f6cf5-ee20-47cf-ae28-15e770b6b6c9)

 
When checking at the Instance page, we can see that an instance is indeed stopped. 
 ![image](https://github.com/user-attachments/assets/d2c5c521-f152-475a-af82-543271dae1b5)






**Task 3: Monitor Unencrypted S3 Buckets Using AWS Lambda and Boto3
Objective: To enhance your AWS security posture by setting up a Lambda function that detects any S3 bucket without server-side encryption.**

S3 Bucket Creation
 ![image](https://github.com/user-attachments/assets/e520ab41-865a-4932-8c22-b74f04eae835)

3 buckets are created with *1 and *3 without server side encryption.

IAM Roles Creation
 ![image](https://github.com/user-attachments/assets/d69f6c85-4216-4bf9-880c-df5016669c24)


Lambda Function Creation
 ![image](https://github.com/user-attachments/assets/8d6d7100-0a6b-4efe-aea9-713294516725)

 ![image](https://github.com/user-attachments/assets/ade8c295-3b4c-4b1a-8609-543bdbb4e484)

**Task 5: Auto-Tagging EC2 Instances on Launch Using AWS Lambda and Boto3
Objective: Learn to automate the tagging of EC2 instances as soon as they are launched, ensuring better resource tracking and management.**
Creating IAM Roles
 
 ![image](https://github.com/user-attachments/assets/b0d63ef6-2d60-47fb-a99a-a881848a54b9)

 
 ![image](https://github.com/user-attachments/assets/f3858f6d-78fc-4170-9635-bcc725e9eb32)

![image](https://github.com/user-attachments/assets/e2c9d0c4-11af-48ec-a1f3-cfeafc8e66ee)
 

![image](https://github.com/user-attachments/assets/5730e0a5-70a1-4a9d-8e74-0d77ccf91213)

Creating Lambda Function
 ![image](https://github.com/user-attachments/assets/56ec0a0b-04b1-4567-86fc-662c4ec9049a)

![image](https://github.com/user-attachments/assets/866a08da-d5c9-47e1-bb8f-fd23add94338)
 
Creating Rule 
![image](https://github.com/user-attachments/assets/32a539be-6996-47a8-88ea-0ddd011689a7)
![image](https://github.com/user-attachments/assets/57bf9e2d-7fe7-48a8-92dc-c5058e60c1d5)
![image](https://github.com/user-attachments/assets/597b1a32-bc40-45ec-b2a7-a0d1d052dee7)

 ![image](https://github.com/user-attachments/assets/2644dd88-f9e8-49bd-9da0-2fe1e4474955)

Performing the CloudWatch Activities
![image](https://github.com/user-attachments/assets/61bb327d-213a-40fa-ab84-5ad84751db5f)

 
Verification of the Tag on the EC2 instances created 
 ![image](https://github.com/user-attachments/assets/6fed6a90-6e0a-4e4c-a488-ac85cdbb2eef)




**Task 17: Restore EC2 Instance from Snapshot
Objective: Automate the process of creating a new EC2 instance from the latest snapshot using a Lambda function.**

Creating the IAM Role
 ![image](https://github.com/user-attachments/assets/80e09270-0ee9-423b-b37e-cec35e6381c0)


Lambda Function
 ![image](https://github.com/user-attachments/assets/3ea1f409-f98d-4845-8c5e-9bb49a6eb7c5)

Test Result from the Lambda Function
 ![image](https://github.com/user-attachments/assets/fdf36329-b650-4e08-8350-bc9eb6e19182)

Checking back on the EC2 instances, seen below is the EC2 instance created from the information provided in the Lambda Function. 
 ![image](https://github.com/user-attachments/assets/db8d154e-48f3-4c86-acf7-70fdece79c98)






