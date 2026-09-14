# Active Directory Security Lab

Hands-on Active Directory administration and Windows security lab built in a virtual Windows Server environment.

## Objectives

- Deploy a Windows Server Domain Controller
- Configure Active Directory Domain Services
- Create users, security groups, and OUs
- Configure Group Policy
- Configure password and account lockout policies
- Configure file and folder permissions
- Enable Windows security auditing
- Investigate Windows security events

## Lab Environment

- Windows Server 2025
- Active Directory Domain Services (AD DS)
- DNS
- Group Policy
- Windows Event Viewer
- PowerShell
- VirtualBox

## Active Directory Configuration

- Domain: `corp.local`
- Domain Controller: Windows Server 2025
- Organizational Units: IT, Security
- User account: John Smith
- Security group: SecurityTeam
- Group-based access control

## Security Configuration

- Password policy
- Account lockout policy
- Windows Firewall
- Security auditing
- Group Policy security settings

## Permissions

Configured a protected folder and assigned access through the `SecurityTeam` group.

## Security Testing

- Failed login attempts
- Account lockout testing
- Permission testing
- Windows security event investigation
- Group membership verification

## Evidence

Screenshots documenting the lab configuration and security testing are available in the `screenshots/` folder.

## Skills Demonstrated

- Active Directory administration
- Windows Server administration
- Identity and access management
- Group Policy
- Access control
- Windows security auditing
- Event log investigation
- PowerShell
