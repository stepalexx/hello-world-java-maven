# Hello World Java Program Buid With Maven
Hello World Java Program Build With Maven
# Building the Application
To build the application, make sure you have Maven installed. Then, cd into the root directory and execute:




<code>mvn clean package</code>

That will create the hello-java-1.0.war file within the 'target' directory.
# Deploy application
Firtsly, Install tomcat with docker with password "mypass", then access tomcat to deploy hello-java-1.0.war

<code>docker run -d -p 8080:8080 -e TOMCAT_PASS="mypass" tutum/tomcat</code>

# Install mvn
export M2_HOME=/opt/apache-maven-3.3.9
export PATH=/var/jenkins_home/apache-maven-3.3.9/bin:$PATH
