# configserver

Config server is an externalized application configuration service, which gives you a central place to manage an application's external properties across all environments

**To Implement Config Server we need below steps:**

* Need to add Spring-cloud-config-server dependency
* In main class we have to add @EnableConfigServer annotation
* In bootstrap Properties file we have to add GIT path in spring cloud config server git Uri
* Property file which is going to consumed by other MS need to keep inside project

