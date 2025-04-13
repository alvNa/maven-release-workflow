# Maven Release Plugin

Release Prepare:

Release Perform:

Release Branches:
```
mvn org.apache.maven.plugins:maven-release-plugin:3.1.1:branch -B -DautoVersionSubmodules=true \
 -DbranchName=release/0.1 -DreleaseVersion=0.1.1-SNAPSHOT -DdevelopmentVersion=0.2.0-SNAPSHOT \
 -DupdateWorkingCopyVersions=true -DupdateBranchVersions=true
```

Release Rollback:
```
mvn release:rollback
```

Release Clean:
```
mvn release:clean
```


References:
- https://maven.apache.org/maven-release/maven-release-plugin/index.html