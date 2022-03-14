---
name: Request to restore a backup Persistent Volume (PV) from OpenShift
about: To have a netapp-file-backup type of Persistent Volume (PV) restored
title: ''
labels: 
  - restore-backup-volume
assignees: StevenBarre, wmhutchison, tbaker1313, tmorik
---

## Restore a backup Persistent Volume (PV)
Please read through the documentation about [OCP4 Backup and Restore](https://developer.gov.bc.ca/OCP4-Backup-and-Restore) before proceeding with this request!

> Note that only the `netapp-file-backup` type of Persistent Volume can be restored from OpenShift.

### Step 1
Fill out the following fields

* Date: the date you need restored from
* Cluster: Silver/Gold/GoldDR
* Source PV: the source PV you need restored
* Destination PV: the destination path

> Note that the Source and destination can be the same PVC or separate. You can specify sub-folders instead of the whole volume.
