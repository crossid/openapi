# Crossid OpenAPI Specification

![Spec Main](https://github.com/crossid/api-openapi/workflows/Spec%20Main/badge.svg) ![Status](https://img.shields.io/badge/Status-Early%20Availability-blue)

The OpenAPI specification for [Crossid's public API v1](https://developers.crossid.io/api).

## What is OpenAPI?

From the [OpenAPI Specification](https://swagger.io/specification/):

> The OpenAPI Specification (OAS) defines a standard, language-agnostic interface to RESTful APIs which allows both humans and computers to discover and understand the capabilities of the service without access to source code, documentation, or through network traffic inspection. When properly defined, a consumer can understand and interact with the remote service with a minimal amount of implementation logic.

> An OpenAPI definition can then be used by documentation generation tools to display the API, code generation tools to generate servers and clients in various programming languages, testing tools, and many other use cases.

## Project Status

The Crossid OpenAPI Specification is currently in **Early Availability**. While the specification should be accurate, it is under active development. The structure of this repository may continue to evolve. If you encounter any inaccuracies or have feedback on how it can better suite your use case, please [open an issue](https://github.com/crossid/api-openapi/issues/new) to let us know.

## Specification

This repository contains the source files used to compile the specification. On each merge to `main`, a bundled version is generated containing the entire specification.

[![Spec Download](https://img.shields.io/badge/Download-OpenAPI%20v3%20Spec-blue?style=for-the-badge&logo=crossid)](https://developer.crossid.io/spec-ci/crossid-public.v1.yaml)

#### Postman Collection

In order to generate a collection that may be imported to Postman, run:

    make collection

The results can be found in `tests/postman.json`.

## Development

To generate a bundled version of the specification locally, run:

    make bundle

To preview the documentation locally, run:

    make preview

The documentation will be available at: `http://127.0.0.1:8080`

For more details on our development process and the structure of this repository, see [CONTRIBUTING.md](/CONTRIBUTING.md).
