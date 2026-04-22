# OpenTelemetry Telescope Shop — Honeycomb Academy Fork

This is a fork of the [OpenTelemetry Demo](https://github.com/open-telemetry/opentelemetry-demo) used as the sample application for **[Honeycomb Academy](https://academy.honeycomb.io/app) courses** delivered via [Instruqt](https://instruqt.com) labs.

## About This Fork

Each Instruqt lab runs in a virtual machine with a custom image that automatically starts the application when the lab opens — learners do not need to clone or run the app themselves.

The application has been modified from the upstream demo as follows:

- **Honeycomb is pre-configured as the observability backend** — the OTel Collector exports traces directly to Honeycomb; learners supply their own Honeycomb API key
- **Service set is reduced** to lower memory requirements for the lab environment (accounting, fraud detection, grafana, jaeger, opensearch, prometheus, llm, and product catalog AI/review features are not included)
- **`paymentFailure` feature flag is set to 50%** — the payment service randomly fails half of all charge requests by design, giving learners real failures to investigate

---

## Original Project

This fork is based on the **OpenTelemetry Astronomy Shop Demo**, maintained by the OpenTelemetry community. All original credits below apply.

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg?color=red)](https://github.com/open-telemetry/opentelemetry-demo/blob/main/LICENSE)

The OpenTelemetry Astronomy Shop is a microservice-based distributed system intended to illustrate the implementation of OpenTelemetry in a near real-world environment.

- [Upstream repository](https://github.com/open-telemetry/opentelemetry-demo)
- [Demo documentation](https://opentelemetry.io/docs/demo/)
- [Fork guidance](https://opentelemetry.io/docs/demo/forking/)

## Demos Featuring the Astronomy Shop

| | | |
|---------------------------|----------------|----------------------------------|
| [AlibabaCloud LogService] | [Grafana Labs] | [Sentry]                         |
| [Apache Doris]            | [Guance]       | [ServiceNow Cloud Observability] |
| [AppDynamics]             | [Honeycomb.io] | [SigNoz]                         |
| [Aspecto]                 | [Instana]      | [SolarWinds Observability]       |
| [Axiom]                   | [Kloudfuse]    | [Splunk]                         |
| [Axoflow]                 | [Kopai]        | [Sumo Logic]                     |
| [Azure Data Explorer]     | [Last9]        | [TelemetryHub]                   |
| [Causely]                 | [Liatrio]      | [Teletrace]                      |
| [ClickStack]              | [Logz.io]      | [Tinybird]                       |
| [Coralogix]               | [New Relic]    | [Tracetest]                      |
| [Dash0]                   | [Oodle]        | [Tsuga]                          |
| [Datadog]                 | [OpenObserve]  | [Uptrace]                        |
| [Dynatrace]               | [OpenSearch]   | [VictoriaMetrics]                |
| [Elastic]                 | [Oracle]       |                                  |
| [Google Cloud]            | [Parseable]    |                                  |

## Maintainers

- [Cyrille Le Clerc](https://github.com/cyrille-leclerc), Grafana Labs
- [Juliano Costa](https://github.com/julianocosta89), Datadog
- [Pierre Tessier](https://github.com/puckpuck), Honeycomb
- [Roger Coll](https://github.com/rogercoll), Elastic

For more information about the maintainer role, see the [community repository](https://github.com/open-telemetry/community/blob/main/guides/contributor/membership.md#maintainer).

## Approvers

- [Cedric Ziel](https://github.com/cedricziel), Grafana Labs
- [Mikko Viitanen](https://github.com/mviitane), Dynatrace
- [Shenoy Pratik](https://github.com/ps48), AWS OpenSearch

For more information about the approver role, see the [community repository](https://github.com/open-telemetry/community/blob/main/guides/contributor/membership.md#approver).

## Emeritus

- [Austin Parker](https://github.com/austinlparker)
- [Carter Socha](https://github.com/cartersocha)
- [Michael Maxwell](https://github.com/mic-max)
- [Morgan McLean](https://github.com/mtwo)
- [Penghan Wang](https://github.com/wph95)
- [Reiley Yang](https://github.com/reyang)
- [Ziqi Zhao](https://github.com/fatsheep9146)

For more information about the emeritus role, see the [community repository](https://github.com/open-telemetry/community/blob/main/guides/contributor/membership.md#emeritus-maintainerapprovertriager).

## Thanks to All Contributors

[![contributors](https://contributors-img.web.app/image?repo=open-telemetry/opentelemetry-demo)](https://github.com/open-telemetry/opentelemetry-demo/graphs/contributors)

<!-- Links for Demos featuring the Astronomy Shop section -->

[AlibabaCloud LogService]: https://github.com/aliyun-sls/opentelemetry-demo
[AppDynamics]: https://community.splunk.com/t5/AppDynamics-Knowledge-Base/How-to-observe-Kubernetes-deployment-of-OpenTelemetry-demo-app/ta-p/741454
[Apache Doris]: https://github.com/apache/doris-opentelemetry-demo
[Aspecto]: https://github.com/aspecto-io/opentelemetry-demo
[Axiom]: https://play.axiom.co/axiom-play-qf1k/dashboards/otel.traces.otel-demo-traces
[Axoflow]: https://axoflow.com/opentelemetry-support-in-more-detail-in-axosyslog-and-syslog-ng/
[Azure Data Explorer]: https://github.com/Azure/Azure-kusto-opentelemetry-demo
[Causely]: https://github.com/causely-oss/otel-demo
[ClickStack]: https://github.com/ClickHouse/opentelemetry-demo
[Coralogix]: https://coralogix.com/blog/configure-otel-demo-send-telemetry-data-coralogix
[Dash0]: https://github.com/dash0hq/opentelemetry-demo
[Datadog]: https://docs.datadoghq.com/opentelemetry/guide/otel_demo_to_datadog
[Dynatrace]: https://www.dynatrace.com/news/blog/opentelemetry-demo-application-with-dynatrace/
[Elastic]: https://github.com/elastic/opentelemetry-demo
[Google Cloud]: https://github.com/GoogleCloudPlatform/opentelemetry-demo
[Grafana Labs]: https://github.com/grafana/opentelemetry-demo
[Guance]: https://github.com/GuanceCloud/opentelemetry-demo
[Honeycomb.io]: https://github.com/honeycombio/opentelemetry-demo
[Instana]: https://github.com/instana/opentelemetry-demo
[Kloudfuse]: https://github.com/kloudfuse/opentelemetry-demo
[Kopai]: https://github.com/kopai-app/opentelemetry-demo/tree/main/kopai
[Last9]: https://last9.io/docs/integrations-opentelemetry-demo/
[Liatrio]: https://github.com/liatrio/opentelemetry-demo
[Logz.io]: https://logz.io/learn/how-to-run-opentelemetry-demo-with-logz-io/
[New Relic]: https://github.com/newrelic/opentelemetry-demo
[Oodle]: https://blog.oodle.ai/meet-oodle-unified-and-ai-native-observability/
[OpenSearch]: https://github.com/opensearch-project/opentelemetry-demo
[OpenObserve]: https://openobserve.ai/blog/opentelemetry-astronomy-shop-demo/
[Oracle]: https://github.com/oracle-quickstart/oci-o11y-solutions/blob/main/knowledge-content/opentelemetry-demo
[Parseable]: https://www.parseable.com/blog/open-telemetry-demo-with-parseable-a-complete-observability-setup
[Sentry]: https://github.com/getsentry/opentelemetry-demo
[ServiceNow Cloud Observability]: https://docs.lightstep.com/otel/quick-start-operator#send-data-from-the-opentelemetry-demo
[SigNoz]: https://signoz.io/blog/opentelemetry-demo/
[SolarWinds Observability]: https://github.com/solarwinds/opentelemetry-demo
[Splunk]: https://github.com/signalfx/opentelemetry-demo
[Sumo Logic]: https://www.sumologic.com/blog/common-opentelemetry-demo-application/
[TelemetryHub]: https://github.com/TelemetryHub/opentelemetry-demo/tree/telemetryhub-backend
[Teletrace]: https://github.com/teletrace/opentelemetry-demo
[Tinybird]: https://github.com/tinybirdco/opentelemetry-demo
[Tracetest]: https://github.com/kubeshop/opentelemetry-demo
[Tsuga]: https://github.com/tsuga-dev/opentelemetry-demo
[Uptrace]: https://github.com/uptrace/uptrace/tree/master/example/opentelemetry-demo
[VictoriaMetrics]: https://github.com/VictoriaMetrics-Community/opentelemetry-demo
