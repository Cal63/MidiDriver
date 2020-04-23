# DEVELOPMENT NOTES

Below can be found useful information for maintaining this project.

Q: How to upgrade to newer version of Gradle?  
A: Run in terminal: `./gradlew wrapper --gradle-version 5.6.4`
   Instead of `5.6.4` substitute appropriate version number.

Q: Where to find more information about `gradle-versions-plugin`?  
A: https://github.com/ben-manes/gradle-versions-plugin

Q: How to check project dependencies for updates?  
A: Run next command in terminal: `./gradlew clean dependencyUpdates`