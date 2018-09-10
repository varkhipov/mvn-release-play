# mvn-release-play

http://maven.apache.org/maven-release/maven-release-plugin/examples/non-interactive-release.html

```
mvn release:clean && \
mvn --batch-mode release:prepare \
    -DreleaseVersion=relVer \
    -DdevelopmentVersion=nextVer-SNAPSHOT
mvn release:perform
```
