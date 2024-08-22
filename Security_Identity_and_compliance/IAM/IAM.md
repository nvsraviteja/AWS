# What is AWS IAM

Identity & Access Management (IAM) is a service provided by AWS. It is a global service used to securely access AWS resources. Using IAM, an admin can create and manage AWS users and groups. They can grant permissions to access AWS resources by allowing or denying user permissions.

It is especially helpful in a multi-user environment, ensuring that only authorized users can access and perform actions on AWS resources.

## Authentication

Authentication is the process of verifying a user's identity using the email and password provided by the user.

When a new user creates an account in AWS or any other service, they set up credentials to secure their account. When they provide the correct credentials during login, AWS or the service allows them to access the resources.

## Authorization

In AWS or other services, once a user is authenticated, they gain access to the service. The service provider then manages their access to various resources and actions, which is known as authorization.

When a user is authenticated to AWS or other services, they gain access to the resources provided by the service. However, if the user is not an admin, then there should be restrictions to ensure that they can only access the specific resources necessary for their role.

For example, if the user is a developer, they typically need access to only a subset of resources. The admin would configure permissions to allow access only to those resources required for development. Thus, the developer is authorized to work with the resources necessary for their tasks, while other resources remain restricted.

## Features of AWS IAM

* Global
* User and Group management
* Roles
* Policies
* Multi Factor Authentication
* Temporary security credentials
* Free to use