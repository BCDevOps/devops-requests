---
name: Request for an Pathfinder SSO Client in a standard realm
about: To create a set of SSO clients (in KeyCloak DEV, TEST, PROD).
title: ''
labels: keycloak-client, pending, sso
assignees: nvunnamm

---

**If you have an urgent request, please contact our Product Owner at Vardhman.Shankar@gov.bc.ca**

## Step 0
**Are you the product owner or project admin/team lead?**
If not, you will need to ask one of those two people in your organization to make this request for you. 
We cannot process realm requests except from individuals in these roles.

**Note:** This SSO service is undergoing upgrades in 2021 and is currently not recommended for critical applications. Support is currently available only during business hours and only on a best efforts basis. If your application is critical, please contact Web Access Management (WAM) and/or Provincial Identity Information Management Program (IDIM).

## Step 1
Are you new to Single Sign-On (Keycloak)? 
If so, please indicate that in Step 4, we will setup a meeting with you and your team for an onboarding meeting. 

## Step 2
Field the following information.

* Project Name: 

* Identity Providers Required
  - [ ] BCeID Basic
  - [ ] BCeID Business
  - [ ] GitHub
  - [ ] IDIR

* A list of redirect URLs for each environment (DEV, TEST, PROD). *These are the URLs that your application is allowed to use after sign-on events are complete. These are the secure "front door" for your application.*
  - DEV redirect URL(s): 
  - TEST redirect URL(s): 
  - PROD redirect URL(s):

* Client Type Required
  - [ ] Confidential Client (most secure but not appropriate for all architectures)
  - [ ] Public Client with PKCE

## Step 3
For teams requesting access to BCeID, there is an approval process. Please provide the following information on this ticket. The IDIM team will review this information and will be in touch with you at the email provided.
The OCP-SSO team will provision your DEV and TEST clients right away, and your PROD client will be provisioned when the IDIM team approves your request.

* Organization Details (Organization/Division/Branch/Program): 
* **Exectutive Sponsor** Name, Title, & Email: 
* **Project Manager / Business Lead** Name, Title, & Email: 
* **Technical Lead** (if applicable) Name, Title, & Email: 
* **Privacy Lead** (if applicable) Name, Title, & Email: 
* **Security Lead** (if applicable) Name, Title, & Email: 
* **Communications Lead** (if applicable) Name, Title, & Email: 
* Name of service or application:
* URL of service or application:
* Estimated volume of initial users:
* Forecast of anticipated growth over the next three years:
* Date of release in production environment:
* Date of first use by citizens or end users:

## Step 4
Submit this ticket and email us the contact information.

For security purpose, please provide the following contact information to the email address - Vardhman.Shankar@gov.bc.ca

* Email to reach out for On-Boarding meeting invitation:
* link to the GitHub ticket you just created: 
* Product Owner's IDIR name: 
* Product Owner's Business Email Address: 

Please note that we will only start processing your request when the email has been received.
