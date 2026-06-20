# Ticket 5: Provide Storage with LVM.

## Provide persistent storage at:

/research

## Requirements:

- Use available space from one unused disk
- Storage must be managed through LVM
- Use the XFS filesystem
- Storage must survive reboot

---

## Execution: 

## LVM Structure

### Evaluate the disk to use. 
For this case the disk /dev/vdb was the one selected to be used. 
![Disk Selection](/images/ticket_5/determinate_disk_to_use.jpg)

### Create the gpt partition for /dev/vdb
![Disk Partition](/images/ticket_5/create_a_gpt_partition_to_dsik.jpg)

### Create the Phisical Volume for /dev/vdb
![Phisical Volume](/images/ticket_5/phisical_volume_created.jpg)

### Create Volume Group:
![Volue Group](/images/ticket_5/volume_group_created.jpg)

### Create the Logical Volume:
![Logical Volume](/images/ticket_5/logical_volume_created.jpg)

### Set the file system: xfs
![File System](/images/ticket_5/filesystem_created_and_verify.jpg)

### LVM Structure and filesystem verified:
![Verification 1](/images/ticket_5/lvm_verification1.jpg)
![Verification 1](/images/ticket_5/lvm_verification2.jpg)

## Mount the storage permanently:

### Create the directory to mount the new storage: /research.
![Directory mounting point](/images/ticket_5/directory_created.jpg)

### Configure the fstab file to make the system to mount the new storage during booting. 
![fstab FIle](/images/ticket_5/fstab_file_configuration.jpg)

### New mounting point mounted and verified:
![MOunted](/images/ticket_5/storage_mounted_and_verify.jpg)
