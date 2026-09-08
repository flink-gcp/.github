# GCP Connectors for Apache Flink

We develop independent open-source connectors for using Google Cloud services with Apache Flink.
Our main project, [flink-connector-gcp](https://github.com/flink-gcp/flink-connector-gcp), connects Flink jobs to BigQuery, Cloud Pub/Sub, Cloud Tasks, Bigtable, and Spanner through DataStream and Table/SQL APIs.

## Get started

- [Documentation](https://flink-gcp.github.io/flink-connector-gcp/) describes the connectors and supported versions.
- [Quickstart](https://flink-gcp.github.io/flink-connector-gcp/docs/quickstart/) covers installation, credentials, and example jobs.
- [Releases](https://github.com/flink-gcp/flink-connector-gcp/releases) provide release notes and SQL connector JARs.
- [Maven Central](https://central.sonatype.com/namespace/io.github.flink-gcp) hosts the published connector artifacts under `io.github.flink-gcp`.

## Blog series

This series introduces the project and its five connectors as they were released in 1.0.0.
For current setup instructions and supported behavior, use the documentation linked above.

- [Release introduction](https://laughingman7743.hatenablog.com/entry/2026/08/31/190604)
- [BigQuery](https://laughingman7743.hatenablog.com/entry/2026/09/02/001129)
- [Pub/Sub](https://laughingman7743.hatenablog.com/entry/2026/09/03/001309)
- [Spanner](https://laughingman7743.hatenablog.com/entry/2026/09/04/001631)
- [Bigtable](https://laughingman7743.hatenablog.com/entry/2026/09/05/163307)
- [Cloud Tasks](https://laughingman7743.hatenablog.com/entry/2026/09/06/123117)

## Related projects

| Project | Purpose |
| --- | --- |
| [flink-datastream-protobuf](https://github.com/flink-gcp/flink-datastream-protobuf) | Native Protocol Buffers type integration for the Flink DataStream API. Under development; no release is available yet. |
| [flink-gcp-dev-tools](https://github.com/flink-gcp/flink-gcp-dev-tools) | Shared development workflows, a pull request template, and documentation design assets for flink-gcp projects. |

## About the project

This is an independent open-source project.
It is not affiliated with, endorsed by, or supported by the Apache Software Foundation or Google.
Apache Flink, Flink, and the Flink logo are trademarks of the Apache Software Foundation.
