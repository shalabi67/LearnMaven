#This project shows how to use profiles.
profiles are define in plus plus project

##find active profile
mvn help:active-profiles

##run specific prom command line
mvn clean install -P output

##we can select profile based on condition
###OS
###Environment variable
###maven property
###set a default active profile in maven
###JDK
###file existence
