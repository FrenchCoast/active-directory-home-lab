# Phase 4: Active Directory Users, Groups, and Organizational Units

**Project:** Active Directory Home Lab  
**Environment:** Windows Server 2025 and Active Directory  
**Status:** Configuration evidence available.

## 1. Objective

The objective of this phase was to create and organize domain accounts and security groups to simulate a small business environment.

Active Directory allows administrators to centrally manage employee accounts and assign permissions based on department responsibilities.

## 2. Creating the Domain Administrator Account

A domain administrator account was created for administrative tasks within the lab.

Administrator accounts are used to perform tasks that require elevated permissions, such as managing users, groups, and domain resources.

**Evidence:** `domain-admin-created.PNG`

## 3. Creating Department Users

User accounts were created for the HR and IT departments.

These accounts represent employees who need access to different network resources.

The accounts were organized according to their department.

**Evidence:** `users-created-in-HR-and-IT.PNG`

## 4. Creating Security Groups

Security groups were created to simplify permission management.

Instead of assigning permissions individually to every user, administrators can add users to groups and assign permissions to those groups.

This makes it easier to manage access as employees join, leave, or change departments.

**Evidence:** `Security-Groups-and-Users.PNG`

## 5. Organizational Structure

The lab uses separate department accounts and groups to simulate an organization.

Example structure:

```text
Domain
│
├── HR
│   └── HR Users
│
├── IT
│   └── IT Users
│
└── Security Groups
    ├── HR Security Group
    └── IT Security Group
```

*This is a conceptual example. The actual organizational units and group names should match the configuration in Active Directory.*

## 6. Verification

The following items should be checked in Active Directory Users and Computers:

- Confirm that the domain administrator account exists.
- Confirm that HR and IT user accounts exist.
- Confirm that the security groups exist.
- Verify that users are members of their intended groups.
- Verify that the accounts are enabled.

## 7. Skills Demonstrated

- Creating Active Directory users.
- Creating security groups.
- Managing group membership.
- Organizing employee accounts.
- Understanding centralized account management.
- Applying role-based access concepts.

## 8. Conclusion

This phase demonstrated how Active Directory can organize employee accounts and security groups in a business environment. Using groups provides a more manageable approach to assigning permissions and controlling access to shared resources.
