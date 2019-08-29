# Mobile Money API.

## Overview

The goal of the Mobile Money API is to enable all parties to implement mobile money API&#39;s in a flexible, yet consistent manner. This has been achieved by implementing the following principles:

- Use of REST architectural principles.
- Providing a set of well-defined objects that are abstracted from the underlying object representations held in the various mobile money systems. This allows an API client to construct an API message without requiring specific knowledge of the target server implementation.
- Creation of a standard set of transaction types and other key enumerations, removing the need for developers to map for each and every API implementation.
- Use of ISO international standards for enumerators such as currency and country codes
- Use of supplementary metadata and sub-types to enable use case and/or mobile money provider-specific properties to be conveyed where necessary.
- Recognising that no common mobile money account identifier exists, use of a flexible construct to enable the target account(s) and transaction parties to be identified using one or multiple identifier types.

## Getting Started

The Mobile Money API is defined using Swagger 2.0 (now renamed as the Open API Specification). The goal of Swagger is to provide a standard, language-agnostic interface to REST APIs which allows both humans and computers to discover and understand the capabilities of the service without access to source code, documentation, or through network traffic inspection.

The [https://swagger.io/](https://swagger.io/) site contains all the information you need to view the Mobile Money API definition as well as providing code generation capabilities to support you when implementing the API. Note that we currency use the Swagger 2.0 and not 3.0 although we do plan to upgrade soon…

To help you understand the how the API can support your business, refer to . Here we provide detailed documentation on the API as well as providing a set of Postman collections to demonstrate typical implementation use cases.

## Support

Coming soon….

## Release Versions

(We are now using [Semantic Versioning](https://semver.org/)).

| **Mobile Money API Version** | **Release Date** | **Swagger (AKA Open API Spec) Compatibility** | **Notes** | **Status** |
| --- | --- | --- | --- | --- |
| 1.0.0 | 2016-10-24 | 2.x | Insert tag | Current Version |
| 1.1.0 | TBD | 2.x | Insert tag | Beta Version |
| 1.2.0 | TBD | 2.x | Insert tag | Beta Version |