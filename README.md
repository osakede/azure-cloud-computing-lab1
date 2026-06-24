Screenshot: Payment methods page
<img width="1364" height="684" alt="payment method" src="https://github.com/user-attachments/assets/f3499599-3775-477b-9006-10b79df989c4" />
1 – Azure Account Verification and Payment Method
During Azure account registration, I was required to add a valid payment card. I navigated to Cost Management + Billing → Payment Methods and verified that my Mastercard was successfully added to the account.
Microsoft requires a payment method to verify the identity of new users and prevent fraudulent account creation. The payment method also serves as a backup billing source after free credits expire.
Evidence: Figure 1 shows the registered payment method and the available Azure credit balance of $200.

Uploading image.png…]()
<img width="1358" height="675" alt="Storsge center" src="https://github.com/user-attachments/assets/d084ab29-45ac-46e8-8c18-f76e04502e9a" />
2 – Azure Subscription Overview
After account creation, I opened Subscriptions from the Azure Portal and reviewed my active subscription details.
The subscription acts as the billing and management boundary for Azure resources. It allows users to monitor credit balances, manage resources, and track costs.
Evidence: Figure 2 confirms that the Azure subscription is active and includes the $200 free trial credit.

Screenshot: Search resource
<img width="430" height="567" alt="Sarch resource" src="https://github.com/user-attachments/assets/ffda2f08-52b9-4455-8d38-56e3a193df33" />
Azure Portal Search Functionality
I used the Azure Portal search bar located at the top of the screen to search for services such as Resource Groups, Storage Accounts, Cost Management, and Microsoft Entra ID.
The search feature allows administrators to quickly locate services without manually browsing through menus, improving efficiency when managing cloud resources.
Evidence: Figure 3 displays recently accessed Azure services and search history.

Screenshot: Dashboard
<img width="1357" height="682" alt="Dash board" src="https://github.com/user-attachments/assets/47c17089-20b9-46d1-b947-3de0a57fe4a6" />
Dashboard Customization
I navigated to Dashboard, selected Edit, and customized the layout by pinning frequently used resources and services.
Tile Configuration
The dashboard contains:
Storage Accounts
Quickstart Tutorials
Recently Created Resources
Frequently Used Services
Custom dashboards improve productivity by providing quick access to commonly used resources and important information.
Evidence: Figure 4 shows the customized Azure Dashboard.

Screenshot: Resource Group Deployment
<img width="1360" height="668" alt="Resource group deployment" src="https://github.com/user-attachments/assets/891d7f39-74b7-4244-bfd1-21038f03bff0" />
Resource Group Deployment
I created a Resource Group named RG-AzureTraining and deployed a Storage Account within it. I accessed the Resource Group and reviewed the deployment status.
Resource Groups provide a logical container for Azure resources, making administration, security, monitoring, and resource organization easier.
Evidence: Figure 5 confirms that the deployment completed successfully with a status of Succeeded.

Sreenshort:Billing and Cost Management
<img width="1144" height="637" alt="Budget Alert Configuration" src="https://github.com/user-attachments/assets/71371bea-349b-40d2-88d6-6580f481a407" />

Accessing Cost Management
Search Cost Management + Billing.
Open Cost Analysis.
Review current usage.
Azure Free Tier Benefits
New Azure accounts generally include:
Initial Credit
USD $200 credit for the first 30 days.
12-Month Free Services
Examples include:
Azure Virtual Machines (selected limits)
Azure Blob Storage
Azure Files
Azure SQL Database
Azure Bandwidth
Always-Free Services
Examples include:
Azure Functions
Event Grid
Azure Advisor
Azure DevTest Labs
Note: Service availability and quotas may change over time.

Sreenshort:Password Protection Policy
<img width="1139" height="639" alt="security" src="https://github.com/user-attachments/assets/3585ac7a-bfaf-42aa-b35f-561ed7dc0c1b" />
Security Considerations
Password Protection Policy
How I Accessed Password Protection Settings
Logged in to the Azure Portal.
Searched for Microsoft Entra ID.
Selected Authentication Methods under the Security section.
Opened Password Protection to review password security settings.

Password Protection Configuration
Caption: Password Protection settings in Microsoft Entra ID showing smart lockout controls, password restrictions, and password security management features.

Multi-Factor Authentication (MFA)
How MFA Can Be Configured
Open Microsoft Entra ID.
Navigate to Multifactor Authentication.
Select the target user account.
Enable MFA.
Register an authentication method such as:
Microsoft Authenticator App
SMS Verification
Phone Call Verification
Complete the verification process.
Why MFA Is Important

Passwords alone can be stolen through phishing attacks, malware, or credential leaks. MFA requires an additional verification step, significantly reducing the likelihood of unauthorized account access.

Benefits of MFA
Stronger account protection
Reduced risk of credential theft
Improved compliance with security standards
Protection against phishing attacks
Security Center and Identity Protection
How I Accessed Security Center
Opened the Azure Portal.
Navigated to Security.
Selected Security Center.
Reviewed security recommendations and identity protection alerts.
Why This Is Important

The Security Center continuously evaluates Azure resources and identities for vulnerabilities, misconfigurations, and security risks. It provides recommendations that help improve the overall security posture of the Azure environment.

Security Features Observed
Identity and Access Recommendations
Security Severity Monitoring
Alert Management
Microsoft Defender for Cloud Integration
Secure Score Recommendations
Azure Security Center

Caption: Azure Security Center displaying security recommendations, identity protection monitoring, and risk assessment information.

Security Best Practices
1. Enable Multi-Factor Authentication
All administrator and user accounts should use MFA to protect against unauthorized access.

2. Use Strong Passwords
Passwords should:
Be at least 12 characters long.
Include uppercase and lowercase letters.
Include numbers and special characters.
Avoid common words or personal information.
3. Follow the Principle of Least Privilege
Users should only receive permissions necessary to perform their assigned tasks.
4. Monitor Security Recommendations
Regularly review Azure Security Center and Microsoft Defender for Cloud recommendations.
5. Review Sign-In Activity
Monitor login attempts and investigate unusual authentication activity.
6. Maintain Multiple Subscription Owners
Azure Security Center recommends having more than one subscription owner to avoid administrative lockout and improve account recovery options.
Why Security Matters in Azure

Cloud security follows a Shared Responsibility Model:

Microsoft Responsibilities
Physical datacenter security
Network infrastructure
Hardware maintenance
Azure platform security
Customer Responsibilities
User accounts and passwords
MFA configuration
Access permissions
Data protection
Resource security settings
