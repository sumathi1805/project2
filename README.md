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

  
  


