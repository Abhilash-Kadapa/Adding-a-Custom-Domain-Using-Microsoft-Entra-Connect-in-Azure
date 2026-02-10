# Adding-a-Custom-Domain-Using-Microsoft-Entra-Connect-in-Azure
This project demonstrates how to add and configure a custom domain (e.g., company.com) in Microsoft Entra ID and synchronize on-premises Active Directory users using Microsoft Entra Connect.

## Architecture
- On-premises Active Directory
- Microsoft Entra Connect (Azure AD Connect)
- Microsoft Entra ID (Azure AD)
- Custom verified domain

## Prerequisites
- Azure subscription with Global Administrator access
- On-premises Active Directory
- Public DNS access for domain verification
- Windows Server for Entra Connect installation

## Implementation Steps
1. Add custom domain in Microsoft Entra ID
2. Verify domain ownership using DNS TXT record
3. Configure UPN suffix in on-prem Active Directory
4. Install and configure Microsoft Entra Connect
5. Synchronize users to Entra ID
6. Validate sign-in using custom domain

## Outcome
Users can authenticate using:
user@company.com

with support for SSO, MFA, and Conditional Access.
![image alt](https://github.com/Abhilash-Kadapa/Adding-a-Custom-Domain-Using-Microsoft-Entra-Connect-in-Azure/blob/main/Entra%20ID-1.png?raw=true)
