
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

- Display name: [Enter display name or a sanitized example]
- Username: [Enter a placeholder, not a sensitive account]
- Account status: [Enabled/Disabled]

### Step 2: Create a Security Group

Created a security group to practise organizing users for access management.

**Configuration details:**

- Group name: [Enter group name]
- Group type: Security
- Membership type: Assigned
- Purpose: [Describe the intended use]

### Step 3: Create a Microsoft 365 Group

Created a Microsoft 365 group to understand how Microsoft 365 groups differ from security groups.

**Configuration details:**

- Group name: [Enter group name]
- Group type: Microsoft 365
- Membership type: Assigned
- Purpose: [Describe the intended use]

### Step 4: Add the User to the Group

Added the created user to the relevant group.

**Steps performed:**

1. Opened the group in the Microsoft Entra admin center.
2. Navigated to its membership settings.
3. Added the intended user as a member.
4. Saved the changes and checked the resulting membership.

**Result:** [Record what happened after completing these steps.]

## Verification

The following checks were used to validate the configuration.

- [ ] Confirmed that the user account appears in the directory.
- [ ] Checked the account's enabled or disabled status.
- [ ] Confirmed that the security group exists and has the expected group type.
- [ ] Confirmed that the Microsoft 365 group exists, if created.
- [ ] Checked that the intended user appears in the relevant group's membership list.

**Verification outcome:** [Document the checks you actually performed and their results.]

## Challenges and Troubleshooting

[Describe any issue you encountered and how you resolved it.]

If no issues occurred, state:

"No significant issues were encountered during this lab."

## Licensing Considerations

Dynamic group membership requires appropriate licensing. Microsoft documents a Microsoft Entra ID P1 license or an Intune for Education license for each unique user who belongs to one or more dynamic membership groups.

Dynamic membership was not tested in this lab because [state the actual licensing or access limitation, if applicable].

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

[Edit these points to reflect what you actually learned.]

## Conclusion

This lab provided practical experience with Microsoft Entra ID identity and group management. It helped reinforce the importance of organizing users into groups and verifying membership to support effective access administration.

[Update this conclusion if any of the objectives were not completed.]

## References

- [Microsoft Entra ID documentation](https://learn.microsoft.com/en-us/entra/identity/)
- [Microsoft Entra dynamic membership groups](https://learn.microsoft.com/en-us/entra/identity/users/groups-dynamic-membership)
- [Microsoft AZ-104 hands-on labs](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/)
