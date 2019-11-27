Build a webapp archetype with Maven with Tomcat7 embedded
https://www.theserverside.com/tutorial/How-to-embed-Tomcat-and-Java-web-apps-in-an-executable-JAR

Include java.servlet dependency
https://stackoverflow.com/questions/16262948/error-package-javax-servlet-does-not-exist

Remember: set the path on Tomcat7 plugin (pom.xml file)

Find CATALINA_HOME
https://stackoverflow.com/questions/24623731/where-is-catalina-base-webapps-folder-for-tomcat-8-on-mac

TO DO
Come impostare in modo automatico utenza e password del tomcat server?
Ansible? Gestione secret con AWS?


Maven tutorial
http://tutorials.jenkov.com/maven/maven-tutorial.html


How to find setting.xml file of maven
https://stackoverflow.com/questions/9988814/how-do-i-find-out-which-settings-xml-file-maven-is-using

How to find tomcat.xml file to set users


DEPLOY ON TOMCAT with Maven

Maven settings
  settings.xml (esistono due settings file, quello user specific ha la precedenza nel merge) aggiungere il server tomcat e le credenziali

Tomcat settings
  tomcat-users.xml (set-up dei ruoli manager-gui e manager-script)

Maven POM
  usare plugin tomcat per deploy (concordanza con id server fra settings e POM)


INSTALLARE TOMCAT su ubuntu
https://www.linode.com/docs/development/frameworks/apache-tomcat-on-ubuntu-16-04/

TO DO:
usare ansible per modificare il configuration file tomcat-users.xml
usare ansible per far partire maven? jenkins?
