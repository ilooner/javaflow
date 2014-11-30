javaflow
========

This is a fork of apache javaflow http://commons.apache.org/sandbox/commons-javaflow/

Javaflow provides an implementation of continuations which works with java 6, 7 and probably 8 (I haven't tried it). To use javaflow add the following to your pom. Instructions on how to instrument at compile time will be added soon.

  <groupId>org.apache.commons</groupId>
  <artifactId>topeka-javaflow</artifactId>
  <version>2.0</version>

  <distributionManagement>
      <repository>
          <id>ip-172-31-32-140</id>
          <name>ip-172-31-32-140-releases</name>
          <url>https://www.timwiki.com:8443/artifactory/libs-release-local</url>
      </repository>
      <snapshotRepository>
          <id>ip-172-31-32-140</id>
          <name>ip-172-31-32-140-snapshots</name>
          <url>https://www.timwiki.com:8443/artifactory/libs-snapshot-local</url>
      </snapshotRepository>
  </distributionManagement>
