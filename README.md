
# Microsoft 365 License Management

## Overview

This repository covers basic Microsoft 365 license administration, including assigning licenses, reviewing availability and troubleshooting licensing issues.

## Tools

- Microsoft 365 Admin Center
- Microsoft Entra Admin Center
- Microsoft 365 User Management

## Common Administration Tasks

- Checking available licenses
- Assigning licenses to users
- Reviewing assigned licenses
- Removing licenses when approved
- Checking license usage
- Troubleshooting license assignment issues

## Checking License Availability

1. Sign in to the Microsoft 365 Admin Center.
2. Navigate to Billing > Licenses.
3. Select the required subscription or product.
4. Review total, assigned and available licenses.
5. Confirm availability before assigning a license.

## Assigning a License

1. Open Users > Active users.
2. Search for the required user.
3. Open the user's account.
4. Navigate to Licenses and apps.
5. Select the required license.
6. Review the available service options.
7. Save the changes.
8. Verify that the license is assigned.

## Removing a License

Before removing a license:

- Confirm that the request is approved.
- Check whether the user still requires the service.
- Review possible effects on email, files and other services.
- Follow the organization's retention and offboarding procedures.
- Verify the result after the change.

## Group-Based Licensing

Microsoft Entra ID supports assigning licenses through groups in supported environments.

Important checks include:

- Group membership
- Available licenses
- License assignment errors
- Conflicting service plans

## Basic Troubleshooting

| Issue | What to Check |
|---|---|
| License cannot be assigned | Available licenses and permissions |
| User missing a service | Assigned license and enabled service plans |
| Group license not applied | Group membership and processing errors |
| License assignment error | Usage location and licensing requirements |
| Incorrect license | Assigned products and approved requirements |

## Best Practices

- Verify the correct user before making changes.
- Assign only approved licenses.
- Check license availability.
- Review service impact before removing licenses.
- Document completed changes.
- Avoid publishing tenant information or user details.

## Note

This repository contains general technical documentation. No real tenant details, user accounts or subscription information are included.
