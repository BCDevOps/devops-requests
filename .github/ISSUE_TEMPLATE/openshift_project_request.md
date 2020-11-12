---
name: Request for Removal of OCP 3.11 Project Set
about: To remove an OpenShift 3.11 Project Set after all environments have been migrated to the OCP 4 Platform.
title: ''
labels: openshift-project-set, pending
assignees: caggles, mitovskaol, ShellyXueHan

---

## Step 0
**Are you the Product Owner or Technical Lead?**
If not, you will need to ask one of those two people to make this request.

If you are one of these two people, please ensure that you also request Openshift access if you don't have it already. This request does NOT grant you access to the platform itself - you will find a separate request for that on the issues page of this repo!
However, you may submit both requests at the same time - there's no need to wait until that request has been completed to submit this one.

**Have you migrated all workloads including production from the OCP 3.11 namespaces to the OCP 4 Silver cluster?**
If not, please do so before you submit the request.

**Have you scaled down all pods to 0 in all 4 project set namespaces - dev, test, tools and prod ?**
If not, please do so before you submit the request.

## Step 1
Make sure no duplicated request exists, search here:
https://github.com/BCDevOps/devops-requests/issues


## Step 2
Confirm that you are aware that you are requesting to:
- [ ] Remove a project set 

**Note: There is no rollback or restore of the deployments once a namespace is deleted.



