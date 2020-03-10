---
name: Request to Change Project Set Quotas
about: Request changes to cpu/storage/etc
title: ''
labels: quota-update, pending
assignees: caggles, ShellyXueHan

---

## Step 0
**Are you the product owner or technical lead?**
If not, you will need to ask one of those two people to make this request.


## Step 1
Make sure no duplicated request exists, search here:
https://github.com/BCDevOps/devops-requests/issues


## Step 2
What quotas need to be changed? (Select all that apply)
- [ ] CPU: Best Effort (compute-best-effort-quota)
- [ ] CPU: Long Running (compute-long-running-quota)
- [ ] CPU: Time Bound (compute-time-bound-quota)
- [ ] Storage: Netapp Block (storage-netapp-block-standard-quota)
- [ ] Storage: Netapp File (storage-netapp-file-standard-quota)
- [ ] Storage: NFS Backup (storage-nfs-backup-quota)

Note: if you are looking for any other quotas to be changed (namely, gluster), you may explain here what type of change you require.
Please be aware that there is a VERY low chance that any such requests will be approved.

## Step 4
Please explain here the reasons for requesting your quota change.
Remember that OCP is a shared resource. Please be community-minded in making these requests and include thorough details about why your project's current resource usage cannot be reduced to adhere to the existing quota requirements.
