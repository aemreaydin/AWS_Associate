# IAM - Identity Access Management

## What does IAM give you?
* Centralized control of you AWS account.
* Shared Access to your AWS account.
* Granular Permissions
* Identity Federation(Active Directory, Facebook, LinkedIn, etc.)
* Multi-factor Authentication
* Provides temporary access for users/devices and services.
* Allows you to set up your own password rotation policy
* Integrates with many AWS services.
* Supports PCI DSS(Payment Card Industry Data Security Standard) Compliance

## Critical Terms
* Users - End Users
* Groups - A collection of users under one set of permissions
* Roles - Defines a set of permissions for making AWS service requests.
* Policies - A JSON document that defines one or more permissions.

### IAM Security Status
1. Delete your root access keys
2. Activate MFA on your root account
3. Create individual IAM users
4. User groups to assign permissions
5. Apply an IAM password policy