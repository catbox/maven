The exec plugin has been added to the pom so that the exec:java command can be executed to run the project using maven.

This is the equivalent of running the project as a java application.

<plugin>
  	<groupId>org.codehaus.mojo</groupId>
    <artifactId>exec-maven-plugin</artifactId>
    <version>1.3.1</version>
    <configuration>
      <mainClass>com.hello.HelloWorld</mainClass>
    </configuration>
 </plugin>