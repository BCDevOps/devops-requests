---
name: Request for an Pathfinder SSO Client in a standard realm
about: To create a set of Pathfinder SSO clients (in KeyCloak DEV, TEST, PROD).
title: ''
labels: sso-onboarding, pending, sso, BCeID
assignees: jlangy, junminahn, arcshiftsolutions, zsamji, nvunnamm, ConradBoydElliottGustafson

---

## Before you start, you should know 

For detailed information on the service, please reference the [Pathfinder SSO Wiki](https://github.com/bcgov/ocp-sso/wiki).

**This GitHub request process is only applicable for teams looking for integration with BCeID through Pathfinder SSO.** 

If you only need IDIR login, use the [Pathfinder SSO Client Request Web App](https://bcgov.github.io/sso-requests/). If you are looking for integration for IDIR login the process is completely self-serve and takes only minutes. You will need an IDIR to log in and you _should_ be a product owner, product admin, or team lead for a project. Once the automated provisioning is complete, your client details will be available securely through the web app. 

**If you have an urgent request, please contact the Pathfinder SSO Product Owner at bcgov.sso@gov.bc.ca**

## Step 0
**Are you the product owner or project admin/team lead?**
If not, you will need to ask one of those two people in your organization to make this request for you. 
We cannot process realm requests except from individuals in these roles.

**Note:** This SSO service is undergoing upgrades in 2021 and is currently not recommended for critical applications. Support is currently available only during business hours and only on a best efforts basis. If your application is critical, please contact Web Access Management (WAM) and/or Provincial Identity Information Management Program (IDIM).

## Step 1
Field the following information.

Project Name: 

## Step 2
Select BCeID identity provider flavour

(Note: GitHub integration is available in all standard realms for developer convenience. It is not in Production).

(Note: If you are not looking for BCeID integration use the [Pathfinder SSO Client Request Web App](https://bcgov.github.io/sso-requests/) instead of submitting this issue)
  - [ ] BCeID Basic
  - [ ] BCeID Business
  - [ ] Both BCeID Basic AND BCeID Business
  - [X] IDIR (provided by default in all standard realms)

## Step 3
Provide a list of redirect URLs for each environment (DEV, TEST, PROD). *These are the URLs that your application is allowed to use after sign-on events are complete. These are the secure "front door" for your application.* If you do not know the URLs for all your environments, you can use a temporary one such as "http://localhost:5000" and change it later.
  - DEV redirect URL(s): 
  - TEST redirect URL(s): 
  - PROD redirect URL(s):

## Step 4
For teams requesting access to BCeID, there is an approval process. Please provide the following information on this ticket. The IDIM team will review this information and will be in touch with you at the email provided.
The OCP-SSO team will provision your DEV and TEST clients right away, and your PROD client will be provisioned when the IDIM team approves your request.

For security purpose, please provide the following contact information to the email address bcgov.sso@gov.bc.ca with the subject "For the BCeID Team"


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

## Step 5
Submit this ticket and email us the contact information.

For security purpose, please provide the following contact information to the email address - bcgov.sso@gov.bc.ca with the subject "For the Pathfinder SSO Team"

* Email to reach out for On-Boarding meeting invitation:
* link to the GitHub ticket you just created: 
* Product Owner's IDIR name: 
* Product Owner's Business Email Address: 
* Are you new to Single Sign-On (Keycloak)? If so, we will setup a meeting with you and your team for an onboarding meeting. 

Please note that we will only start processing your request when the email has been received.
