# Artifactory

There are 2 main distributions OSS and PRO. The professional requires a license. 
Hence, we will use OSS for learning purposes.

https://jfrog.com/download-jfrog-platform/


## Create a new user

http://localhost:8082/ui/admin/management/users/new

Example:

alvna
jFrog123

## Generate a Maven Settings
Go to set me up option and generate a Maven settings with a Encrypted password.

After upload the libraries check it:

http://localhost:8082/ui/repos/tree/General/libs-release-local/org/alvna/module-1/0.1.0/module-1-0.1.0.pom