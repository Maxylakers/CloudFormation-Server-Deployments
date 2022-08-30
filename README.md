Output URL at the time:
DNS name: http://maxse-webap-mqhfsgdb83c-1164526157.us-west-2.elb.amazonaws.com/

DNS name output name: MaxDNS

- A project to deploy a high availability webapp using infrastructure as code (CloudFormation) 

- The project is to deploy a dummy HTML file to an Apache web server running on an EC2 instance, configured to echo "it works! Udagram, Udacity as its index page, replaying the Apache landing page.

- The project includes a diagram showing schematics and flow of the deployment named as Project Architecture.jpeg.


Also it includes the following scripts:

- create.sh: for creating the stack within which the infrastructures gets deployed.
- update.sh: A script to run updates to the infrastructure.
- infrastructure.yml: includes all of the core IaaS codes ranging from VPC, public and private subnets to route tables and routes.
- parameter.json: allows for desired infrastructure value allocation.
- server.yml: is core to the web app code, down to listeners for health checks, DNS, load balancing etc.
- server.json: is also a parameter file for the server.yml script.
