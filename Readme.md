Install the archetype:

mvn clean install

Use the archetype:

mvn archetype:generate -DarchetypeGroupId=com.mycompany.app -DarchetypeArtifactId=my-app-archetype \
-DarchetypeVersion=1.0-SNAPSHOT -DgroupId=customGroup -DartifactId=customproject -DinteractiveMode=false