# Maven Release Plugin

Maven Prepare:

Maven Perform:

Maven Branches:
```
mvn org.apache.maven.plugins:maven-release-plugin:3.1.1:branch -B  \
 -DbranchName=release/0.1 -DreleaseVersion=0.1.1-SNAPSHOT -DdevelopmentVersion=0.2.0-SNAPSHOT \
 -DautoVersionSubmodules=true  -DupdateWorkingCopyVersions=true -DupdateBranchVersions=true
```

References:
- https://maven.apache.org/maven-release/maven-release-plugin/index.html