TASK 1: Simple Node Js Application Deployment on Docker container Description:

I created a Dockerfile for a simple Node.js application that listens on port 3000, used a sample package.json and app.js files for app dependencies.

Included Files:

Dockerfile: Builds the Docker image.

package.json: Lists application dependencies.

app.js: Simple Node.js app that responds with "Hello World."

USE COMMAND:

docker build -t image-name .

docker run -p 3000:3000 image-name

USE URL FOR ACCESS APPLICATION:

http://localhost:3000

Task 2: K8s Deployment: 

For Task 2, a Kubernetes deployment configuration is provided in the deployment.yaml file. This file sets up an Nginx web application with the following specifications:

USE COMMAND:

kubectl apply -f deployment.yaml

Task 3: Resource Provisioning and configuration management through terraform and ansible To run the terraform main.tf file use below commands:

USE COMMAND FOR TERRAFORM:

terraform init

terraform validate

terraform plan

terraform apply

terraform destroy

USE COMMAND FOR ANSIBLE:

ansible-playbook playbook.yml
