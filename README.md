# Conventional Commits for Java

Provides a Java implementation of [Conventional Commits] for projects built
with Java 1.8+ using Git for version control.

## Maven Plugin

### Usage

This plugin works together with the [Maven Release Plugin] to create 
conventional commit compliant releases for your Maven projects

#### Install the Plugin
 
In your main `pom.xml` file add the plugin:

    <plugins>
        <plugin>
            <groupId>com.smartling.ci</groupId>
            <artifactId>semantic-maven-plugin</artifactId>
            <version>0.0.1-SNAPSHOT</version>
        </plugin>
    </plugins>

#### Release a Version

    mvn semantic:version release:prepare
    mvn release:perform

## Gradle Plugin

A [Gradle] plugin is planned for future release.











[Conventional Commits]: https://www.conventionalcommits.org/en/v1.0.0/
[Maven Release Plugin]: https://maven.apache.org/maven-release/maven-release-plugin/
