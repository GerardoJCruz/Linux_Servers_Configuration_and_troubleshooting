# Ticket 2: File Permissions management.

## A development team requires a shared workspace at:

/srv/development

##  Requirements:

- Members of group developers must be able to create and modify files
- Files created within the directory must automatically belong to the correct group
- Other users must not have access
- Create a symbolic link named /development pointing to the shared location

---

## Execution:
A user named alex was created to be add to the group developers and test the configuration. 

### Group 'developers' created 
![Group Developers](/images/ticket_2/ticket_2_group_created.jpg)

### Shared Directory created
![Shared Directory](/images/ticket_2/directory_createdjpg)

### Set the permissions and SetGID to the directory:
![Set Permissions](/images/ticket_2/directory_permissions.jpg)

### Test configuration using the user 'alex' who is part of the group developers.
![Test Permissions](/images/ticket_2/verify_alex_can_create_and_edit_files.jpg)

### Create Symbolic Link
![Simbolic Link](/images/ticket_2/softlink_creation_and_testing.jpg)

