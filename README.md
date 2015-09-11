# Camel Deployment Kar
This is a helper project for [Camel Deployment](https://github.com/jnupponen/camel-deployment) tutorial.

The purpose of this project is to group dependencies needed in Camel Deployment project when the example code is deployed to Apache Karaf.

## To build this project
```
git clone git@github.com:jnupponen/camel-deployment-kar.git
mvn clean install
```
After that you get .kar-file in target/ folder. That file can be deployed to Karaf's deploy folder and the features listed in [feature.xml](src/main/feature/feature.xml) file will be installed in Karaf.
