# Microsoft Entra ID Privileged Identity Management Lab

## Enforcing Multifactor Authentication with Privileged Identity Management & Sign-In Log Validation

### Project Summary:
This lab will demonstrate how to design , deploy and enforce Entra ID Conditional Access Policy that requires MFA. It will follow this workflow:

* Configuring a Just in time Admin access (Global Administrator) to the admin
* Create Conditional Access policy
* Safe deployment using Report Only Mode
* Live enforcement
* Real sign and testing
* Log monitoring

  ## Security Objectives

* Enforce MFA to all users
* Reduce attack surface by blocking weak authentication paths
* Secure adminisitrative actions by employing PIM
* Validate controls using identity telemetry
* Simulate SOC style identity verification
* Log collection and analysis


## Tools and Environment

- Microsoft Entra ID (P1 or P2)
- Standard User
- Break Glass admin
- MFA
- Azure Portal

## Lab Execution - Step by Step

### Step 1 - Enforce PIM to the admin account

1. Open PIM ( Microsoft Entra ID --> Privileged Identity Management --> My Roles)
2. Search Global Administrator
3. Activate Global Administrator for User "Admin Breakglass"
4. Approve MFA
5. <img width="1605" height="375" alt="AdminBreak Glass Global Admin Role" src="https://github.com/user-attachments/assets/2e918e9b-e7df-4040-a0dc-0e4d9e53a960" />

### Step 2 - Create a Condition Access Policy

