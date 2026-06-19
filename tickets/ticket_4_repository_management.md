# Ticket 4: Repository Management.


## Configure access to a software repository located at:

/mnt/rhel9_repository

## Requirements:

- Configure repository access
- Install the package providing the 'dig' utility
- Verify installation

---

## Execution: 

### Repository File create and consigure:
A repository configuration file was create: /etc/yum.repos.d/exam_repo.repo
This is the configuration within the file: 

![Repository FIle](/images/ticket_4/repository_file_configuration.jpg)

### Verify no errors in the previous configuration: 
![Error Verification](/images/ticket_4/repository_file_verification.jpg)

### Consult which package install in order to get 'dig' utility. 
![Look for Package](/images/ticket_4/verify_package_name.jpg)

### Install 'dig' utility and verify. 
![Install utility](/images/ticket_4/install_and_verify.jpg)
