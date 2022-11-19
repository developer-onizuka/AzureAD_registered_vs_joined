# AzureAD_registered_vs_joined

|  | Windows Sign-in | Device Management | Policy Management | Use Case |
| --- | --- | --- | --- | --- |
| Work Group | Local | N/A | N/A |  |
| Active Directory Domain Joined | Active Directory | Active Directory | Group Policy |  |
| Azure AD Registered | Local | - Azure AD <br> - MS Intune | MS Intune | - Bring Your Own Device (BYOD) <br> - Enables access control in Conditional Access policies. |
| Azure AD Joined | Azure AD | - Azure AD <br> - MS Intune | MS Intune | In addition to the Azure AD registered, <br> - sign-in to an Azure AD-joined device with an Azure AD user <br> - SSO |
