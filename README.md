# Solution

## Create Jenkins and Windows instance

```bash
# below commands will prompt for windows vm administrator password to be configured
$ terraform init
$ terraform apply
```

## Setup jenkins job

1. SSH into the jenkins instance with key from terraform output with ubuntu username.
2. Get admin password from /var/lib/jenkins/secrets/initialAdminPassword.
3. Access jenkins at port 80
4. Login with admin password
5. Create a new jenkins pipeline job and select pipeline from scm and provide github url as https://github.com/Sasi2228/devops-assessment.git
6. Run and test the job.
