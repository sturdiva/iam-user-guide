# Actions, Resources, and Condition Keys for Amazon Session Manager Message Gateway Service<a name="list_amazonsessionmanagermessagegatewayservice"></a>

Amazon Session Manager Message Gateway Service \(service prefix: `ssmmessages`\) provides the following service\-specific resources, actions, and condition context keys for use in IAM permission policies\.

References:
+ Learn how to [configure this service](https://docs.aws.amazon.com/systems-manager/latest/userguide/)\.
+ Learn how to protect this service and its resources by [using IAM](https://docs.aws.amazon.com/systems-manager/latest/userguide/sysman-configuring-access-iam-create.html) permission policies\.

**Topics**
+ [Actions Defined by Amazon Session Manager Message Gateway Service](#amazonsessionmanagermessagegatewayservice-actions-as-permissions)
+ [Resources Defined by Amazon Session Manager Message Gateway Service](#amazonsessionmanagermessagegatewayservice-resources-for-iam-policies)
+ [Condition Keys for Amazon Session Manager Message Gateway Service](#amazonsessionmanagermessagegatewayservice-policy-keys)

## Actions Defined by Amazon Session Manager Message Gateway Service<a name="amazonsessionmanagermessagegatewayservice-actions-as-permissions"></a>

You can specify the following actions in the `Action` element of an IAM policy statement\. Use policies to grant permissions to perform an operation in AWS\. When you use an action in a policy, you usually allow or deny access to the API operation or CLI command with the same name\. However, in some cases, a single action controls access to more than one operation\. Alternatively, some operations require several different actions\.

The **Resource** column indicates whether each action supports resource\-level permissions\. If there is no value for this column, you must specify all resources \("\*"\) in the `Resource` element of your policy statement\. If the column includes a resource type, then you can specify an ARN of that type in a statement with that action\. Required resources are indicated in the table with an asterisk \(\*\)\. If you specify a resource\-level permission ARN in a statement using this action, then it must be of this type\. Some actions support multiple resource types\. If the resource type is optional \(not indicated as required\), then you can choose to use one but not the other\.

For details about the columns in the following table, see [The Actions Table](reference_policies_actions-resources-contextkeys.md#actions_table)\.


****  

| Actions | Description | Access Level | Resource Types \(\*required\) | Condition Keys | Dependent Actions | 
| --- | --- | --- | --- | --- | --- | 
|   CreateControlChannel  | Registers a control channel for an instance to send control messages to Systems Manager service\. | Write |  |  |  | 
|   CreateDataChannel  | Registers a data channel for an instance to send data messages to Systems Manager service\. | Write |  |  |  | 
|   OpenControlChannel  | Opens a websocket connection for a registered control channel stream from an instance to Systems Manager service\. | Write |  |  |  | 
|   OpenDataChannel  | Opens a websocket connection for a registered data channel stream from an instance to Systems Manager service\. | Write |  |  |  | 

## Resources Defined by Amazon Session Manager Message Gateway Service<a name="amazonsessionmanagermessagegatewayservice-resources-for-iam-policies"></a>

Amazon Session Manager Message Gateway Service has no service\-defined resources that can be used as the `Resource` element of an IAM policy statement\.

## Condition Keys for Amazon Session Manager Message Gateway Service<a name="amazonsessionmanagermessagegatewayservice-policy-keys"></a>

SSM Messages has no service\-specific context keys that can be used in the `Condition` element of policy statements\. For the list of the global context keys that are available to all services, see [Available Keys for Conditions](reference_policies_condition-keys.html#AvailableKeys) in the *IAM Policy Reference*\.