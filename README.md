This project contains 4 simple bash scripts to make my life easier while developing
ee projects using maven and glassfish.

ginstall: Sets up project dir and war name. It runs mvn package and asadmin deploy on the created war file.
gupdate: runs mvn package and redeploys the war file.
gclean: just does a mvn clean
gremove: mvn clean and undeploys the war from glassfish

run ginstall without parameters for a few more details.

