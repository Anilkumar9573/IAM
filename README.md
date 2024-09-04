# IAM (Identity and Access Management):
**IAM (Identity and Access Management)** in AWS (Amazon Web Services) is a service that helps you manage who can access your AWS resources and what actions they can perform. It allows you to create and manage users, groups, and roles, and set permissions to control access to AWS services and resources securely. Essentially, IAM is a way to manage access and ensure that only authorized users can access or perform specific actions on AWS resources.

![IAM](https://github.com/user-attachments/assets/b0deaa50-b35a-4d17-8254-ade476208c3f)

# Authentication :
**Authentication** in AWS is the process of verifying the identity of a user or service trying to access AWS resources. It ensures that the person or application requesting access is who they claim to be, typically using a username and password, access keys, or other security credentials. This step is crucial before allowing any user or service to interact with AWS resources.
# Authorization :
**Authorization** in AWS is the process of determining what actions a user or service is allowed to perform on AWS resources after they have been authenticated. It defines what permissions they have, such as which services they can access or what specific operations they can perform within those services. In simple terms, after AWS confirms who you are (authentication), it checks what you're allowed to do (authorization).
# group Users :
In AWS, a **group** is a collection of users that share the same set of permissions. Instead of assigning permissions to each individual user, you can assign them to a group, and all users in that group will automatically have those permissions. This simplifies management by allowing you to control access for multiple users at once.


![user group](https://github.com/user-attachments/assets/39db8bd9-4ae4-4127-98c5-57b522cb6ca0)

# policies are directly attached through the user Groups :
![11](https://github.com/user-attachments/assets/707cb36a-45e4-4af1-ad65-8f8ab19b1efc)

# Users :
In AWS, a **user** is an individual account created for a person or application that needs to interact with AWS resources. Each user has its own credentials (like a username and password or access keys) and can be assigned specific permissions that define what actions they are allowed to perform in AWS. Users are typically created and managed through AWS Identity and Access Management (IAM).


![user11](https://github.com/user-attachments/assets/3f86e3b0-7c95-4594-8fe2-793a8c17d66e)


# Policies :
In AWS, a **policy** is a document that defines permissions. It specifies what actions are allowed or denied on which resources and under what conditions. Policies are used to control user and service access to AWS resources by attaching them to users, groups, or roles. Policies are written in JSON format and help enforce security by defining who can do what within your AWS environment.


![policies](https://github.com/user-attachments/assets/b31c7d63-4829-4246-9251-99da2c913e45)


# Roles :
In AWS, a **role** is a set of permissions that define what actions an entity (such as an AWS service, user, or application) can perform on AWS resources. Roles are used to grant temporary access to AWS resources without needing to share long-term credentials. For example, you can create a role for an EC2 instance to access an S3 bucket, or for a user to assume temporarily for specific tasks. Roles are particularly useful for granting access between different AWS accounts or services securely.

