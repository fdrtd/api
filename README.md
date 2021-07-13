# fdrtd

`fdrtd` is a free and open source implementation of `federated secure computing`,
a modern microservice architecture for privacy-preserving computation:

- [x] multi-protocol technology platform (e.g. secure multipary computation)
- [x] cryptography is offloaded to the server/cloud (separation of concerns)
- [x] client-side business logic is easy to implement (no barriers to entry)
- [x] toolbox of specific microservices (no complex monolithic universality)
- [x] runs in virtually any environment (compatibility and interoperability)
- [x] OpenAPI 3.0 standard for 3rd party developers (plug & play extensions)

## resources

* non-technical information: [www.fdrtd.com](https://www.fdrtd.com)
* technical documentation: [www.fdrtd.com/docs](https://www.fdrtd.com/docs)
* support by email: [support@fdrtd.com](mailto:support@fdrtd.com)

## this repository

this repository holds the OpenAPI 3.0 definition

![license](https://img.shields.io/github/license/fdrtd/api)

![language](https://img.shields.io/github/languages/top/fdrtd/api)

![swagger-validator](https://img.shields.io/swagger/valid/3.0?specUrl=https%3A%2F%2Fraw.githubusercontent.com%2Ffdrtd%2Fapi%2Fmain%2Fopenapi.yaml)

### usage

e.g. to generate a Flask server stub

`java -jar openapi-generator-cli.jar generate -g python-flask -i openapi.yaml -o openapi_server`
