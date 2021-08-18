
## Adding Data Sources (Direct)
Use the **Direct** connection if you want Nobl9 to access your server by connection directly over the internet. This method may be less secure, as you will need to open the port the data source is running on for Nobl9 to connect. 

### AppDynamics

1. Enter the **Controller URL** to connect your data source (required).
   AppDynamics does not support user or agent requests that originate from any URL other than the **Controller URL**.
   
2. Enter your AppDynamics **ClientID**.

3. Enter your AppDynamics **Client Secret**.

4. Enter a **Project** name.\
   The **Project** field is intended for use in situation where multiple users are spread across multiple teams or 
   projects. When **Project** field is left blank the typical **default** value appears.
   
5. The **Display Name** appears automatically when a name is entered into the **Name** field.

6. Enter a **Name** (required).\
    A **Name** is required because metadata names are unique within each
    project and are validated against some RFC and DNS names. The name
    must contain only lowercase alphanumeric characters and dashes.
    
    For example: `my-direct-appdynamics-data-source`
    
7. Enter a **Description** (optional).\
    Add the team or owner details and explain the purpose of creating this
    specific data source. Adding a description can provide immediate
    context for any team member.
    
### Big Query

1. Upload **Service Account Key File** to authenticate with Google Cloud.<br>
   The file must be in JSON format. [See the following reference](https://cloud.google.com/iam/docs/creating-managing-service-account-keys).

2. Enter a **Project** name.\
   The **Project** field is intended for use in situation where multiple users are spread across multiple teams or 
   projects. When **Project** field is left blank the typical **default** value appears.
   
3. The **Display Name** appears automatically when a name is entered into the **Name** field. 

3. Enter a **Name** (required).\
    A **Name** is required because metadata names are unique within each
    project and are validated against some RFC and DNS names. The name
    must contain only lowercase alphanumeric characters and dashes.
    
    For example: `my-direct-big-query-data-source`
    
4. Enter a **Description** (optional).\
    Add the team or owner details and explain the purpose of creating this
    specific data source. Adding a description can provide immediate
    context for any team member.
    
 ### Datadog

1.  Add the Datadog **API endpoint** to connect to your data source
    (required).

2.  Enter your Datadog **API Key**.<br>
    For more information about how to manage your **API Key**, see [*API and Application Keys*](https://docs.datadoghq.com/account_management/api-app-keys/).

3. Enter your Datadog **Application Key**.<br>
   For more information about how to manage your **Application Key**, see [*API and Application Keys*](https://docs.datadoghq.com/account_management/api-app-keys/).

2.  Enter a **Project** name.\
    The **Project** field is intended for use in situations where multiple
    users are spread across multiple teams or projects. When
    the **Project** field is left blank the typical **default** value
    appears.
    
3.  The **Display Name** appears automatically when a name is entered into the **Name** field.

4.  Enter a **Name** (required).\
    A **Name** is required because metadata names are unique within each
    project and are validated against some RFC and DNS names. The name
    must contain only lowercase alphanumeric characters and dashes.

    For example: `my-direct-datadog-data-source`

5.  Enter a **Description** (optional).\
    Add the team or owner details and explain the purpose of creating this
    specific data source. Adding a description can provide immediate
    context for any team member.
    
### New Relic

1.  Enter your New Relic **Account ID** to connect to your data source
    (required).
 
2. Enter the **Insights Query Key**.

3.  Enter a **Project** name.\
    The **Project** field is intended for use in situations where multiple
    users are spread across multiple teams or projects. When
    the **Project** field is left blank, the typical **default** value appears.

4.  The **Display Name** appears automatically when a name is entered into the **Name** field.

5.  Enter a **Name** (required).\
    A **Name** is required because metadata names are unique within each
    project and are validated against some RFC and DNS names. The name
    must contain only lowercase alphanumeric characters and dashes.

    For example: `my-direct-new-relic-data-source`

6.  Enter a **Description** (optional).\
    Add the team or owner details and explain the purpose of creating this
    specific data source. Adding a description can provide immediate
    context for any team member.
    
### Splunk

1.  Enter the **API Endpoint URL** to connect to your data source (required).<br>
    The URL must start with `https://`

2.  Enter the **Access Token**.<br>
    The **Access Token** is generated from Splunk.

2.  Enter a **Project** name.\
    The **Project** field is intended for use in situations where multiple
    users are spread across multiple teams or projects. When
    the **Project** field is left blank the typical **default** value
    appears.

3.  The **Display Name** appears automatically when a name is entered into the **Name** field.

4.  Enter a **Name** (required).\
    A **Name** is required because metadata names are unique within each
    project and are validated against some RFC and DNS names. The name
    must contain only lowercase alphanumeric characters and dashes.

    For example: `my-direct-splunk-data-source`

5.  Enter a **Description** (optional).\
    Add the team or owner details and explain the purpose of creating this
    specific data source. Adding a description can provide immediate
    context for any team member.
	
### Splunk Observability

1.  Add the **API Endpoint URL** to connect to your data source (required).
    
    For example: https://api.<code>REALM</code>.signalfx.com

2. Enter the **Access Token** environment variable for authentication with the organization API Access Token.<br>
   See [Create and manage organization access tokens](https://docs.splunk.com/Observability/admin/authentication-tokens/org-tokens.html#admin-org-tokens).

3. Enter a **Project** name.\
    The **Project** field is intended for use in situations where multiple
    users are spread across multiple teams or projects. When
    the **Project** field is left blank the typical **default** value
    appears.

4. The **Display Name** appears automatically when a name is entered into the **Name** field.

5. Enter a **Name** (required).\
    A **Name** is required because metadata names are unique within each
    project and are validated against some RFC and DNS names. The name
    must contain only lowercase alphanumeric characters and dashes.

    For example: `my-direct-splunk-observability-data-source`

6. Enter a **Description** (optional).\
    Add the team or owner details and explain the purpose of creating this
    specific data source. Adding a description can provide immediate
    context for any team member.
	
### ThousandEyes

1. Enter the **OAuth Bearer Token** for authentication with the ThousandEyes API.<br>
   When the Nobl9 agent is deployed for ThousandEyes, you must to provide a `THOUSANDEYES_OAUTH_BEARER_TOKEN` environment variable for authentication with ThousandEyes API.<br>
   
   To get the **OAUTH_BEARER_TOKEN**:

   - Log in to your ThousandEyes account.
   - Navigate to **Account Settings**.
   - Select **Users and Roles**.
   - Navigate to the bottom of the page and you will see **User API Tokens**.
   - Select **OAuth Bearer Token**.<br>
     Currently, Nobl9 only supports OAUTH_BEARER_TOKEN.

2. Enter a **Project** name.\
   The **Project** field is intended for use in situation where multiple users are spread across multiple teams or 
   projects. When **Project** field is left blank the typical **default** value appears.
   
3. The **Display Name** appears automatically when a name is entered into the **Name** field.

4. Enter a **Name** (required).\
    A **Name** is required because metadata names are unique within each
    project and are validated against some RFC and DNS names. The name
    must contain only lowercase alphanumeric characters and dashes.
    
    For example: `my-direct-thousandeyes-data-source`
    
5. Enter a **Description** (optional).\
    Add the team or owner details and explain the purpose of creating this
    specific data source. Adding a description can provide immediate
    context for any team member.
