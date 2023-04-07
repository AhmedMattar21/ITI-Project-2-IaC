# Project-2: Deploy a high-availability web app using CloudFormation

### Scenario
Your company is creating an Instagram clone called Udagram. Developers want to deploy a new application to the AWS infrastructure. You have been tasked with provisioning the required infrastructure and deploying a dummy application, along with the necessary supporting software. This needs to be automated so that the infrastructure can be discarded as soon as the testing team finishes their tests and gathers their results.

### Server specs
  1.You'll need to create a Launch Configuration for your application servers in order to deploy four servers, two located in each of your private subnets. The launch configuration will be used by an auto-scaling group.  
  
  2.You'll need two vCPUs and at least 4GB of RAM. The Operating System to be used is Ubuntu 18. So, choose an Instance size and Machine Image (AMI) that best fits this spec.  
  
3. Be sure to allocate at least 10GB of disk space so that you don't run into issues.  
