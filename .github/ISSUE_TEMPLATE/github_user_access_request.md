---
name: Request for BCGOV GitHub Organization Membership
about: To grant or remove access for a team member to BCGOV GitHub repositories.
title: ''
labels: github-membership
assignees: caggles, ShellyXueHan, mitovskaol, patricksimonian
---
## What we use GitHub Org Membership for

We use the membership in the GitHub org - bcgov and BCDevOps - to control access to the following functions on the DevOps Openshift Platform: 
- a membership in **bcgov** org allows teams to create **public** repos in bcgov org and to deploy their code to the Openshift Platform
- a membership in **BCDevOps** org grants developers access to the Openshift 4 Console (Silver cluster). Note that it does **not** grant access to any namespaces in Openshift. Access to the namespaces is granted to Product Owner and Technical Lead through the Project Registry at the time of the namespace creation or can be granted by them to other team members.
## Changes to Github Organization Membership Requests

There have been changes to the Github Access management workflow to __better automate__ the process. Please read the details below.
### Requesting a membership in bcgov and BCDevOps orgs

If you are making a simple request to invite someone or yourself to the bcgov or BCDevOps organizations in GitHub, this can now be done with the
[Platform Service's Github Access Managmenet Tool](https://just-ask-web-bdec76-prod.apps.silver.devops.gov.bc.ca/). You do not need to open a ticket or create a GitHub issue anymore, please use the app for all org membership requests. 

If you are a member in bcgov or BCDevOps org and are inviting another user to the org, your request will be approved automatically and processed right away.  The invited user will get an invite in the email to join the org. Only after the invite is accepted, the membership will be granted to the invited user's GitHub ID account.

If you are __asking to invite yourself to an org__ please note that the request will **not** be automatically approved. An administrator of the bcgov and bcdevops github organizations will still need to approve the request. If this is not done in a timely manner please ping one of our Platform Admin @patricksimonian @cailey.jones or @shelly.han in [#devops-operations](https://chat.developer.gov.bc.ca/channel/devops-operations) channel in Rocket.Chat.

## Removing Access

If you are removing access please **provide responses to all the steps below**. All questions are mandatory.

## Step 1

**Are you the Technical Lead?**
If not, you need to ask your team's Technical Lead role to make this request on your behalf. 
This person must already be a member of the bcgov GitHub Organization in order for us to process this request.

If you are a technical lead and you've come here to request access for yourself, please go ahead and create this ticket, and then 
contact @mitovskaol (Olena Mitovska) with a link to the ticket so she can approve it.

## Step 2
Fill out the following fields

* Project Name:
* Technical Lead Github ID:
* GitHub Org: bcgov or private
* GitHub ID: @
* Reason for removal:


**Note** that the Platform Services Team will be removing GitHub Org access **automatically** for users that are not active for six months. Once the access has been removed, a new `Access Request` has to be made by the product owner.
