
# Lab 01: Manage Azure Identities

## Overview

This lab focuses on identity and group management in Microsoft Entra ID. It covers creating a user account, creating security and Microsoft 365 groups, and managing group membership.

The purpose of this lab is to practise identity administration tasks relevant to Azure administration and access management.

## Objectives

- Create a Microsoft Entra ID user account.
- Create a security group.
- Create a Microsoft 365 group.
- Add a user to the appropriate group.
- Verify that the user and group configurations are correct.
- Understand the licensing requirements for dynamic group membership.

## Technologies Used

- Microsoft Azure
- Microsoft Entra ID
- Microsoft Entra admin center

## Prerequisites

- Access to a Microsoft Entra tenant.
- Sufficient permissions to create users and groups.
- A web browser and internet connection.

## Implementation

### Step 1: Create a User Account

Created a user account in Microsoft Entra ID using the Microsoft Entra admin center.

**Configuration details:**

- Display name: user1
- Username: user1
- Account status: Enabled
 <img width="1337" height="856" alt="Screenshot 2026-10-15 045652" src="https://github.com/user-attachments/assets/40a5e3a4-a124-4052-ba03-7ebfd49618df" />

### Step 2: Create a Security Group

Created a security group to practise organizing users for access management.

**Configuration details:**

- Group name: Secgroup
- Group type: Security
- Membership type: Assigned
<img width="1164" height="900" alt="secgroup" src="https://github.com/user-attachments/assets/5a64db20-84ed-4de9-b0f7-4d0a08398999" />


### Step 3: Create a Microsoft 365 Group

Created a Microsoft 365 group to understand how Microsoft 365 groups differ from security groups.

**Configuration details:**

- Group name: M365group
- Group type: Microsoft 365
- Membership type: Assigned
  <img width="591" height="431" alt="m365group" src="https://github.com/user-attachments/assets/b0b2e727-05d7-40c8-8e15-346669e2d5f2" />

### Step 4: Add the User to the Group

Added the created user to the relevant group.

**Steps performed:**

1. Opened the group in the Microsoft Entra admin center.
2. Navigated to its membership settings.
3. Added the intended user as a member.
4. Saved the changes and checked the resulting membership.
<img width="1457" height="923" alt="m365mem" src="https://github.com/user-attachments/assets/9322b9e8-9500-473d-8514-eba300fe2e56" />

## Challenges and Troubleshooting

"No significant issues were encountered during this lab."

## Licensing Considerations

Dynamic group membership requires appropriate licensing. Microsoft documents a Microsoft Entra ID P1 license or an Intune for Education license for each unique user who belongs to one or more dynamic membership groups.

Dynamic membership was not tested in this lab because the subscription used is free.

Reference: https://learn.microsoft.com/en-us/entra/identity/users/groups-dynamic-membership

## Cleanup

- [ ] Removed temporary test users or groups if they were no longer required.
- [ ] Confirmed that no unnecessary resources or assignments remained.

Do not remove accounts, groups, or assignments that are required by an organization or other workloads.

## Lessons Learned

- Practised creating and managing Microsoft Entra ID user accounts.
- Explored the use of security and Microsoft 365 groups.
- Practised checking group membership to validate identity configuration.
- Learned about the licensing considerations for dynamic group membership.

## Conclusion

This lab provided practical experience with Microsoft Entra ID identity and group management. It helped reinforce the importance of organizing users into groups and verifying membership to support effective access administration.

## References

- [Microsoft Entra ID documentation](https://learn.microsoft.com/en-us/entra/identity/)
- [Microsoft Entra dynamic membership groups](https://learn.microsoft.com/en-us/entra/identity/users/groups-dynamic-membership)
- [Microsoft AZ-104 hands-on labs](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/)
