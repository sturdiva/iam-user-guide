# Actions, Resources, and Condition Keys for AWS Marketplace Management Portal<a name="list_awsmarketplacemanagementportal"></a>

AWS Marketplace Management Portal \(service prefix: `aws-marketplace-management`\) provides the following service\-specific resources, actions, and condition context keys for use in IAM permission policies\.

References:
+ Learn how to [configure this service](https://docs.aws.amazon.com/marketplace/latest/controlling-access/)\.
+ View a [list of the API operations available for this service](https://docs.aws.amazon.com/marketplace/latest/controlling-access/)\.
+ Learn how to protect this service and its resources by [using IAM](https://docs.aws.amazon.com/marketplace/latest/controlling-access/marketplace-management-portal-user-access.html#detailed-management-portal-permissions) permission policies\.

**Topics**
+ [Actions Defined by AWS Marketplace Management Portal](#awsmarketplacemanagementportal-actions-as-permissions)
+ [Resources Defined by AWS Marketplace Management Portal](#awsmarketplacemanagementportal-resources-for-iam-policies)
+ [Condition Keys for AWS Marketplace Management Portal](#awsmarketplacemanagementportal-policy-keys)

## Actions Defined by AWS Marketplace Management Portal<a name="awsmarketplacemanagementportal-actions-as-permissions"></a>

You can specify the following actions in the `Action` element of an IAM policy statement\. Use policies to grant permissions to perform an operation in AWS\. When you use an action in a policy, you usually allow or deny access to the API operation or CLI command with the same name\. However, in some cases, a single action controls access to more than one operation\. Alternatively, some operations require several different actions\.

The **Resource** column indicates whether each action supports resource\-level permissions\. If there is no value for this column, you must specify all resources \("\*"\) in the `Resource` element of your policy statement\. If the column includes a resource type, then you can specify an ARN of that type in a statement with that action\. Required resources are indicated in the table with an asterisk \(\*\)\. If you specify a resource\-level permission ARN in a statement using this action, then it must be of this type\. Some actions support multiple resource types\. If the resource type is optional \(not indicated as required\), then you can choose to use one but not the other\.

For details about the columns in the following table, see [The Actions Table](reference_policies_actions-resources-contextkeys.md#actions_table)\.


****  

| Actions | Description | Access Level | Resource Types \(\*required\) | Condition Keys | Dependent Actions | 
| --- | --- | --- | --- | --- | --- | 
|   [ uploadFiles ](https://docs.aws.amazon.com/marketplace/latest/controlling-access/marketplace-management-portal-user-access.html#detailed-management-portal-permissions)  | Allows a user to access the File Upload page inside the AWS Marketplace Management Portal\. | Write |  |  |  | 
|   [ viewMarketing ](https://docs.aws.amazon.com/marketplace/latest/controlling-access/marketplace-management-portal-user-access.html#detailed-management-portal-permissions)  | Allows a user to access the Marketing page inside the AWS Marketplace Management Portal\. | List |  |  |  | 
|   [ viewReports ](https://docs.aws.amazon.com/marketplace/latest/controlling-access/marketplace-management-portal-user-access.html#detailed-management-portal-permissions)  | Allows a user to access the Reports page inside the AWS Marketplace Management Portal\. | List |  |  |  | 
|   [ viewSettings ](https://docs.aws.amazon.com/marketplace/latest/controlling-access/marketplace-management-portal-user-access.html#detailed-management-portal-permissions)  | Allows a user to access the Settings page inside the AWS Marketplace Management Portal\. | List |  |  |  | 
|   [ viewSupport ](https://docs.aws.amazon.com/marketplace/latest/controlling-access/marketplace-management-portal-user-access.html#detailed-management-portal-permissions)  | Allows a user to access the Customer Support Eligibility page inside the AWS Marketplace Management Portal\. | List |  |  |  | 

## Resources Defined by AWS Marketplace Management Portal<a name="awsmarketplacemanagementportal-resources-for-iam-policies"></a>

AWS Marketplace Management Portal has no service\-defined resources that can be used as the `Resource` element of an IAM policy statement\.

## Condition Keys for AWS Marketplace Management Portal<a name="awsmarketplacemanagementportal-policy-keys"></a>

Marketplace Portal has no service\-specific context keys that can be used in the `Condition` element of policy statements\. For the list of the global context keys that are available to all services, see [Available Keys for Conditions](reference_policies_condition-keys.html#AvailableKeys) in the *IAM Policy Reference*\.