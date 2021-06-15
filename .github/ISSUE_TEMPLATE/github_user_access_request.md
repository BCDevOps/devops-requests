---
name: Request for Openshift and BCGOV GitHub Organization Membership
about: To grant or remove access for a team member to BCGOV GitHub repositories and Openshift.
title: ''
labels: 
  - github-membership
  - openshift-access
assignees: caggles, ShellyXueHan, mitovskaol, patricksimonian
---

## What we use GitHub Org Membership for

There are three GitHub orgs that are managed by BC Government:
- __bcgov__: 
  - __Is used__ for public repos/projects/applications for BC Government. 
  - Membership in this organization is required to create new repositories in the organization.
  - **You do not need org membership to contribute to these repositories.**
  -  Membership requests submitted for a new member by an existing member are **approved automatically**. Platform Services Team's approval is required for the requests submitted by a user for themselves.
- __BCDevops__: 
  - Is used for devops specific tooling and issue tracking related to the Openshift 4 Platform.
  - __Is not used__ for public BC Government applications/projects 
  - Membership in **BCDevOps** org is required to access [__Openshift 4 Silver Cluster Console__](https://console.apps.silver.devops.gov.bc.ca/dashboards).
  - You do not need org membership to contribute to these repositories.
  -   Membership requests submitted for a new member by an existing member are **approved automatically**. Platform Services Team's approval is required when a request is made on your own behalf
- __bcgov-c__: 
  - __Is used__ for private repositories/projects.
  - Org membership is limited, by Platform Services Team's approval only as it requires a user license  and is only granted in special cases. 



## Changes to Github Organization Membership Requests

There have been changes to the Github Access management workflow to __better automate__ the process. Please read the details below. There is also a [YouTube video describing the workflow](https://www.youtube.com/watch?v=IvdPyx2-qm0)

### Requesting membership to bcgov and BCDevOps orgs

If you are making a simple request to invite someone or yourself to the bcgov or BCDevOps organizations in GitHub, this can now be done with the
[Platform Service's Github Access Management Tool](https://just-ask-web-bdec76-prod.apps.silver.devops.gov.bc.ca/). You do not need to open a ticket or create a GitHub issue anymore, please use the app for all org membership requests. 

If you are a member in bcgov or BCDevOps org and are inviting another user to the org, your request will be approved automatically and processed right away.  The invited user will get an invite in the email to join the org. Only after the invite is accepted, the membership will be granted to the invited user's GitHub ID account.

If you are __asking to invite yourself to an org__ please note that the request will **not** be automatically approved. The Platform Services Team will need to review the request to confirm your affiliation with the BC Government (**please indicate in the request if you are a government employee or include the name of the project and Ministry that you are working on, if you are a contractor, to expedite the approval process) before it can be approves. If this is not done in a timely manner please ping one of our Platform Admin @patrick.simonian @cailey.jones or @shelly.han in [#devops-operations](https://chat.developer.gov.bc.ca/channel/devops-operations) channel in Rocket.Chat.

### Requesting membership to bcgov-c

These requests are not fulfilled through this issue. Typically requesting access to the org is done at the repository collaboration level. You will need to get in contact with the repo admin for access. If you are seeking a new private repository see [Requesting a Private Repository](https://github.com/BCDevOps/devops-requests/issues/new?assignees=caggles%2C+ShellyXueHan%2C+mitovskaol%2C+patricksimonian&labels=github-repo%2C+pending&template=github_repo_request.md&title=)

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
* GitHub Org: bcgov, BCDevops, or private
* GitHub ID: @
* Reason for removal:


**Note** that the Platform Services Team will be removing GitHub Org access **automatically** for users that are not active for six months. Once the access has been removed, a new `Access Request` has to be made by the product owner.
