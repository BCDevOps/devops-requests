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

If you are a member in bcgov or BCDevOps org and are inviting another user to the org, your request will be approved automatically and processed right away.  The invited user will get an invite in the email to join the org. Only after the invite is accepted, the membership will be granted to the invite user's GitHub ID account.

If you are __asking to invite yourself to an org__ please note that the request will not be automatically approved. An administrator of the bcgov and bcdevops github organizations will still need to approve the request. If this is not done in a timely manner please ping one of our Platform Admin @patricksimonian @cailey.jones or @shelly.han in [#devops-operations](https://chat.developer.gov.bc.ca/channel/devops-operations) channel in Rocket.Chat.

## Removing Access

If you are removing access please follow the steps below.

## Step 0

**Are you looking for access to the Openshift Console?**
Please note that this ticket is to request membership in our GitHub Organization used for sharing the many open-source projects ongoing at BCGov.
Typically, membership is required for those employees and contractors who need the ability to create new repositories there.
This ticket does not grant access to Openshift! There's another ticket template for that!

**Are you the Technical Lead?**
If not, you need to ask your team's Technical Lead role to make this request on your behalf. 
This person must already be a member of the bcgov GitHub Organization in order for us to process this request.

If you are a technical lead and you've come here to request access for yourself, please go ahead and create this ticket, and then 
contact @mitovskaol (Olena Mitovska) with a link to the ticket so she can approve it.

**Do you actually need the team member to be a member of the organization?**
Often, it works just fine to have a team member as a Collaborator on your repository, without them being a member of 
the `bcgov` GitHub organization. Before submitting this request, consider whether you could simply invite your team 
member to contribute as a Collaborator.  
Instructions [here](https://help.github.com/en/github/setting-up-and-managing-your-github-user-account/inviting-collaborators-to-a-personal-repository).


## Step 1
Visit DevHub for detailed instruction on creating a request:
https://developer.gov.bc.ca/Getting-Started-on-the-DevOps-Platform/How-to-request-new-GitHub-user-access-or-repository-creation

## Step 2
Make sure no duplicated request exists, search here:
https://github.com/BCDevOps/devops-requests/issues


## Step 4
Are you requesting to:
- [x] Invite a user
- [ ] Remove a user


## Step 5
Fill out the following fields

* Project Name: 
* GitHub Org: bcgov or private
* Full Name: 
* GitHub ID: @
* GitHub Account 2FA Confirmed: yes or no
* Email address: 
* Organization: 
* Project Role: 
* GitHub Team to Join (if exists): 
* Existing GitHub Repo: 


**Note** that the platform services team will be removing GitHub Org access for users that are not active for six months. Once the access has been removed, a new `Access Request` has to be made by the product owner.
