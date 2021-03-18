---
name: Request for Keycloak Realm
about: To create a set of Keycloak Realms.
title: ''
labels: keycloak-realm, pending, keycloak
assignees: nvunnamm, ConradBoydElliottGustafson, Sandeeparch

---

## Step 0
**Are you the product owner or project admin/team lead?**
If not, you will need to ask one of those two people to make this request for you. 
We can't process realm requests except from individuals in these roles.

**Does the Admin User have an IDIR account?**
We use IDIR authentication for Realm Admin Users, so make sure there's a *valid IDIR* for the assigned realm admin.  

**Are you requesting for Identity Provider Update?**
If so, you need to be the realm admin. Then proceed to Step 3.

## Step 0
We are currently undergoing management of SSO realm resources, as a result we will not onboard new teams for sometime.
Should you have urgent need for SSO/keycloak integration for your application, please connect with SSO Product Owner Vardhman at Vardhman.Shankar@gov.bc.ca


## Step 1
Are you new to RedHat Single Sign-On (Keycloak)? 
If so, please indicate that in Step 4, we will setup an meeting with you and your team for an on-boarding meeting. 


## Step 2
Ask the Realm Admin User to login to each of the following links using the **IDIR credentials**.

When you login, you will see a "_Forbidden_" message, but this is expected behaviour and will create the initial account on Keycloak.

- https://dev.oidc.gov.bc.ca/auth/admin/idir/console
- https://test.oidc.gov.bc.ca/auth/admin/idir/console
- https://oidc.gov.bc.ca/auth/admin/devhub/console

_Please note that if the Realm Admin User has not completed this step, he/she will not be granted the role for the realms._


## Step 3
Field the following information.

* Project Name: 

* OpenShift Project Set/s Info
  - Project set name:  (please provide the namespace name in the form of a 6 character alphanumeric code followed by the environment, like so: a1b2c3-prod.)
  - Namespace ID:

* For existing Keycloak realm update only
  - Realm ID: 
  - Identity Provider to Add
    - [ ] BCeID
    - [ ] GitHub
    - [ ] BCSC


## Step 4
Submit this ticket and email us the contact information.

For security purpose, please provide the following contact information to the email address - pathfinder@gov.bc.ca

* Email to reach out for On-Boarding meeting invitation:
* link to the GitHub ticket you just created: 
* Admin user's IDIR account: 
* Admin user's Business Email Address: 

Please note that we will only start processing your request when the email has been received.


## Step 5
After we have completed processing your request, you can proceed to creating a realm at [Realm-O-Matic](https://realm-o-matic.developer.gov.bc.ca)
