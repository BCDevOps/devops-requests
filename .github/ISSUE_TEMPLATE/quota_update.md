---
name: Request to Change OCP 3.11 Project Set Quotas
about: Request changes to cpu/storage/etc
title: ''
labels: quota-update, pending
assignees: caggles, ShellyXueHan, patricksimonian

---

## Step 0
**Are you making this request for OCP4?**
In OCP4, you can now make this change yourself with our [Project Registry](https://registry.developer.gov.bc.ca/) tool! 
Just click the link and login. If you submit a request here for an OCP4 namespace, please note that it will be closed without action.

**Are you the product owner or technical lead?**
If not, you will need to ask one of those two people to make this request.


## Step 1
Make sure no duplicated request exists, search here:
https://github.com/BCDevOps/devops-requests/issues


## Step 2
What quotas need to be changed? (Select all that apply)
- [ ] CPU: Long Running (compute-long-running-quota)
   - [ ] CPU Limit
   - [ ] Memory Limit
   - [ ] CPU Request
   - [ ] Memory Request
- [ ] CPU: Time Bound (compute-time-bound-quota)
   - [ ] CPU Limit
   - [ ] Memory Limit
   - [ ] CPU Request
   - [ ] Memory Request
- [ ] Storage: Netapp Block (storage-netapp-block-standard-quota)
   - [ ] Number of PVCs
   - [ ] Total Storage
- [ ] Storage: Netapp File (storage-netapp-file-standard-quota)
   - [ ] Number of PVCs
   - [ ] Total Storage
- [ ] Storage: NFS Backup (storage-nfs-backup-quota)
   - [ ] Number of PVCs
   - [ ] Total Storage
- [ ] Storage: Gluster Block (storage-gluster-block-quota)
   - [ ] Number of PVCs
   - [ ] Total Storage
- [ ] Storage: Gluster File (storage-gluster-file-quota)
   - [ ] Number of PVCs
   - [ ] Total Storage
- [ ] General Storage Quota (storage-quota)
   - [ ] Number of PVCs
   - [ ] Total Storage

## Step 3
Please provide the namespace(s) to which these quota changes need to be applied:

**Note: ensure you are providing the namespace name, not the project display name. It should be a string of 6 random alphanumeric characters, followed by -tools, -dev, -test or -prod.**

## Step 4
Add details about your quota request here.

*ex: Please increase number of PVCs that can be provisioned to 30.*

## Step 5
Please explain here the reasons for requesting your quota change.

Remember that OCP is a shared resource. Please be community-minded in making these requests and include thorough details about why your project's current resource usage cannot be reduced to adhere to the existing quota requirements.
