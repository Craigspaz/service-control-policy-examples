## Region controls 

Enforce controls in your multi-account environment to inhibit use of certain AWS Region or Regions.

| Included policy | Rationale |
|------|-------------|
|[Deny account region enable and disable actions](Deny-account-region-enable-and-disable-actions.json)| Restrict enabling or disabling [opt-in regions](https://docs.aws.amazon.com/general/latest/gr/rande-manage.html#rande-manage-enable) for an account to privileged role.| 
|[Deny access to AWS based on the requested AWS region](Deny-access-to-AWS-based-on-the-requested-AWS-region.json)| Deny access to any operations outside of the specified Regions while providing exemptions for operations in approved global services. Replace the list of services and operations with the global services used by accounts in your organization.Replace eu-central-1 and eu-west-1 with the AWS Regions you want to use. This example might not include all of the latest global AWS services or operations.|
|||

