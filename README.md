# java-maven-archetype
A maven archetype that can be used to create spring web application. When someone generate a project using this archetype he will get
a Java Spring application with an app.properties file to configure the application properties and a Unit test class.

To install the archetype locally clone the code and do
>mvn install

To genrate a web application project do
>mvn archetype:generate -DarchetypeGroupId=com.asciimango.app  -DarchetypeArtifactId=hello-app-archetype -DarchetypeVersion=1.0.0-SNAPSHOT -DgroupId=com.test.app  -DartifactId=testapp
