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

The following screenshots document the lab configuration and security testing in sequence.

### 01 — Server Manager / Active Directory Domain Services
![01 - Server Manager AD DS](./screenshots/01-server-manager-ad-ds.png.png)

### 02 — AD DS Deployment Configuration
![02 - AD DS Deployment Configuration](./screenshots/02-ad-deployment-configuration.png.png)

### 03 — Active Directory Forest
![03 - AD Forest](./screenshots/03-ad-forest.png.png)

### 04 — Active Directory Domain
![04 - AD Domain](./screenshots/04-ad-domain.png.png)

### 05 — Domain Controller Login
![05 - Domain Controller Login](./screenshots/05-domain-controller-login.png.png)

### 06 — Active Directory Users and Computers
![06 - Active Directory Users and Computers](./screenshots/06-active-directory-users-computers.png.png)

### 07 — Organizational Units
![07 - Active Directory OUs](./screenshots/07-active-directory-ous.png.png)

### 08 — Test User: John Smith
![08 - AD Test User](./screenshots/08-ad-test-user.png.png)

### 09 — SecurityTeam Group
![09 - AD Security Group](./screenshots/09-ad-security-group.png.png)

### 10 — Password Policy
![10 - Password Policy](./screenshots/10-password-policy.png.png)

### 11 — Account Lockout Policy
![11 - Account Lockout Policy](./screenshots/11-account-lockout-policy.png.png)

### 12 — Group Policy Update
![12 - GPUpdate](./screenshots/12-gpo-update.png.png)

### 13 — SecurityShare and Group Access
![13 - SecurityShare](./screenshots/13-security-share.png.png)

### 14 — File and Folder Permissions
![14 - File and Folder Permissions](./screenshots/14-file-folder-permissions.png.png)

### 15 — Security Audit Logon Policy
![15 - Audit Logon Policy](./screenshots/15-audit-logon-policy.png.png)

### 16 — GPUpdate After Auditing Configuration
![16 - GPUpdate Audit](./screenshots/16-gpupdate-audit.png.png)

### 17 — Failed Login Test
![17 - Failed Login Test](./screenshots/17-failed-login-test.png.png)

### 18 — Event ID 4625 Failed Login Events
![18 - Event ID 4625 Failed Login](./screenshots/18-event-4625-failed-login.png.png)

## Skills Demonstrated

- Active Directory administration
- Windows Server administration
- Identity and access management
- Group Policy
- Access control
- Windows security auditing
- Event log investigation
- PowerShell
