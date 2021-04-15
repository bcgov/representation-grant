# Representation Grant
Representation Grant

[![img](https://img.shields.io/badge/Lifecycle-Dormant-ff7f2a)](https://github.com/bcgov/repomountie/blob/master/doc/lifecycle-badges.md)

## Structure

### Client Application (web)
An AngularJS client application which serves out the SurveyJS based questionnaire.

###	REST API (api)
A Django based REST API which provides the heavy lifting.  The API includes a Swagger interface containing API documentation and UI that allows you to interact with the various APIs manually.

### PDF Microservice (pdf)
An html to PDF microservice used to generate reports.

###	Database (db)
A PostgreSQL database for storage, complete with a SchemaSpy instance for documentation.

## Development Instances

To be updated.

## Running on OpenShift

To deploy using a local instance of OpenShift, refer to [Running on OpenShift](./RunningOnOpenShift.md).  These instructions, apart from the steps that are specific to setting up your local environment, can be used to get the project deployed to a production OpenShift environment.

## Running on Docker

The project can also be run locally using Docker and Docker Compose.  Refer to [Running with Docker Compose](./docker/README.md) for instructions.


## Code of Conduct

Please refer to the [Code of Conduct](./CODE_OF_CONDUCT.md) 

## Contributing

For information on how to contribute, refer to [Contributing](CONTRIBUTING.md)

## License

Code released under the [Apache License, Version 2.0](./LICENSE).
