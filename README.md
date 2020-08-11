# sparkjava-war-example
Build war with maven and sparkjava framework

Steps:

1. Download a fresh [Tomcat 8 distribution](https://tomcat.apache.org/download-80.cgi)
2. Clone this repository to your local machine
2.  Define version package command: mvn versions:set -DnewVersion=1.0-SNAPSHOT
3. Run mvn package
5. Copy the generated `sparkjava-hello-world-1.0.war` to the Tomcat `webapps` folder
6. Start Tomcat by running `bin\startup.bat` (or `bin\startaup.sh` for Linux)
7. Tomcat will automatically deploy the war
8. Open [http://localhost:8080/sparkjava-hello-world-1.0/hello](http://localhost:8080/sparkjava-hello-world-1.0/hello) in your browser

