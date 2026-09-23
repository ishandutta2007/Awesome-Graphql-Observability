# Awesome-Graphql-Observability

## Top GraphQL Observability Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on GraphQL Metrics, Tracing, Schema Usage Analytics, Performance & Federation Observability*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **GraphQL Observability**. These systems collect operation-level metrics, traces, error rates, schema usage, and client insights so teams can understand and optimize GraphQL APIs and federated supergraphs.



**Examples** include GraphQL Hive, Apollo GraphOS / Studio, Stellate, New Relic GraphQL Monitoring, Datadog APM, Hasura Cloud Metrics, Grafbase, GraphCDN Analytics, and Inigo (the category leaders).



**Open-source emphasis**: GraphQL observability has a strong open core in **GraphQL Hive** (schema registry + usage analytics + gateway) plus OpenTelemetry instrumentation for major GraphQL servers. This section is heavily expanded around Hive and open tracing.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[GraphQL Hive Cloud](https://the-guild.dev/graphql/hive)**  

  Managed offering of the open-source Hive platform—schema registry, operation analytics, usage reporting, and federation observability.



- **[Apollo GraphOS / Studio](https://www.apollographql.com/graphos)**  

  Apollo’s platform for supergraph management with schema registry, operation metrics, client awareness, and performance insights.



- **[Stellate](https://stellate.co/)**  

  Edge GraphQL platform with deep request-level metrics, error tracking, caching analytics, and performance observability.



- **[New Relic (GraphQL / APM)](https://newrelic.com/)**  

  Full-stack observability platform with GraphQL-aware tracing and metrics when instrumented via agents or OpenTelemetry.



- **[Datadog APM](https://www.datadoghq.com/)**  

  APM and observability platform supporting GraphQL tracing and metrics through standard instrumentation and integrations.



- **[Hasura Cloud Metrics](https://hasura.io/)**  

  Built-in metrics and observability for Hasura GraphQL Engine in the managed cloud offering.



- **[Grafbase](https://grafbase.com/)**  

  GraphQL platform with observability and analytics features for edge and federated GraphQL workloads.



- **[Inigo](https://inigo.io/)**  

  GraphQL-specific security and observability platform providing schema insights, performance, and runtime visibility.



- **[GraphCDN / Stellate Analytics heritage](https://stellate.co/)**  

  Analytics capabilities originating from GraphCDN, now part of Stellate’s GraphQL metrics suite.



- **[Other APM / API observability tools with GraphQL support](https://www.example.com/)**  

  Additional commercial observability platforms that instrument GraphQL via OpenTelemetry or native agents.



## Open-Source GitHub Projects

- **[GraphQL Hive](https://github.com/graphql-hive)**  

  Fully open-source (MIT) schema registry, usage analytics, and GraphQL federation platform—self-host for operation metrics, schema checks, and observability.



- **[Hive Gateway OpenTelemetry integration](https://the-guild.dev/graphql/hive)**  

  Built-in OpenTelemetry support in Hive Gateway for traces and metrics across the GraphQL lifecycle and upstream calls.



- **[OpenTelemetry GraphQL instrumentation](https://github.com/)**  

  Official and community OpenTelemetry instrumentations for Apollo Server, GraphQL Yoga, Strawberry, and other GraphQL runtimes.



- **[Apollo Server / Client reporting plugins (open components)](https://github.com/apollographql)**  

  Open instrumentation and reporting libraries used to send traces and usage data to Apollo GraphOS or custom backends.



- **[GraphQL Yoga / Envelop observability plugins](https://github.com/graphql-hive/graphql-yoga)**  

  Open plugins for metrics, tracing, and logging in the Yoga/Envelop ecosystem.



- **[Prometheus and Grafana GraphQL exporters](https://github.com/)**  

  Open exporters and dashboards that expose GraphQL operation metrics in Prometheus format.



- **[Client-side GraphQL analytics open collectors](https://github.com/)**  

  Libraries that report operation names, timing, and errors from browsers or mobile clients to open backends.



- **[Schema usage and field-level analytics open tools](https://github.com/)**  

  Community projects that analyze which fields and types are actually used from traffic or persisted operations.



- **[Distributed tracing open backends (Jaeger, Tempo, etc.)](https://github.com/)**  

  Open tracing systems commonly used to store and visualize GraphQL spans collected via OpenTelemetry.



- **[Custom metrics pipelines with OpenTelemetry Collector](https://github.com/open-telemetry)**  

  Vendor-neutral pipelines for collecting, processing, and exporting GraphQL metrics and traces.



### Additional Strong Open-Source Options

- Self-hosting **GraphQL Hive** for schema registry + operation analytics without vendor lock-in.

- Instrumenting servers with **OpenTelemetry** and sending data to Jaeger, Grafana Tempo, Prometheus, or a commercial backend.

- Combining Hive usage reporting with open tracing for full request-path visibility.

- Accepting that polished federated supergraph analytics, global edge metrics, and turnkey alerting still favor commercial platforms (Apollo GraphOS, Stellate, Hive Cloud, Datadog, New Relic, Inigo, etc.).

- Focusing open-source efforts on standards (OpenTelemetry), data ownership, and self-hosted control planes.



**Frameworks for building custom systems**: Instrument GraphQL servers and gateways with OpenTelemetry → collect traces/metrics in an open backend (or Hive) → use Hive or custom analytics for operation and schema usage → alert via open or commercial tools. Suitable for platform teams that want full ownership of observability data. Many production graphs use Hive or Apollo for schema + usage and OpenTelemetry for distributed tracing.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Observability systems process API traffic and may contain sensitive operation data. Proper access control and retention policies are required. This list is not security or operational advice.



---

**Made for GraphQL platform engineers, SREs, and API teams monitoring federated and standalone graphs.**

Let's keep GraphQL observability standards-based, actionable, and as open as practical.
