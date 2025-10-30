# Credit Enforcement Platform Config Repo

This repository contains the configuration files for the Credit Enforcement Platform microservices.

## Project Structure

The repository is structured by service and environment. Each service has its own configuration file for each environment.

For example, the `access-management-service` has the following configuration files:

- `access-management-service-dev.yml`: Configuration for the development environment
- `access-management-service-staging.yml`: Configuration for the staging environment

## Usage

The Spring Cloud Config Server is used to serve the configuration files to the microservices. The microservices are configured to connect to the Config Server and retrieve their configuration from this repository.

To use the configuration files, you need to:

1.  Start the Spring Cloud Config Server.
2.  Configure your microservices to connect to the Config Server.

## Contributing

To contribute to this project, please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your changes.
3.  Make your changes and commit them.
4.  Push your changes to your fork.
5.  Create a pull request.
