# Automation with cloudformation
# Introduction
  AWS CloudFormation is a service that helps users manage and provision cloud resources. It treats infrastructure as code (IaC), which can make it easier to manage changes and versioning.Creates, updates, and deletes a set of resources as a single unit called a stack.
# Language
  YAML
# Resources
  * VPC<br>
  * Public Subnet<br>
  * Public RouteTable<br>
  * Security Group
  * Instance<br>
  * S3 bucket<br>
# Template Structure
  * Parameters - Inputs into template and values pass to template at runtime.
  * mappings   - A lookup tables,map keys to values so we can change values.
  * Resources  - Create AWS resources which is based on infrastucture.
  * Output     - Values of custom resources created by template (URLs, usernames, etc.)
# Key functions
## 1.Infrastructure as Code (IaC): 
CloudFormation allows users to define and manage AWS infrastructure using a template, which is essentially code. This approach provides the benefits of versioning, reuse, and consistency in infrastructure deployment.
## 2.Resource Orchestration: 
 CloudFormation helps orchestrate the creation, update, and deletion of a collection of AWS resources as a single unit called a stack. This ensures that all resources are provisioned in a coordinated and consistent manner.
## 3.Automation Deployment:
Users can create, modify, and delete AWS resources without manually interacting with the AWS Management Console. This automation reduces the risk of human error, increases efficiency, and enables reproducibility of infrastructure across different environments.
## 4.Version Control:
Since infrastructure is defined as code, CloudFormation templates can be version-controlled using standard version control systems. This facilitates tracking changes, collaboration among team members, and the ability to roll back to previous configurations if needed.
## 5.Consistency and Reproducibility:
CloudFormation provides a unified view of the entire stack and its resources, making it easier to manage and monitor the infrastructure. Users can efficiently track resource dependencies and manage the entire stack lifecycle.
## 6.Cost Management:
By defining infrastructure requirements in templates, users can estimate costs before deploying resources. CloudFormation also allows for the tagging of resources, aiding in cost allocation and budget management.
  
  


