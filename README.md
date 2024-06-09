This is a very Basic DevOps Project

Design the IaC (Terraform, Aws ECS/Fargate) for Hello world Node.js app, CD pipeline using GitHub Actions .

Follow with the steps:

have node js installed in your system

download the repo

go to the folder "hello_world_app"

npm init -y

npm install express

Can change the region, availability-zone and cidr_block according your configurations

Run the following commands in your terminal inside the terraform directory:

terraform init

terraform apply

Push to GitHub

Initialize a Git Repository and Push Code

Go back to your project root directory and initialize a Git repository:

git init

git add .

git commit -m "Initial commit"

Create a New Repository on GitHub

Go to GitHub and create a new repository.

Follow the instructions to push your local repository to GitHub:

git remote add origin https://github.com/your-username/hello-world-ecs-terraform.git

git branch -M main

git push -u origin main
