# AzureAD_registered_vs_joined

|  | Windows Sign-in | Device Management | Policy Management | Use Case |
| --- | --- | --- | --- | --- |
| WorkGroup | Local | N/A | N/A | SMEs without servers, **small-scale home networks**, and multiple personal computers used by one person |
| Active Directory Domain Joined | Active Directory | Active Directory | Group Policy | - A domain controller can **centrally manage various settings for all domain-joined Windows computers and users**. <br> - The SSO can only be available by those connected to the local network within the company.|
| Azure AD Registered | Local | - Azure AD <br> - MS Intune | MS Intune | - **Authentication can also be performed for mobile terminals outside the company.** <br> - Bring Your Own Device (BYOD) <br> - Enables access control in Conditional Access policies. |
| Azure AD Joined | Azure AD | - Azure AD <br> - MS Intune | MS Intune | In addition to the Azure AD registered, <br> - **sign-in to an Azure AD-joined device with an Azure AD user.** <br> - **SSO to Azure Resources from outside.** |
| Hybrid Azure AD Joined | Active Directory | - Azure AD <br> - MS Intune <br> - Active Directory | - MS Intune <br> - Group Policy | - Windows 8.1 and 7 will be also available. <br> - SSO to Azure Resources from outside. <br> - **After Windows sign-in to a domain-joined device, you can sign in to Azure without entering a username and password.**|

> https://jpazureid.github.io/blog/azure-active-directory/azure-ad-join-vs-azure-ad-device-registration/ <br>
> https://www.jbsvc.co.jp/useful/windows10/azure_ad.html <br>
> https://learn.microsoft.com/en-us/training/modules/create-configure-manage-identities/7-configure-manage-device-registration
