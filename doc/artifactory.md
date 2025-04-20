# Artifactory

https://jfrog.com/download-jfrog-platform/

Download Docker compose option

https://releases.jfrog.io/artifactory/artifactory-pro/org/artifactory/pro/docker/jfrog-artifactory-pro/[RELEASE]/jfrog-artifactory-pro-[RELEASE]-compose.tar.gz?_gl=1*a3iuv9*_gcl_au*MTQ2NDM1Nzk3MS4xNzQ1MDk3NzU2*FPAU*MTQ2NDM1Nzk3MS4xNzQ1MDk3NzU2*_ga*OTI5MTM0Nzg3LjE3NDUwOTc2MjY.*_ga_SQ1NR9VTFJ*MTc0NTEwNDUwMi4zLjEuMTc0NTEwNDc1My4wLjAuMTU0Mzg5OTczNQ..*_fplc*OW4xUzBoeWdqTVRaczZST3NmWjZMYzZQeERNOFBqelpWMWJzQmdhUmRSQmRwOTRhJTJCaWZESUt6RHlYT21mJTJGSWxCMktuZTl2eExZY05NV01GMVJwSHY3MFV1NGl0R1o2OGViWk5yV1N2R2ZRJTJCYXlORXRyNWdhOGYzVksxUkVRJTNEJTNE

Unzip the file

Execute config

./config.sh

export POSTGRES_PSWRD=jfrog123


PUT /api/security/users/davids
{
user.json
}

curl -u admin:jFrog1234 -X PUT http://localhost:8082/artifactory/api/security/users/alvaro \
-H Content-Type: application/vnd.org.jfrog.artifactory.security.User+json \
--data '{
    "name": "alvaro",
    "email": "alvaro@example.com",
    "password": "P@sswOrd",
    "groups": ["readers"],
    "admin": false,
    "profileUpdatable": true,
    "internalPasswordDisabled": false
    }'






Usage
:Consumes application/vnd.org.jfrog.artifactory.security.Group+json


http://localhost:8082/ui/admin/management/users/new

alvna
jFrog123
