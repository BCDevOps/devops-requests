---
name: Request for KeyCloak Realm
about: To create a set of KeyCloak Realms.
title: ""
labels: keycloak-realm, pending
assignees: caggles, ShellyXueHan
---

## Step 0

**Are you the product owner or project admin/team lead?**
If not, you will need to ask one of those two people to make this request for you. We can't process realm requests except from individuals in these roles.

**Does the Admin User have an IDIR account?**
We use IDIR authentication for Realm Admin Users, so make sure there's a _valid IDIR_ for the assigned realm admin.

**Are you requesting for Identity Provider Update?**
If so, you need to be the realm admin. Then proceed to Step 3.

## Step 1

Are you new to RedHat Single Sign-On (KeyCloak)? If so, please indicate that in Step 4, we will setup an meeting with you and your team for an on-boarding meeting.

## Step 2

Ask the Realm Admin User to login to each of the following links using the **IDIR credentials**.

When you login, you will see a "_Forbidden_" message, but this is expected behaviour and will actually create the initial account on KeyCloak.

- https://sso-dev.pathfinder.gov.bc.ca/auth/admin/idir/console
- https://sso-test.pathfinder.gov.bc.ca/auth/admin/idir/console
- https://sso.pathfinder.gov.bc.ca/auth/admin/devhub/console

_Please note that if the Realm Admin User has not completed this step, he/she will not be granted the role for the realms._

## Step 3

Field the following information.

- Project Name:

- OpenShift Project Set/s Info

  - Project set name:
  - Namespace ID:

- For existing KeyCloak realm update only
  - Realm ID:
  - Identity Provider to Add
    - [ ] BCeID
    - [ ] GitHub
    - [ ] BCSC

## Step 4

Submit this ticket and email us the contact information.

For security purpose, please provide the following contact information to the email address - [pathfinder@gov.bc.ca](mailto:pathfinder@gov.bc.ca?subject=DevOps%20Request%20KeyCloak%20Realm&body=%2A%20Link%20to%20the%20GitHub%20ticket%20you%20just%20created%3A%0A%2A%20Email%20to%20reach%20out%20for%20On-Boarding%20meeting%20invitation%3A%0A%2A%20Admin%20user%27s%20IDIR%20account%3A%0A%2A%20Admin%20user%27s%20Business%20Email%20Address%3A)

- Link to the GitHub ticket you just created:
- Email to reach out for On-Boarding meeting invitation:
- Admin user's IDIR account:
- Admin user's Business Email Address:

Please note that we will only start processing your request when the email has been received.

## Step 5

After we have completed processing your request, you can proceed to creating a realm at Realm-O-Matic: https://realm-o-matic.pathfinder.gov.bc.ca/
