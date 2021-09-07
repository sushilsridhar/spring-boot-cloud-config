
**Boostrap.yml**  
Bootstrap.yml is loaded before application.yml. A Spring Cloud application operates by creating a "bootstrap" context, which is a parent context for the main application. Out of the box it is responsible for loading configuration properties from the external sources, and also decrypting properties in the local external configuration files.