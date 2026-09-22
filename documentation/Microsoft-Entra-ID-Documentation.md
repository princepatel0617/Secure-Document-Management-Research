# Microsoft Entra ID Documentation

## Organization

**Microsoft**

## Documentation

[Microsoft Entra ID Documentation](https://learn.microsoft.com/en-us/entra/identity/)

---

## What is Microsoft Entra ID?

Microsoft Entra ID is Microsoft's cloud-based identity and access
management service.

It helps organizations manage digital identities and control access to
applications, services and resources.

---

## Key Capabilities

### Identity Management

Entra ID provides centralized management of users, groups and digital
identities.

### Authentication

It provides authentication mechanisms for verifying the identity of users
before they access protected resources.

### Multi-Factor Authentication

MFA adds additional verification beyond a user's primary credentials,
providing an additional layer of protection for sensitive resources.

### Access Management

Entra ID supports controlling access to organizational applications and
resources based on identity and access policies.

---

## Relevance to Our Project

Microsoft Entra ID provides the **identity and authentication layer** of
the proposed Secure Digital Document Management System.

Legal and investigation documents can contain highly sensitive
information, so access should be limited to authenticated and authorized
users.

Entra ID can provide the identity foundation used before users access the
SharePoint-based document environment.

---

## Application in the Proposed System

```text
                  USER
                    │
                    ▼
            Microsoft Entra ID
                    │
              Authentication
                    │
                    ▼
                   MFA
                    │
                    ▼
          Authorized Application
                    │
                    ▼
          Microsoft SharePoint
