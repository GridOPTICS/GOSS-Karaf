GOSS-Karaf
==========

Maven deployment of karaf with goss core features installed.  In order for you to use this method of deployment you must have maven 3.0.5 installed and have MAVEN_HOME/bin on the system path.

 1. Clone repository
 2. Open command line to the root of the repository
 3. execute mvn clean compile
 4. execute start-karaf (Starts the server in debug mode)
 5. type feature:install goss-core-feature   (If this is successful you should see the line GossRequestHandlerRegistrationImpl (120) | Starting handler)
 
Step 5 is where the core-features are actually installed on the system.
 

