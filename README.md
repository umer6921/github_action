# Github Actions 
The project utilizes an AWS S3 bucket to host a static web page. Whenever there is a modification in the code, GitHub automatically initiates the change, triggering a job to update and reflect the changes on the hosted site.

![image](https://github.com/umer6921/github_action/assets/75561123/f3731172-e8df-4db4-8397-eae249970b8b)

# How to run this project?
##### 1) Clone the Repository:
  Begin by cloning the repository.
##### 2) Sign In to Your AWS Account and Create an IAM Role:
   Access your AWS account and establish an IAM role.
##### 3) Grant S3 Bucket Permissions to the User:
   Provide the user with the necessary permissions for all S3 buckets.
##### 4) Create the S3 Bucket:
   Generate the S3 bucket required for your project.
##### 5) Update the main.yml File with the Bucket Name:
   Insert the S3 bucket name into the main.yml configuration file.
##### 6) Push Code to GitHub:
   Upload your code to your GitHub account. This will trigger the GitHub Actions job automatically.
