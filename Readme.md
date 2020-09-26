# Gradle publish demo

the `build.gradle` contains the configuration for publishing artifact to mavenLocal(normally is ./m2/repository) and specific repo(like Nexus) 

run `gradle install` to deploy the artifact to mavenLocal

run `gradle deploy` to deploy the artifact to specific repo