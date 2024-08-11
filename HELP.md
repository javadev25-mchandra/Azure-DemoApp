# Read Me First
The following was discovered as part of building this project:

* The original package name 'com.td.wipro.azure.app.Azure DemoApp' is invalid and this project uses 'com.td.wipro.azure.app.Azure.DemoApp' instead.

# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/3.3.2/maven-plugin)
* [Create an OCI image](https://docs.spring.io/spring-boot/3.3.2/maven-plugin/build-image.html)
* [Spring Web](https://docs.spring.io/spring-boot/docs/3.3.2/reference/htmlsingle/index.html#web)
* [Spring Boot DevTools](https://docs.spring.io/spring-boot/docs/3.3.2/reference/htmlsingle/index.html#using.devtools)
* [Function](https://docs.spring.io/spring-cloud-function/docs/current/reference/html/spring-cloud-function.html)
* [Spring Cloud Azure developer guide](https://aka.ms/spring/msdocs/developer-guide)
* [Azure Key Vault](https://microsoft.github.io/spring-cloud-azure/current/reference/html/index.html#secret-management)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)
* [Deploying a Spring Boot app to Azure](https://spring.io/guides/gs/spring-boot-for-azure/)
* [Read Secrets from Azure Key Vault in a Spring Boot Application](https://aka.ms/spring/msdocs/keyvault)
* [Securing Spring Boot Applications with Azure Key Vault Certificates](https://aka.ms/spring/msdocs/keyvault/certificates)

### Additional Links
These additional references should also help you:

* [Various sample apps using Spring Cloud Function](https://github.com/spring-cloud/spring-cloud-function/tree/main/spring-cloud-function-samples)
* [Azure Samples](https://aka.ms/spring/samples)
* [Azure Key Vault Sample](https://aka.ms/spring/samples/latest/keyvault)

### Maven Parent overrides

Due to Maven's design, elements are inherited from the parent POM to the project POM.
While most of the inheritance is fine, it also inherits unwanted elements like `<license>` and `<developers>` from the parent.
To prevent this, the project POM contains empty overrides for these elements.
If you manually switch to a different parent and actually want the inheritance, you need to remove those overrides.

