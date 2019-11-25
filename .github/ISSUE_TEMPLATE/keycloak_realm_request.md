---
name: Request for KeyCloak Realm
about: To create a set of KeyCloak Realms
title: ''
labels: keycloak-realm
assignees: caggles, ShellyXueHan

---

## Step 0
**Are you the product owner or project admin/team lead?**
If not, you will need to ask one of those two people to make this request for you. We can't process realm requests except from individuals in these roles.

**Do you have an IDIR account?**
We use IDIR authentication for realm admin users, so you *must* have one in order to become a realm admin.  

**Are you requesting for Identity Provider Update?**
If so, you need to be the realm admin. Then proceed to Step 2.


## Step 1
Login to each of the following links using your **IDIR credentials**. You will then see a "_Forbidden_" message, but this is expected behaviour and will actually create your initial account on KeyCloak.
- https://sso-dev.pathfinder.gov.bc.ca/auth/admin/idir/console
- https://sso-test.pathfinder.gov.bc.ca/auth/admin/idir/console
- https://sso.pathfinder.gov.bc.ca/auth/admin/devhub/console


## Step 2
Field the following information.

* Project Name: 
* For existing KeyCloak realm update only:
  - Realm ID: 
  - Identity Provider to add: IDIR or BCeID or GitHub


## Step 3
Submit this ticket and email us the contact information.

For security purpose, please provide the following contact information to the email address - pathfinder@gov.bc.ca

* link to the GitHub ticket you just created: 
* Admin user's IDIR account: 
* Admin user's Business Email Address: 

Please note that we will only start processing your request when the email has been received.


## Step 4
After we have completed processing your request, you can proceed to creating a realm at Realm-O-Matic: https://realm-o-matic.pathfinder.gov.bc.ca/
