# Azure Identity, Access, and Security

## Directory Services

- Azure Active Directory
  - identity service in Azure
  - authenticates and authorizes
  - controls access
  - service principle - AAD application
  - managed identity - Azure resources

## Azure AD Domain Services

- Cloud-based Windows Active Directory
- Uses managed domains and replica sets
- Why?
  - no support for modern auth methods
  - integrate Azure AD resources with AD

## Single Sign-On

- authenticate using credentials used with OS
- Azure AD Connect allows SSO to on-premises
- uses two methods
  - password hash synchronization
  - pass-through authentication

## Multi-Factor Authentication

- authentication factors
- azure MFA is two-factor authentication

## Passwordless

- FIDO2 Security Key
- Microsoft Authenticator App
- Text message authentication
- Temporary Access Pass
- Certificate
- Windows Hello for Business

## Azure AD Conditional Access

- Applies policies against users accessing resources
- Signals
- Decisions

## Azure Role-Based Access Control (RBAC)

- authorizes users based on their role
- three elemenets
  - security principal
  - role
  - scope

## Zero Trust

- Assumes breach
- Network endpoints, data, apps, infrastructure, and network
- Includes:
  - Use MFA
  - Use Conditional Access

## Microsoft Defender for Cloud

- Azure resources, on-premises, and other clouds
- Features
  - Security
  - Regulatory compliance
  - Workload protections
- Constantly monitors and protects
