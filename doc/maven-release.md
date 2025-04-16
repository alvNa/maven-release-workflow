# Maven Release Plugin

Release Prepare:
```
mvn -s settings.xml org.apache.maven.plugins:maven-release-plugin:3.1.1:prepare -B -DautoVersionSubmodules=true \
-DprojectVersionPolicyId=SemVerVersionPolicy \
-Dusername=alvNa -Dpassword=
```

Release Perform:
```
mvn -s settings.xml org.apache.maven.plugins:maven-release-plugin:3.1.1:perform -DautoVersionSubmodules=true \
-DprojectVersionPolicyId=SemVerVersionPolicy \
-Dusername=alvNa -Dpassword= \
-DdryRun=true
```

Release Branches:
```
mvn org.apache.maven.plugins:maven-release-plugin:3.1.1:branch -B -DautoVersionSubmodules=true \
 -DbranchName=release/0.1 -DreleaseVersion=0.1.1-SNAPSHOT -DdevelopmentVersion=0.2.0-SNAPSHOT \
 -DupdateWorkingCopyVersions=true -DupdateBranchVersions=true
```

Release Update:
```
mvn org.apache.maven.plugins:maven-release-plugin:3.1.1:update-versions -DautoVersionSubmodules=true -DdevelopmentVersion=0.1.0-SNAPSHOT
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