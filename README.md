The Google Web Toolkit Debug Panel
==================================


Building
---------

1. Build Requirements

 - JDK
 - MAVEN
 - GWT

2. Building From the Command Line

        $ cd gwt-debug-panel
        $ mvn clean install
     
3. Building From an IDE

 - Import the project as a normal maven project and run the maven install goal.

Running the Example
-------------------

There is an example included in the source repository.

1. Running From the Command Line

        $ cd gwt-debug-panel-example
        $ mvn package gwt:devmode


2. Deploying the Example As a WAR File

        $ cd gwt-debug-panel-example
        $ mvn clean package
