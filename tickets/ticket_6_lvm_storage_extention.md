# Ticket 6: LVM Storage Extention.

## Additional storage capacity has been approved.

## Requirements:

- Expand the storage available at /research
- No data loss may occur
- Verify the filesystem can use the new capacity

--- 

## Execution: 

### Evaluate which disk to use: 
In this case, the disk selected is /dev/vdc
![Disk Selected](/images/ticket_6/determinate_new_disk_to_add.jpg)

### GPT partition created: 
![Partition the Disk](/images/ticket_6/new_disk_gpt_partition.jpg)

### Phisical Volume Creation: 
![Phisical Volume](/images/ticket_6/new_phisical_volume.jpg)

### Volume Group Extended:
![Volume Group](/images/ticket_6/volume_group_extended.jpg)

### Logical Volume Extended and filesystem resized:
![Logical Volume](/images/ticket_6/logical_volume_extended_and_verify.jpg)
