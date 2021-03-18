---
name: Request to remove a duplicate user from Keycloak
about: To remove an IDIR or BCeID user when username update causes conflicts
title: ''
labels: keycloak-user, sso
assignees: nvunnamm

---

## Step 0
**Are you the Keycloak Realm Admin?**
If not, you will need to ask one of the admin user in your realm to make this request instead.


## Step 1
Provide some background on the user account issue.
- What is the issue with the user account?
- What result of debugging have you obtained that lead you to request an account removal?


## Step 2
Deleting the user account from Keycloak will also remove records with any other application using Keycloak that the user has logged into. So before proceeding with this request, make sure the user is aware of the consequences!

- [ ] Confirm that user is ready to have the account removed from Keycloak


## Step 3
Field the following information.

* Username to be removed: 
* Realm ID where user is having problem login: 
