<div align="center">

# QuickBooks V3 Java SDK

Java SDK for QuickBooks REST API v3 services.

</div>

## 📌 Overview

QuickBooks V3 Java SDK provides Java class libraries for working with QuickBooks Online REST API v3 services. It is intended for Java applications that need to call QuickBooks Online APIs and access QuickBooks Online data through SDK-provided components.

The SDK supports common QuickBooks Online API workflows, including CRUD operations, batch processing, request and response handling, querying, reports access, sparse updates, and change data retrieval.

## ✨ Features

- Single and batch processing for CRUD operations on QuickBooks Online entities.
- Common request and response handler interface.
- Implementations for synchronous and asynchronous requests.
- XML and JSON request and response format support.
- Configuration-file based app settings.
- Gzip and Deflate compression support for service calls.
- Retry policy constructors for handling transient errors.
- Trace logging and request/response logging.
- Query filters for retrieving entities that match specified criteria.
- Queries for accessing QuickBooks reports.
- Sparse update support for updating selected writable properties.
- Change data support for retrieving entities modified during specified time ranges.

## 🧩 Components

| Component | Description |
|---|---|
| `ipp-v3-java-data` | Contains entities and entity dependencies used in data service operations. |
| `ipp-v3-java-devkit` | Core component with REST API support. |
| `ipp-java-qbapihelper` | Contains QuickBooks Online helper methods for OAuth, Disconnect, and Reconnect APIs. Deprecated with v6.0.0. |
| `oauth2-platform-api` | Contains helper methods for OAuth2 tokens, Disconnect, and Reconnect APIs for OAuth2 apps. |
| `payments-api` | Payments SDK for V2 API, including charge, eCheck, token, card, and bank account APIs. |

## ✅ System Requirements

The SDK works on JDK 1.7 and above.

## 🛠️ Basic Usage

To work with the SDK source locally:

1. Clone the repository.
2. Import the project into the IDE of your choice.
3. Use Maven to build and test the project.

To test and build artifacts locally, run Maven from the project directory:

```bash
mvn install
```

This runs unit tests, builds the project, and generates the data, devkit, OAuth helper, and OAuth2 platform artifacts described by the project.

## 📚 Documentation and Support

- Support: https://developer.intuit.com/help
- User Guide: https://developer.intuit.com/app/developer/qbo/docs/develop/sdks-and-samples-collections/java
- JavaDocs: https://developer-static.intuit.com/SDKDocs/QBV3Doc/ipp-v3-java-devkit-javadoc/index.html
- Release Notes: https://developer.intuit.com/docs/0100_quickbooks_online/0400_tools/0005_sdks/0200_java/0080_quickbooks_java_sdk_release_notes

## 🤝 Contributing

Contributions may include features, bug fixes, documentation, tutorials, or tests. Pull requests should generally be submitted against the `develop` branch.

Suggested contribution flow:

1. Fork the repository.
2. Clone your fork.
3. Develop and test your changes.
4. Add or update unit tests when applicable.
5. Open a pull request for review.

Before submitting a pull request, remove any keys or tokens added during local testing.

## 📄 License

This project is licensed under the Apache License 2.0.
