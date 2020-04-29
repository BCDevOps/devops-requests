---
name: Request to remove a user from KeyCloak
about: To remove an IDIR or BCeID user when username update causes conflicts
title: ''
labels: keycloak-user
assignees: caggles, ShellyXueHan

---

## Step 0
**Are you the KeyCloak Realm Admin?**
If not, you will need to ask one of the admin user in your realm to make this request instead.


## Step 1
Deleting the user account from KeyCloak will also remove records with any other application using KeyCloak that the user has logged into. So before proceeding with this request, make sure the user is aware of the consequences!

- [ ] Confirm that user is ready to have the account removed from KeyCloak


## Step 2
Field the following information.

* Username to be removed: 
* Realm ID where user is having problem login: 
