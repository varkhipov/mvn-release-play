# mvn-release-play

http://maven.apache.org/maven-release/maven-release-plugin/examples/non-interactive-release.html

```
mvn release:prepare \
    <!---Dtag=timestamp_relVer \-->
    -DreleaseVersion=relVer \
    -DdevelopmentVersion=nextVer-SNAPSHOT
```
