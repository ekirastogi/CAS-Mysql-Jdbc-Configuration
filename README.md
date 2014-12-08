CAS-Mysql-Jdbc-Configuration
============================
This is a sample configuration of the CAS server setup using MYSQL database.

To run the code follow the steps below
1. Clone the git repository to your local machine.
2. Install maven 
3. Run command -> mvn clean package;
4. The war file will be available in the folder -> target/cas.war
5. Deploy this war on a servlet container like tomcat or jboss or websphere.

That's it. Your CAS server will now look in your database for authnticatiog users.
