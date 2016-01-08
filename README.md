# Flyway
## A simple project for data migration using the maven plugin
Run this command from the project's root
<pre>
mvn compile flyway:migrate -Dflyway.configFile=flyway-config.properties
</pre>
It will create a table an populate with 4 rows, the db configuration is in the flyway-config.properties file

