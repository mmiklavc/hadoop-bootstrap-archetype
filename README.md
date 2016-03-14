Welcome to the project

This archetype provides a template for new Hadoop projects

It includes:

1. Hadoop repo
1. Unit testing deps
1. .gitignore that accounts for Maven, Eclipse, and IntelliJ IDEA
1. Adds source and javadoc jars when your project is installed/deployed via Maven
1. Release plugin configuration and instructions in the materialized project's README.md

Usage:

Clone the project
```bash
git clone https://github.com/mmiklavc/hadoop-bootstrap-archetype
```

Install the archetype
```bash
cd <archetype-home-dir>
mvn clean install
```

Use the archetype (in CLI or IDE)
```bash
cd <some directory where you want the archetype to generate a new child folder for your project>
mvn archetype:generate -DarchetypeGroupId=com.michaelmiklavcic -DarchetypeArtifactId=hadoop-bootstrap-archetype -DarchetypeVersion=1.0-SNAPSHOT
```

Then just follow the prompts provided by Maven and you should have a new project skeleton complete with README file.

