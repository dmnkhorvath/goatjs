## OpenTelemetry, Prometheus & Grafana Learning Resources

*Compiled: 2026-03-15 | Verified URLs*

---

## Table of Contents
1. [OpenTelemetry with Node.js](#1-opentelemetry-with-nodejs)
2. [Prometheus Metrics Collection](#2-prometheus-metrics-collection)
3. [Grafana Dashboards for Node.js](#3-grafana-dashboards-for-nodejs)
4. [Recommended Learning Path](#4-recommended-learning-path)

---

## 1. OpenTelemetry with Node.js

OpenTelemetry (OTel) is the CNCF open-source observability framework providing a unified set of APIs, SDKs, and tools for collecting traces, metrics, and logs. Key concepts: traces, spans, metrics, auto-instrumentation, exporters, and the OpenTelemetry Collector.

### Official Documentation

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| OpenTelemetry JS - Getting Started (Node.js) | https://opentelemetry.io/docs/languages/js/getting-started/nodejs/ | docs | 30 min | Beginner | Official quickstart: instrument traces and metrics in a Node.js Express app in under 5 minutes. Covers SDK setup, auto-instrumentation, and console exporters. |
| OpenTelemetry JS - Instrumentation Guide | https://opentelemetry.io/docs/languages/js/instrumentation/ | docs | 1-2 hrs | Intermediate | Official guide on manual instrumentation: creating spans, recording metrics, and adding context propagation to Node.js apps. |
| OpenTelemetry JS - Zero-Code Instrumentation | https://opentelemetry.io/docs/zero-code/js/ | docs | 20 min | Beginner | Official guide to instrumenting Node.js apps without code changes using environment variables and auto-instrumentation packages. |
| OpenTelemetry JavaScript Landing Page | https://opentelemetry.io/docs/languages/js/ | docs | 15 min | Beginner | Overview of OpenTelemetry for JavaScript covering traces, metrics, logs for both Node.js and browser environments. |
| @opentelemetry/sdk-node API Reference | https://open-telemetry.github.io/opentelemetry-js/modules/_opentelemetry_sdk_node.html | docs | 1 hr | Intermediate | TypeDoc-generated API reference for the Node.js SDK package with all configuration options and interfaces. |
| @opentelemetry/auto-instrumentations-node (npm) | https://www.npmjs.com/package/@opentelemetry/auto-instrumentations-node | docs | 15 min | Beginner | npm package page for the meta-package that auto-instruments popular Node.js libraries (Express, HTTP, pg, mysql, etc.). |
| OpenTelemetry Collector Installation | https://opentelemetry.io/docs/collector/install/ | docs | 30 min | Intermediate | Official guide to installing and configuring the OpenTelemetry Collector for receiving, processing, and exporting telemetry data. |

### Written Tutorials & Articles

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| OpenTelemetry Node.js - Getting Started (SigNoz) | https://signoz.io/opentelemetry/nodejs/ | article | 45 min | Beginner | Comprehensive guide from zero-code to production-ready setup. Covers auto and manual instrumentation, traces, metrics, logs, and visualization with SigNoz. |
| Monitoring Node.js Apps with OpenTelemetry Metrics (BetterStack) | https://betterstack.com/community/guides/observability/opentelemetry-metrics-nodejs/ | article | 1 hr | Intermediate | Hands-on tutorial covering Counter, UpDownCounter, Gauge, and Histogram metric types with a Fastify demo app. Includes custom metrics and OTel Collector setup. |
| Distributed Tracing in Node.js with OpenTelemetry (BetterStack) | https://betterstack.com/community/guides/observability/opentelemetry-nodejs-tracing/ | article | 1 hr | Intermediate | Step-by-step guide to setting up distributed tracing with OpenTelemetry, exporting spans to Jaeger via the OTel Collector. |
| How to Use OpenTelemetry to Trace Node.js Applications (freeCodeCamp) | https://www.freecodecamp.org/news/how-to-use-opentelementry-to-trace-node-js-applications/ | article | 45 min | Beginner | Covers auto-instrumentation, SDK setup, Jaeger exporter, and Datadog integration via the OTel Collector. Includes multi-service tracing example. |
| OpenTelemetry for Node.js: Complete Setup Guide (Encore) | https://encore.cloud/resources/opentelemetry-nodejs-guide | article | 1 hr | Intermediate | Step-by-step SDK configuration, auto-instrumentation, custom spans, exporters, and collector setup with working code examples. |
| A Comprehensive Guide to OpenTelemetry in Node.js (TheRightSW) | https://therightsw.com/opentelemetry-in-node-js/ | article | 45 min | Intermediate | Covers setup, configuration, tracing, and integration with Jaeger. Explains traces, metrics, and logs concepts in the Node.js context. |
| Implementing OpenTelemetry in Node.js Microservices (Dev.to) | https://dev.to/codingmavrick/implementing-opentelemetry-in-nodejs-microservices-from-fundamentals-to-production-deployment-12d9 | article | 1 hr | Intermediate | From fundamentals to production deployment. Covers Express, Fastify, HTTP auto-instrumentation in microservice architectures. |
| Manual Instrumentation with OpenTelemetry for Node.js (Elastic) | https://www.elastic.co/observability-labs/blog/manual-instrumentation-nodejs-apps-opentelemetry | article | 45 min | Intermediate | Deep dive into manual instrumentation: creating custom spans, adding attributes, and recording events in Node.js applications. |
| Automatic Instrumentation with OpenTelemetry for Node.js (Elastic) | https://www.elastic.co/observability-labs/blog/auto-instrument-nodejs-apps-opentelemetry | article | 30 min | Beginner | How to auto-instrument Node.js apps using Docker and standard commands without modifying application code. |
| OpenTelemetry Traces & Spans Explained (OneUptime) | https://oneuptime.com/blog/post/2025-08-27-traces-and-spans-in-opentelemetry/view | article | 30 min | Beginner | Real code examples explaining traces and spans concepts for Node.js/TypeScript distributed tracing and debugging. |
| How to Set Up OpenTelemetry for Node.js Applications (OneUptime) | https://oneuptime.com/blog/post/2026-02-20-nodejs-opentelemetry-setup/view | article | 45 min | Beginner | From-scratch setup guide for OpenTelemetry in Node.js with Express, Fastify, and database driver auto-instrumentation. |
| Supercharge Your Node.js Monitoring with OTel, Prometheus, and Grafana (Dev.to) | https://dev.to/gleidsonleite/supercharge-your-nodejs-monitoring-with-opentelemetry-prometheus-and-grafana-4mhd | article | 1 hr | Intermediate | Full-stack tutorial combining OpenTelemetry tracing, Prometheus metrics, and Grafana visualization for Node.js apps. |
| How to Monitor Your Node.js Application Using OpenTelemetry and the Collector | https://rudimartinsen.com/2025/07/27/otel-instrumenting-app/ | article | 1 hr | Intermediate | Shows how to instrument a Node.js app with the OTel SDK and route signals through an OTel Collector to backends. |

### Online Courses (Free & Paid)

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Getting Started with OpenTelemetry - LFS148 (Linux Foundation) | https://training.linuxfoundation.org/blog/new-free-course-getting-started-with-opentelemetry-lfs148/ | course | 10 hrs | Beginner | FREE self-paced course with hands-on labs covering traces, metrics, logs, auto/manual instrumentation, and the OTel Collector. Certificate included. |
| Master OpenTelemetry: Free Course (Highlight.io) | https://nodejs.highlight.io/otel-course-signup | course | 5-8 hrs | Beginner | Free comprehensive OpenTelemetry course focused on Node.js observability from Highlight.io. |
| OpenTelemetry: Observability with JavaScript (Pluralsight) | https://www.pluralsight.com/courses/opentelemetry-observability-javascript | course | 3-4 hrs | Intermediate | Paid course covering OTel for both Node.js and browser. Auto and manual instrumentation techniques for end-to-end observability. |
| Monitoring Systems and Services with Prometheus - LFS241 (Linux Foundation) | https://training.linuxfoundation.org/training/monitoring-systems-and-services-with-prometheus-lfs241/ | course | 20 hrs | Intermediate | Paid course covering Prometheus monitoring including querying, alerting, and Kubernetes integration. Relevant for OTel + Prometheus pipelines. |
| OpenTelemetry Courses (Udemy) | https://www.udemy.com/topic/opentelemetry/ | course | Varies | All | Collection of paid OpenTelemetry courses on Udemy covering various backends and languages including Node.js. |
| Learn Prometheus from the Creator (PromLabs) | https://training.promlabs.com/ | course | Self-paced | All | Self-paced trainings by the co-founder of Prometheus. Covers PromQL, instrumentation, and alerting. |

### YouTube Videos & Playlists

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Practical OpenTelemetry in Javascript/Typescript - NDC Oslo 2024 | https://www.youtube.com/watch?v=Bh0PeMM6VZQ | video | 60 min | Intermediate | Conference talk by Martin Thwaites covering practical OTel implementation in JS/TS: codeless instrumentation, sampling strategies, and production deployment. |
| Distributed Tracing & OpenTelemetry in Node.js: Masterclass | https://www.youtube.com/watch?v=Pu-HiD2QksI | video | 90 min | Intermediate | In-depth masterclass on distributed tracing with OpenTelemetry in the Node.js ecosystem. |
| Tutorial: OpenTelemetry Node.js Instrumentation in 5 Minutes | https://www.youtube.com/watch?v=n-Ar0nnho3s | video | 5 min | Beginner | Quick-start video demonstrating OpenTelemetry Node.js instrumentation for traces, metrics, and logs. |
| How to Integrate OpenTelemetry for NodeJS Application | https://www.youtube.com/watch?v=TG7G2fH56OE | video | 30 min | Beginner | Step-by-step video tutorial on integrating OpenTelemetry into a Node.js application for observability. |
| OpenTelemetry Official YouTube Channel | https://www.youtube.com/channel/UCHZDBZTIfdy94xMjMKz-_MA/videos | video | Varies | All | Official OpenTelemetry channel with talks on orientation, best practices, and community updates. |

### Books

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| OpenTelemetry Official Documentation (comprehensive) | https://opentelemetry.io/docs/ | docs/book | 10+ hrs | All | The complete official documentation serves as the definitive reference book for OpenTelemetry concepts, APIs, and SDKs across all languages. |
| What is OpenTelemetry and How to Use It? (Padas.io) | https://www.padas.io/blog/2025/09/19/how-opentelemetry-use/index.html | article | 2 hrs | Beginner | Comprehensive beginner's guide covering core concepts, architecture, and hands-on setup with Node.js examples. |

### GitHub Repositories

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| open-telemetry/opentelemetry-js | https://github.com/open-telemetry/opentelemetry-js | repo | 2-4 hrs | Intermediate | Official OpenTelemetry JavaScript SDK. TypeScript-based, includes examples directory with working Node.js demos. |
| open-telemetry/opentelemetry-js (examples) | https://github.com/open-telemetry/opentelemetry-js/tree/main/examples | repo | 2 hrs | Beginner | Official examples directory with multiple Node.js instrumentation demos including Express, HTTP, and gRPC. |
| open-telemetry/opentelemetry-js-contrib | https://github.com/open-telemetry/opentelemetry-js-contrib | repo | 2 hrs | Intermediate | Community-maintained instrumentations for popular Node.js libraries (Express, Fastify, pg, mysql, Redis, etc.). |
| mnadeem/nodejs-opentelemetry-tempo | https://github.com/mnadeem/nodejs-opentelemetry-tempo | repo | 3 hrs | Advanced | Complete observability stack demo: Node.js + OpenTelemetry + Grafana Tempo + Prometheus + Loki + Grafana. Docker Compose included. |

---

## 2. Prometheus Metrics Collection

Prometheus is an open-source monitoring and alerting toolkit. For Node.js, the `prom-client` library is the standard for exposing metrics. Key concepts: counters, gauges, histograms, summaries, the `/metrics` endpoint, and PromQL.

### Official Documentation

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| prom-client (npm) | https://www.npmjs.com/package/prom-client | docs | 30 min | Beginner | Official npm page for prom-client v15.1.3. The standard Prometheus client for Node.js supporting Counter, Gauge, Histogram, and Summary metrics. |
| siimon/prom-client (GitHub) | https://github.com/siimon/prom-client | docs | 1 hr | Beginner | Official GitHub repo with comprehensive README covering all metric types, default metrics, labels, exemplars, OpenMetrics support, and Pushgateway. |
| prom-client README (detailed) | https://github.com/siimon/prom-client/blob/master/README.md | docs | 1 hr | Intermediate | Full API documentation with code examples for every metric type, default metrics configuration, cluster support, and multiple registries. |
| Prometheus Client Libraries | https://prometheus.io/docs/instrumenting/clientlibs/ | docs | 15 min | Beginner | Official Prometheus page listing all client libraries including the Node.js prom-client. |
| Understanding Metric Types (Prometheus) | https://prometheus.io/docs/tutorials/understanding_metric_types/ | docs | 30 min | Beginner | Official Prometheus tutorial explaining Counter, Gauge, Histogram, and Summary metric types with PromQL examples. |
| Prometheus Tutorials | https://prometheus.io/docs/tutorials/ | docs | 2 hrs | All | Official Prometheus tutorial collection covering features, integration, and usage for effective monitoring. |
| Prometheus Node.js Exporter (Grafana) | https://grafana.com/oss/prometheus/exporters/nodejs-exporter/ | docs | 20 min | Beginner | Grafana Labs quickstart for prom-client with preconfigured dashboards, alerting rules, and recording rules. |

### Written Tutorials & Articles

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Monitoring Node.js Apps with Prometheus (BetterStack) | https://betterstack.com/community/guides/scaling-nodejs/nodejs-prometheus/ | article | 1.5 hrs | Intermediate | Comprehensive guide using Fastify: automatic instrumentation with prom-client, custom metrics (Counter, Gauge, Histogram, Summary), Prometheus server setup, PromQL queries, and Alertmanager. |
| How to Set Up Prometheus to Collect Metrics from a Node.js App (Medium) | https://medium.com/@18bhavyasharma/how-to-set-up-prometheus-to-collect-metrics-from-a-node-js-app-a77d0d16fb32 | article | 30 min | Beginner | Step-by-step guide: installing Prometheus, configuring scraping, and using prom-client to expose metrics from a Node.js app. |
| Integrating Prometheus into Node/Express.js (DevOps Blog) | https://blog.devops.dev/integrating-prometheus-into-node-express-js-app-using-the-prom-client-library-to-monitor-app-604641049556 | article | 45 min | Beginner | Thorough explanation of Prometheus concepts and hands-on integration with Express.js using prom-client. |
| Instrument Node.js Code: Prometheus Custom Metrics (SquaredUp) | https://squaredup.com/blog/instrument-node-with-prometheus/ | article | 30 min | Intermediate | Focused walkthrough on creating custom business metrics in a Node.js Express app using prom-client. |
| Node.js and Prometheus: A Comprehensive Guide (w3tutorials) | https://www.w3tutorials.net/blog/nodejs-prometheus/ | article | 1 hr | Beginner | Comprehensive guide covering Prometheus architecture, metric types, prom-client setup, and best practices for Node.js monitoring. |
| Node.js Metrics with Prometheus (w3tutorials) | https://www.w3tutorials.net/blog/nodejs-metrics-prometheus/ | article | 45 min | Intermediate | Detailed coverage of all four Prometheus metric types with Node.js code examples and best practices. |
| Optimizing Performance Using Prometheus with Node.js (Dev.to) | https://dev.to/oluwatobi2001/optimizing-performance-using-prometheus-with-node-js-for-monitoring-b90 | article | 30 min | Beginner | Practical guide comparing prom-client with alternatives (express-prom-bundle, prometheus-api-metrics) and demonstrating integration. |
| Building a TypeScript Prometheus Client (WebDevTutor) | https://www.webdevtutor.net/blog/typescript-prometheus-client | article | 30 min | Intermediate | TypeScript-specific guide to creating a Prometheus client with prom-client, including type-safe metric definitions. |
| How to Add Custom Metrics to Node.js Applications with Prometheus (OneUptime) | https://oneuptime.com/blog/post/2026-01-06-nodejs-custom-metrics-prometheus/view | article | 30 min | Intermediate | Focused on implementing custom business metrics including histograms, gauges, and best practices for metric design. |
| Get Prometheus Metrics from an Express.js App (Dev.to) | https://dev.to/austincunningham/get-prometheus-metrics-from-a-express-js-app-53ck | article | 20 min | Beginner | Quick setup using express-prom-bundle (built on prom-client) for rapid Prometheus metrics in Express apps. |
| 13 Important Prometheus Custom Metrics for Express Server (Substack) | https://metu.substack.com/p/13-important-prometheus-custom-metrics | article | 30 min | Intermediate | Practical list of 13 essential custom metrics for Express servers with metric type recommendations and examples. |
| Node.js Application Monitoring with Prometheus and Grafana (StackAbuse) | https://stackabuse.com/nodejs-application-monitoring-with-prometheus-and-grafana/ | article | 1 hr | Intermediate | End-to-end guide: prom-client setup, default and custom metrics, Docker Compose orchestration, and Grafana dashboard creation. |
| Simple Example of Prometheus Client with Node.js (Medium) | https://medium.com/@the-poole/simple-example-of-prometheus-client-with-nodejs-bb53ddb038bb | article | 20 min | Beginner | Minimal example with Docker Compose for quickly getting prom-client running with Prometheus. |

### Online Courses

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Prometheus Monitoring: Configure & Visualize Systems (Coursera) | https://www.coursera.org/learn/prometheus-monitoring-configure-visualize-systems | course | 10-15 hrs | Intermediate | Coursera course covering Prometheus setup, PromQL, alerting, and Grafana visualization. |
| Learn Prometheus from the Creator (PromLabs) | https://training.promlabs.com/ | course | Self-paced | All | Self-paced trainings by Prometheus co-founder Julius Volz. Covers PromQL mastery, instrumentation, and alerting. |
| Monitoring with Prometheus (PrometheusBook) | https://www.prometheusbook.com/ | book/course | 10+ hrs | All | Comprehensive book/course teaching Prometheus for hosts, applications, and services including installation, service discovery, alerting, and visualization. |

### YouTube Videos & Playlists

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Prometheus & Grafana Monitoring Course for Beginners | https://www.youtube.com/playlist?list=PL48Qn423-MpgsJQax_oOG9yileqchcYss | playlist | 5+ hrs | Beginner | Beginner-friendly course: install Prometheus, collect system metrics from Linux servers, and visualize with Grafana dashboards. |
| Node.js Monitoring with Docker, Kubernetes, Prometheus & Grafana | https://www.youtube.com/watch?v=VIf48M93nCU | video | 45 min | Intermediate | Step-by-step tutorial for production-grade Node.js monitoring using Docker, Kubernetes, Prometheus, and Grafana. |
| The Developer's Guide to Mastering NodeJS with Prometheus and Grafana | https://www.youtube.com/watch?v=oyZhKaubFV0 | video | 40 min | Intermediate | Tutorial on monitoring NestJS applications using Prometheus and Grafana with essential metrics setup. |
| Monitor Express.js with Prometheus & Grafana (DevOps Tutorial #129) | https://www.youtube.com/watch?v=qnDRwknDg-E | video | 30 min | Beginner | Step-by-step integration of Prometheus + Grafana to collect metrics, expose them, and build dashboards for Express.js. |
| Prometheus Monitoring Official Channel | https://www.youtube.com/c/PrometheusIo | video | Varies | All | Official Prometheus YouTube channel with talks and videos about the monitoring system. |
| Prometheus Grafana Tutorial for Beginners | https://www.youtube.com/watch?v=5fN3CoEzT3A | video | 1 hr | Beginner | Core concepts of IT Monitoring, Visualization, Observability, Alerting & Notification, and Incident Management. |

### GitHub Repositories

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| siimon/prom-client | https://github.com/siimon/prom-client | repo | 2 hrs | Beginner | The official Prometheus client for Node.js. v15.1.3, supports all metric types, default metrics, labels, exemplars, OpenMetrics, and cluster mode. |
| labbsr0x/express-monitor | https://github.com/labbsr0x/express-monitor | repo | 1 hr | Beginner | Prometheus middleware for Express.js that adds basic but useful metrics automatically. Drop-in monitoring solution. |
| Adarshjain3011/express-prometheus-metrics | https://github.com/Adarshjain3011/express-prometheus-metrics | repo | 1 hr | Beginner | Demo repo showing Prometheus integration with Express and prom-client: HTTP request metrics, active connections, and system performance. |
| StackAbuse/node-prometheus-grafana | https://github.com/StackAbuse/node-prometheus-grafana | repo | 1 hr | Beginner | Complete Docker Compose project with Node.js app, Prometheus, and Grafana. Companion to the StackAbuse tutorial. |
| michalzagrodzki/prometheus-grafana | https://github.com/michalzagrodzki/prometheus-grafana | repo | 2 hrs | Intermediate | Complete monitoring sandbox: Node.js/Express + prom-client + Prometheus + Grafana + Loki + Promtail. Docker Compose orchestrated. |

---

## 3. Grafana Dashboards for Node.js

Grafana is an open-source visualization and analytics platform. It integrates with Prometheus for metrics, Loki for logs, and Tempo for traces. Key concepts: dashboards, panels, data sources, alerting, and the LGTM stack (Loki, Grafana, Tempo, Mimir/Prometheus).

### Official Documentation

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Get Started with Grafana and Prometheus | https://grafana.com/docs/grafana/latest/fundamentals/getting-started/first-dashboards/get-started-grafana-prometheus/ | docs | 45 min | Beginner | Official walkthrough: create dashboards in Grafana to display system metrics from Prometheus. Step-by-step with screenshots. |
| Grafana Technical Documentation | https://grafana.com/docs/ | docs | Ongoing | All | Complete official documentation hub for Grafana, Loki, Tempo, Mimir, Alloy, and all Grafana Labs products. |
| Node.js Integration (Grafana Cloud) | https://grafana.com/docs/grafana-cloud/monitor-infrastructure/integrations/integration-reference/integration-nodejs/ | docs | 30 min | Beginner | Official Grafana Cloud Node.js integration with 1 pre-built alert and 1 pre-built dashboard for prom-client metrics. |
| Grafana Tempo - Set Up for Tracing | https://grafana.com/docs/tempo/latest/set-up-for-tracing/ | docs | 1 hr | Intermediate | Official guide to setting up Grafana Tempo as a distributed tracing backend. Covers pipeline components, collector setup, and Grafana visualization. |
| Grafana Tempo - Set Up Your Collector | https://grafana.com/docs/tempo/latest/set-up-for-tracing/instrument-send/set-up-collector/ | docs | 30 min | Intermediate | Guide to configuring OpenTelemetry Collector or Grafana Alloy to forward traces to Tempo. |
| Grafana Loki Tutorial (Quick Start) | https://grafana.com/docs/loki/latest/get-started/quick-start/tutorial/ | docs | 1 hr | Beginner | Expanded quick start tutorial covering core Loki functions for log aggregation and querying. |
| Grafana Alerting - Get Started | https://grafana.com/tutorials/alerting-get-started/ | docs | 30 min | Beginner | Official tutorial: create your first Grafana alert, send notifications to a webhook, and generate sample data. |
| Grafana Fundamentals Tutorial | https://github.com/grafana/grafana/blob/main/docs/sources/tutorials/grafana-fundamentals/index.md | docs | 2 hrs | Beginner | Official fundamentals tutorial: explore metrics/logs, build dashboards, annotate, and set up alert rules. |
| Prometheus Support in Grafana | https://prometheus.io/docs/visualization/grafana/ | docs | 20 min | Beginner | Official Prometheus documentation on Grafana integration for creating dashboards and visualizations. |
| Instrument a Node.js Application (Grafana OTel docs) | https://grafana.com/docs/opentelemetry/instrument/node/ | docs | 45 min | Intermediate | Grafana's guide to instrumenting Node.js with the upstream OpenTelemetry SDK for Application Observability. |

### Pre-Built Dashboards

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| NodeJS Application Dashboard (ID: 11159) | https://grafana.com/grafana/dashboards/11159-nodejs-application-dashboard/ | dashboard | 15 min | Beginner | Pre-built Grafana dashboard for Node.js apps using prom-client default metrics. Import via dashboard ID 11159. Displays CPU, memory, event loop, GC, and HTTP metrics. |
| Node.js Dashboard (ID: 12230) | https://grafana.com/grafana/dashboards/12230-node-js-dashboard/ | dashboard | 15 min | Beginner | Alternative pre-built Node.js dashboard for Grafana with Prometheus data source. |
| Express.js Application Performance Dashboard (ID: 22603) | https://grafana.com/grafana/dashboards/22603-express-js-node-application-application-performance-dashboard/ | dashboard | 15 min | Intermediate | Grafana dashboard specifically for Express.js apps with prom-client metrics including request duration and throughput. |

### Written Tutorials & Articles

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| How to Configure Grafana Loki with a Node.js App (Grafana Blog) | https://grafana.com/blog/how-to-configure-grafana-loki-with-a-node-js-e-commerce-app/ | article | 1 hr | Intermediate | Official Grafana blog: configure Loki to collect logs from a Node.js/TypeScript Express app using winston and winston-loki. Includes LogQL queries and dashboard building. |
| Integrating Grafana with Node.js: A Comprehensive Guide (w3tutorials) | https://www.w3tutorials.net/blog/grafana-nodejs/ | article | 1 hr | Intermediate | Comprehensive guide covering Grafana + Node.js integration for metrics collection, visualization, and performance monitoring. |
| Monitor Your Node.js App with Prometheus and Grafana Using Docker (Medium) | https://bbhupen.medium.com/monitor-your-node-js-app-with-prometheus-and-grafana-using-docker-acae930c9e03 | article | 45 min | Beginner | Fully containerized setup using Docker Compose with Prometheus and Grafana to track Node.js app metrics. |
| Setting Up a Monitoring System with Prometheus and Grafana for Node.js (AWS Plain English) | https://aws.plainenglish.io/setting-up-a-monitoring-system-with-prometheus-and-grafana-for-a-node-js-application-5683fdc9b8e3 | article | 1 hr | Intermediate | Complete monitoring system setup: Prometheus for metrics, Grafana for visualization with panels for graphs, tables, heatmaps, and logs. |
| Creating Grafana Dashboards for Prometheus: A Beginner's Guide (BetterStack) | https://betterstack.com/community/guides/monitoring/visualize-prometheus-metrics-grafana/ | article | 1 hr | Beginner | Comprehensive guide to setting up Prometheus + Grafana, integrating Node Exporter, and crafting insightful dashboards. |
| Server Monitoring with Grafana, Prometheus, Loki, and Node.js (Level Up Coding) | https://levelup.gitconnected.com/building-a-robust-server-monitoring-system-with-grafana-prometheus-loki-and-node-js-455d1e170407 | article | 1.5 hrs | Intermediate | Build a powerful server monitoring system with the full LGTM stack and Node.js, all managed with Docker containers. |
| Distributed Tracing with OpenTelemetry, Grafana Tempo, and Node.js (DevOps Blog) | https://blog.devops.dev/distributed-tracing-with-opentelemetry-grafana-tempo-and-node-js-c0a3a0b61dc8 | article | 45 min | Intermediate | Setting up distributed tracing with OpenTelemetry, Grafana Tempo, and Docker Compose for Node.js microservices. |
| How to Configure Grafana Tempo as an OpenTelemetry Trace Backend (OneUptime) | https://oneuptime.com/blog/post/2026-02-06-grafana-tempo-opentelemetry-trace-backend/view | article | 30 min | Intermediate | Configure Grafana Tempo as a trace backend for OpenTelemetry including Collector setup, storage options, and querying traces. |
| Logging and Monitoring of Node.js with Winston, Promtail, Loki and Grafana (Medium) | https://medium.com/@cphasanulbanna/logging-and-monitoring-of-node-js-application-with-winston-grafana-and-loki-c1cd6485dc19 | article | 45 min | Intermediate | End-to-end logging pipeline: Winston logger -> Promtail -> Loki -> Grafana for Node.js applications. |
| Ultimate Guide: Shipping Node.js Application Logs to Loki (Medium) | https://medium.com/@faizanafridi/ultimate-guide-shipping-node-js-application-logs-to-loki-24036368b578 | article | 45 min | Intermediate | Guide to shipping Node.js logs to Loki using Winston and Pino-loki with Docker Compose for Grafana and Loki. |
| Consuming Loki Logs with Grafana API and Node.js (Dev.to) | https://dev.to/myunisoft/consuming-loki-logs-with-grafana-api-and-nodejs-bgg | article | 30 min | Advanced | Programmatically consuming Loki logs via the Grafana API from Node.js applications. |
| 5 Essential Tips for Node.js Alerting with Grafana | https://article.arunangshudas.com/5-essential-tips-for-node-js-alerting-with-grafana-2f4c012b495d | article | 20 min | Intermediate | Practical tips for setting up effective alerting for Node.js applications using Grafana and Prometheus. |
| Quick Guide: Application Monitoring with Node.js, Grafana and Prometheus (DevGenius) | https://blog.devgenius.io/quick-guide-application-monitoring-with-node-js-grafana-and-prometheus-ba4854014102 | article | 30 min | Beginner | Quick-start guide covering Grafana concepts, Prometheus integration, and basic dashboard creation for Node.js. |
| Deploying and Monitoring a Node.js App with Prometheus & Grafana (Medium) | https://medium.com/@iyousefzeer/deploying-and-monitoring-a-node-js-app-with-prometheus-grafana-a4a603c21e68 | article | 45 min | Intermediate | Metrics collection with Prometheus, visualization with Grafana, and Slack alerts for real-time monitoring. |
| Real-Time Dashboarding with Grafana and Prometheus (CodeZup) | https://codezup.com/real-time-dashboarding-with-grafana-and-prometheus/ | article | 1 hr | Intermediate | Comprehensive guide to building real-time dashboards with Grafana and Prometheus including best practices. |

### Online Courses

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Grafana for Beginners (YouTube Playlist - Official) | https://www.youtube.com/playlist?list=PLDGkOdUX1Ujo27m6qiTPPCpFHVfyKq9jT | course | 3-4 hrs | Beginner | Official Grafana YouTube series covering fundamentals: data sources, dashboards, panels, alerting, and exploration. |
| Grafana Crash Course (Volkov Labs) | https://volkovlabs.io/grafana/ | course | 5+ hrs | All | Living, regularly-updated guide from Volkov Labs matching Grafana's latest releases. Covers beginner to advanced topics. |
| Grafana Beginners to Advance Crash Course (Udemy) | https://www.udemy.com/course/grafana-latest/ | course | 5+ hrs | All | Udemy course with free lab access covering Grafana from basics to advanced data visualization and monitoring. |
| All Courses Catalog (Grafana Learn) | https://learn.grafana.com/page/course-catalog | course | Varies | All | Official Grafana learning platform with courses on dashboards, alerting, Loki, Tempo, and more. |

### YouTube Videos & Playlists

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Grafana for Beginners (Official Playlist) | https://www.youtube.com/playlist?list=PLDGkOdUX1Ujo27m6qiTPPCpFHVfyKq9jT | playlist | 3-4 hrs | Beginner | Official Grafana series covering fundamentals of dashboards, data sources, and visualization. |
| Creating Alerts with Grafana - Grafana for Beginners Ep 11 | https://www.youtube.com/watch?v=6W8Nu4b_PXM | video | 15 min | Beginner | Official Grafana video on setting up alerts so you don't need to watch dashboards 24/7. |
| Node.js Monitoring with Docker, Kubernetes, Prometheus & Grafana | https://www.youtube.com/watch?v=VIf48M93nCU | video | 45 min | Intermediate | Production-grade Node.js monitoring setup with the full Docker/K8s/Prometheus/Grafana stack. |
| Monitor Express.js with Prometheus & Grafana (DevOps Tutorial #129) | https://www.youtube.com/watch?v=qnDRwknDg-E | video | 30 min | Beginner | Step-by-step Prometheus + Grafana integration for Express.js backend monitoring. |
| Create Your First Grafana Dashboard (DevOps Tutorial #128) | https://www.youtube.com/watch?v=I3xoY0SdDJo | video | 25 min | Beginner | How to integrate Grafana & Prometheus and create your first monitoring dashboard on Ubuntu/Linux. |
| Monitor Everything with Grafana - Dashboard Step by Step | https://www.youtube.com/watch?v=fX8dIy6zGH8 | video | 45 min | Beginner | Complete beginner-friendly tutorial on Grafana as a monitoring and data visualization platform. |
| Grafana Tutorial for Beginners - Create Stunning Dashboards | https://www.youtube.com/watch?v=M4lviImpdPk | video | 40 min | Beginner | Step-by-step: install Grafana, connect data sources, and build beautiful dashboards. |
| Grafana Official YouTube Channel | https://www.youtube.com/@Grafana | video | Varies | All | Official Grafana channel with tutorials, conference talks, and product updates. |

### GitHub Repositories

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| mnadeem/nodejs-opentelemetry-tempo | https://github.com/mnadeem/nodejs-opentelemetry-tempo | repo | 3 hrs | Advanced | Complete observability stack: Node.js + OpenTelemetry + Tempo + Prometheus + Loki + Grafana. Docker Compose with best practices for logging, metrics, and tracing. |
| michalzagrodzki/prometheus-grafana | https://github.com/michalzagrodzki/prometheus-grafana | repo | 2 hrs | Intermediate | Complete monitoring sandbox: Node.js/Express + prom-client + Prometheus + Grafana + Loki + Promtail. Pre-provisioned dashboards included. |
| luan-hubner/nodejs-logs-to-loki | https://github.com/luan-hubner/nodejs-logs-to-loki | repo | 1 hr | Beginner | Demo project: Node.js API sending logs to Loki via Promtail with Grafana visualization. Docker Compose included. |
| Abdulwasay10/Production-Ready-Observability-Stack | https://github.com/Abdulwasay10/Production-Ready-Observability-Stack-with-Grafana-Prometheus-Loki-Node-Exporter-Docker-Compose | repo | 2 hrs | Intermediate | Production-ready observability stack with Grafana, Prometheus, Loki, Promtail, and Node Exporter. Docker Compose orchestrated. |
| grafana/grafana (Fundamentals Tutorial) | https://github.com/grafana/grafana/blob/main/docs/sources/tutorials/grafana-fundamentals/index.md | repo | 2 hrs | Beginner | Official Grafana fundamentals tutorial source: explore metrics/logs, build dashboards, annotate, and set up alerts. |

---

## 4. Recommended Learning Path

### Week 1-2: OpenTelemetry Foundations
1. Complete the [Linux Foundation LFS148 free course](https://training.linuxfoundation.org/blog/new-free-course-getting-started-with-opentelemetry-lfs148/) (10 hrs)
2. Follow the [official Node.js getting started guide](https://opentelemetry.io/docs/languages/js/getting-started/nodejs/) (30 min)
3. Watch [Practical OpenTelemetry in JS/TS - NDC Oslo 2024](https://www.youtube.com/watch?v=Bh0PeMM6VZQ) (60 min)
4. Read the [SigNoz comprehensive guide](https://signoz.io/opentelemetry/nodejs/) (45 min)
5. Explore the [official examples](https://github.com/open-telemetry/opentelemetry-js/tree/main/examples) (2 hrs)

### Week 3-4: Prometheus Metrics Mastery
1. Read the [prom-client README](https://github.com/siimon/prom-client/blob/master/README.md) thoroughly (1 hr)
2. Follow the [BetterStack Prometheus + Node.js guide](https://betterstack.com/community/guides/scaling-nodejs/nodejs-prometheus/) (1.5 hrs)
3. Complete the [StackAbuse end-to-end tutorial](https://stackabuse.com/nodejs-application-monitoring-with-prometheus-and-grafana/) (1 hr)
4. Watch the [Prometheus & Grafana Monitoring Course for Beginners](https://www.youtube.com/playlist?list=PL48Qn423-MpgsJQax_oOG9yileqchcYss) (5 hrs)
5. Clone and experiment with [michalzagrodzki/prometheus-grafana](https://github.com/michalzagrodzki/prometheus-grafana) (2 hrs)

### Week 5-6: Grafana Visualization & Full Stack
1. Watch the [Grafana for Beginners official playlist](https://www.youtube.com/playlist?list=PLDGkOdUX1Ujo27m6qiTPPCpFHVfyKq9jT) (3-4 hrs)
2. Follow the [Grafana + Prometheus getting started guide](https://grafana.com/docs/grafana/latest/fundamentals/getting-started/first-dashboards/get-started-grafana-prometheus/) (45 min)
3. Import the [NodeJS Application Dashboard](https://grafana.com/grafana/dashboards/11159-nodejs-application-dashboard/) (15 min)
4. Read the [Grafana Loki + Node.js blog post](https://grafana.com/blog/how-to-configure-grafana-loki-with-a-node-js-e-commerce-app/) (1 hr)
5. Set up the [Grafana Tempo tracing pipeline](https://grafana.com/docs/tempo/latest/set-up-for-tracing/) (1 hr)
6. Clone and deploy [mnadeem/nodejs-opentelemetry-tempo](https://github.com/mnadeem/nodejs-opentelemetry-tempo) for the complete LGTM stack (3 hrs)
7. Set up [Grafana alerting](https://grafana.com/tutorials/alerting-get-started/) for your Node.js app (30 min)

### Week 7+: Advanced Topics
- Explore [OpenTelemetry manual instrumentation](https://opentelemetry.io/docs/languages/js/instrumentation/) for custom spans and metrics
- Learn [PromQL](https://prometheus.io/docs/tutorials/) for advanced metric queries
- Build custom Grafana dashboards combining metrics, logs, and traces
- Implement the full observability pipeline in a production environment

---

*Total resources: 130+ entries across 3 subtopics*
*All URLs verified as of March 2026*


---

# Logging & Monitoring in Node.js/TypeScript - Part 3
# Error Tracking, APM Tools, and Health Checks

> Research compiled: 2026-03-15 | 24 web searches performed, key URLs verified via document_query

---

## Table of Contents
1. [Error Tracking (Sentry Integration)](#1-error-tracking-sentry-integration)
2. [APM Tools for Node.js](#2-apm-tools-for-nodejs)
3. [Health Checks and Readiness Probes](#3-health-checks-and-readiness-probes)

---

## 1. Error Tracking (Sentry Integration)

Sentry is the industry-leading error tracking and performance monitoring platform for Node.js/TypeScript applications. The `@sentry/node` SDK (v10.x) provides automatic error capture, distributed tracing via OpenTelemetry, profiling, source map support, and log correlation. It integrates with Express, Fastify, NestJS, Koa, and other frameworks out of the box.

### 1.1 Official Documentation

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Sentry Node.js SDK Guide | https://docs.sentry.io/platforms/javascript/guides/node/ | docs | 1-2 hrs | Beginner | Official setup guide covering installation, initialization, error capture, tracing, profiling, and logs for Node.js. Verified: covers `@sentry/node` with OpenTelemetry-based performance instrumentation. |
| Sentry Node.js Installation Methods | https://docs.sentry.io/platforms/javascript/guides/node/install/ | docs | 30 min | Beginner | Covers ESM vs CJS setup, lightweight mode with `@sentry/node-core`, and choosing the right installation method. |
| Sentry Source Maps - TypeScript (tsc) | https://docs.sentry.io/platforms/javascript/guides/node/sourcemaps/uploading/typescript/ | docs | 30 min | Intermediate | Step-by-step guide for uploading TypeScript source maps using sentry-cli for readable stack traces in production. |
| Sentry Node.js Configuration | https://docs.sentry.io/platforms/javascript/guides/node/configuration/ | docs | 45 min | Intermediate | Extended configuration options including releases, filtering, event loop block detection, and tree shaking. |
| Sentry Node.js Integrations | https://docs.sentry.io/platforms/javascript/guides/node/configuration/integrations/ | docs | 30 min | Intermediate | Auto-instrumentation integrations for Express, Fastify, HTTP, database drivers, and more. |
| Sentry Fastify Integration | https://docs.sentry.io/platforms/javascript/guides/fastify/ | docs | 30 min | Intermediate | Dedicated Fastify guide for error monitoring and performance tracing with Sentry SDK. |
| Sentry NestJS Recipe | https://docs.nestjs.com/recipes/sentry | docs | 30 min | Intermediate | Official NestJS documentation for integrating Sentry error tracking and performance monitoring into NestJS applications. |
| Sentry Performance Metrics | https://docs.sentry.io/platforms/javascript/guides/node/tracing/instrumentation/performance-metrics/ | docs | 30 min | Advanced | Adding custom attributes to spans for detailed performance monitoring and debugging. |
| Sentry Metrics Setup | https://docs.sentry.io/platforms/javascript/guides/node/metrics/ | docs | 20 min | Intermediate | Setting up custom counters, gauges, and measurements to track application health metrics. |
| Capturing Errors - Sentry Node.js | https://docs.sentry.io/platforms/javascript/guides/node/usage/ | docs | 20 min | Beginner | Manual error capture, breadcrumbs, user context, and custom event reporting. |

### 1.2 Written Tutorials & Articles

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| How to Add Sentry to Your Node.js Project with TypeScript (freeCodeCamp) | https://www.freecodecamp.org/news/how-to-add-sentry-to-your-node-js-project-with-typescript/ | article | 30 min | Beginner | Verified: Covers full setup including `@sentry/node`, `@sentry/integrations`, RewriteFrames for TypeScript path mapping, DSN configuration, and dashboard setup. |
| Sentry + Node.js TypeScript Expert Guide (ExpertBeacon) | https://expertbeacon.com/how-to-add-sentry-to-your-node-js-project-with-typescript-an-expert-guide/ | article | 45 min | Intermediate | In-depth guide covering source map configuration, GitHub/Jira/Slack integrations, and custom application context. |
| How to Add Sentry Integration to Your NodeJS App (DEV) | https://dev.to/yusadolat/how-to-add-sentry-integration-to-your-nodejs-app-26eo | article | 20 min | Beginner | Quick-start tutorial for adding Sentry to an Express.js TypeScript application. |
| Maximizing Node.js Performance with Sentry.io (Medium) | https://medium.com/@farras.hafizhudin/maximizing-nodejs-performances-with-sentry-io-platform-monitoring-services-76e51a3f24e5 | article | 25 min | Intermediate | Focuses on performance monitoring capabilities: transaction tracing, real-time analytics, and optimization insights. |
| How to Debug, Log, and Monitor Performance in Node.js (Sentry Blog) | https://blog.sentry.io/how-to-debug-log-and-monitor-performance-in-node-js/ | article | 30 min | Intermediate | Official Sentry blog post (Oct 2024) covering debugging workflows, logging integration, and performance monitoring best practices. |
| Efficient Error Monitoring: Sentry in Node.js, Express.js, MongoDB (Medium/Widle) | https://medium.com/widle-studio/enhancing-error-tracking-and-monitoring-integrating-sentry-in-node-js-3f827deffca5 | article | 30 min | Intermediate | End-to-end tutorial covering error capture, custom events, transaction tracing, and release management. |
| Enhance Error Tracking: Sentry with Node.js & Express.js (Developer Diary) | https://devdiaryacademy.medium.com/enhance-error-tracking-monitoring-integrate-sentry-with-node-js-express-js-developer-diary-fd42578ea61d | article | 25 min | Beginner | Step-by-step integration guide with Express.js focusing on practical error tracking setup. |
| Sentry Node with TypeScript: Comprehensive Guide (xjavascript) | https://www.xjavascript.com/blog/sentry-node-typescript/ | article | 35 min | Intermediate | Covers concepts, usage methods, common practices, and best practices for Sentry with TypeScript. |
| Using Sentry with NodeJS and TypeScript (Medium/Elliot Blackburn) | https://medium.com/engineering-on-the-incline/using-sentry-with-nodejs-and-typescript-bfe4483c1b5d | article | 20 min | Intermediate | Practical guide on using Sentry with TypeScript sourcemaps in production environments. |
| Stop Flying Blind: Error Handling & Logging Best Practices for Node.js (Meerako) | https://www.meerako.com/blogs/error-handling-logging-best-practices-nodejs-sentry | article | 30 min | Intermediate | Combines Sentry integration with structured logging (Pino/Winston) best practices for comprehensive error handling. |
| Getting Started with Sentry (Sentry Build Academy) | https://sentry-build-academy.sentry.dev/getting-started/ | article | 1 hr | Beginner | Interactive learning platform covering Error Monitoring, Logging, Replays, and Tracing for React frontend and Node.js backend. |
| Sentry TS Guide (GitHub Gist) | https://gist.github.com/yigitkonur/34bdd697f5f27fd16b37de2c77d1183f | article | 45 min | Intermediate | Comprehensive guide covering @sentry/browser, @sentry/node, @sentry/react, @sentry/nextjs SDK integration patterns. |

### 1.3 YouTube Videos

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Sentry Integration in Node.js: Ultimate Guide for Advanced Error Tracking | https://www.youtube.com/watch?v=bsiwhthPfNA | video | ~30 min | Intermediate | Comprehensive tutorial on integrating Sentry into Node.js for error tracking and performance insights. |
| Sentry: Capturing Backend Errors (TypeScript, Node.js) - Lesson 118 | https://www.youtube.com/watch?v=OohNVkZSPa4 | video | ~20 min | Beginner | Focused tutorial on Sentry integration for error logging on a Node.js TypeScript backend. |
| Sentry 101: Error Monitoring For Backend Applications | https://www.youtube.com/watch?v=DzhVEK65eYg | video | ~25 min | Beginner | Official Sentry overview for backend apps (Python, PHP, Node.js, Ruby, Go) - covers the who, what, when, and where of errors. |
| Sentry Tutorial: Track Errors in Production | https://www.youtube.com/watch?v=561iVCoysr8 | video | ~15 min | Beginner | Introduction to using Sentry for tracking production errors in web applications. |
| Stop Debugging Blindly! Catch Every Error in Node.js with Sentry | https://www.youtube.com/watch?v=pGEHXW6ZKjk | video | ~20 min | Beginner | Practical guide to catching bugs, crashes, and exceptions using Sentry in Node.js applications. |
| Node.js Monitoring with Sentry (GitNation Workshop) | https://gitnation.com/contents/tracking-errors-and-slowdowns-in-node-javascript-using-sentry | video | 1-2 hrs | Intermediate | Workshop covering application monitoring with Sentry for React, Express, and Node.js - includes debugging demos. |

### 1.4 GitHub Repositories

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| getsentry/sentry-javascript | https://github.com/getsentry/sentry-javascript | repo | 2-4 hrs | Intermediate | Official Sentry JavaScript SDK monorepo - includes @sentry/node, @sentry/browser, framework integrations, and examples. |
| AlbertHernandez/ts-node-sentry-example | https://github.com/AlbertHernandez/ts-node-sentry-example | repo | 30 min | Beginner | Minimal example of a TypeScript backend application configured with Sentry for error tracking. |
| @sentry/node on npm | https://www.npmjs.com/package/@sentry/node | repo | 15 min | Beginner | npm package page with 2,722+ dependent projects - Sentry Node SDK using OpenTelemetry for performance instrumentation. |

### 1.5 Error Handling Best Practices Resources

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Node.js Best Practices (goldbergyoni) | https://github.com/goldbergyoni/nodebestpractices | repo | 3-5 hrs | All levels | 80+ best practices including comprehensive error handling section - the largest Node.js best practices compilation. |
| Mastering Error Handling in Node.js (Medium) | https://medium.com/@govindaekbote7/mastering-error-handling-in-node-js-best-practices-for-robust-applications-a5d1af0e0f1e | article | 25 min | Intermediate | Covers error types, production-grade patterns, and best practices for robust Node.js applications. |
| 13 Proven Node.js Monitoring Best Practices (Atatus) | https://www.atatus.com/blog/nodejs-monitoring-best-practices/ | article | 30 min | Intermediate | Comprehensive monitoring best practices for tracking, fixing, and optimizing Node.js app performance. |

---

## 2. APM Tools for Node.js

Application Performance Monitoring (APM) tools provide distributed tracing, profiling, metrics collection, and flame graph visualization for Node.js applications. The ecosystem includes commercial solutions (Datadog, New Relic, Dynatrace, Elastic APM) and open-source alternatives (OpenTelemetry, Jaeger, Grafana Tempo). OpenTelemetry has emerged as the vendor-neutral standard for instrumentation.

### 2.1 Official Documentation

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| OpenTelemetry Node.js Getting Started | https://opentelemetry.io/docs/languages/js/getting-started/nodejs/ | docs | 1 hr | Beginner | Verified: Official guide to instrumenting traces and metrics in Node.js with OpenTelemetry SDK, auto-instrumentation, and console exporters. |
| Elastic APM Node.js Agent - TypeScript | https://www.elastic.co/docs/reference/apm/agents/nodejs/typescript | docs | 45 min | Intermediate | Official Elastic guide for integrating APM agent with TypeScript projects, including type definitions and example project. |
| Elastic APM Node.js Agent Overview | https://www.elastic.co/docs/reference/apm/agents/nodejs | docs | 1 hr | Intermediate | Complete reference for the Elastic APM Node.js Agent - built-in framework support, API reference, and configuration. |
| Datadog Node.js Tracing | https://docs.datadoghq.com/tracing/trace_collection/dd_libraries/nodejs/ | docs | 1 hr | Intermediate | Official Datadog documentation for dd-trace Node.js library - supports Node.js >=18, auto-instrumentation for popular frameworks. |
| Datadog Node.js Library Configuration | https://docs.datadoghq.com/tracing/trace_collection/library_config/nodejs/ | docs | 30 min | Intermediate | Advanced configuration for Datadog tracing library including Unified Service Tagging and runtime settings. |
| New Relic Node.js Monitoring | https://docs.newrelic.com/docs/apm/agents/nodejs-agent/getting-started/monitor-your-nodejs-app/ | docs | 45 min | Beginner | Official New Relic guide for monitoring Node.js applications - setup, configuration, and data viewing. |
| Introduction to New Relic for Node.js | https://docs.newrelic.com/docs/apm/agents/nodejs-agent/getting-started/introduction-new-relic-nodejs/ | docs | 30 min | Beginner | Overview of New Relic Node.js capabilities: service maps, errors inbox, logs in context, and performance monitoring. |
| Node.js Flame Graphs (Official) | https://nodejs.org/en/learn/diagnostics/flame-graphs | docs | 30 min | Intermediate | Verified: Official Node.js guide to creating flame graphs using 0x tool and system perf tools for CPU profiling. |

### 2.2 Written Tutorials & Articles

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Top 9 APM Tools for Node.js Performance Monitoring (Last9) | https://last9.io/blog/apm-tools-for-node-js-performance-monitoring/ | article | 40 min | Intermediate | Verified: Compares 9 APM tools (Last9, Sentry, AppDynamics, Instana, Grafana Tempo, AppSignal, Datadog, SkyWalking, Elastic APM) with selection guidance. |
| Best Node.js Observability Tools 2025 (NodeSource) | https://nodesource.com/blog/nodejs-observability-tools-2025 | article | 35 min | Intermediate | Compares N|Solid, New Relic, Datadog, and open-source options for Node.js observability with focus on production workloads. |
| Top APM Tools: Real-World Comparison (Medium) | https://medium.com/@kaanberkozbek/top-apm-tools-real-world-comparison-of-pros-cons-cost-performance-and-use-cases-b7dc77f97102 | article | 30 min | Intermediate | Hands-on 2025 comparison covering strengths, weaknesses, pricing, scalability, and best-fit use cases. |
| Best 7 Monitoring Tools for Node.js (Atatus) | https://www.atatus.com/blog/best-monitoring-tools-for-node-js-application/ | article | 25 min | Beginner | Overview of top monitoring tools with key metrics to track in Node.js applications. |
| Distributed Tracing in Node.js with OpenTelemetry (BetterStack) | https://betterstack.com/community/guides/observability/opentelemetry-nodejs-tracing/ | article | 1.5 hrs | Intermediate | Verified: Hands-on tutorial with demo project, Jaeger visualization, OpenTelemetry Collector setup, and custom span instrumentation. |
| OpenTelemetry in Node.js Microservices (DEV) | https://dev.to/codingmavrick/implementing-opentelemetry-in-nodejs-microservices-from-fundamentals-to-production-deployment-12d9 | article | 45 min | Advanced | Production deployment guide for OpenTelemetry in Node.js microservices with scaling considerations. |
| How to Use OpenTelemetry to Trace Node.js Applications (freeCodeCamp) | https://www.freecodecamp.org/news/how-to-use-opentelementry-to-trace-node-js-applications/ | article | 40 min | Beginner | Auto-instrumentation guide with minimal code - covers SDK setup, auto-tracing, metrics collection, and backend export. |
| Elastic APM Setup for Node.js (ExpertBeacon) | https://expertbeacon.com/how-to-set-up-application-performance-monitoring-for-node-js-applications-using-elastic-apm/ | article | 45 min | Intermediate | Production-ready Elastic APM setup with comparison to New Relic and actionable performance insights. |
| Datadog Basics for TypeScript Developers (Medium) | https://medium.com/@natz.dev/basic-datadog-concepts-for-the-busy-typescript-developer-18102e888fda | article | 25 min | Beginner | Concise guide to APM traces, spans, and logs with Node.js examples for TypeScript developers. |
| Monitoring Node.js Using Datadog APM (GameChanger) | https://tech.gc.com/monitoring-node-js-using-datadog-apm/ | article | 30 min | Intermediate | Real-world experience report on Datadog APM implementation for Node.js with practical tips. |
| Node.js APM: A Practical Guide (CubeAPM) | https://cubeapm.com/blog/nodejs-apm-practical-guide/ | article | 35 min | Intermediate | Covers instrumentation, OpenTelemetry, performance overhead, tracing async workflows, and observability trade-offs. |
| Monitoring Node.js with OpenTelemetry Metrics (BetterStack) | https://betterstack.com/community/guides/observability/opentelemetry-metrics-nodejs/ | article | 1 hr | Intermediate | Setting up OpenTelemetry metrics in Node.js - tracking key metrics and sending data to analysis backends. |
| Next-Gen Flamegraphs for Node.js (Platformatic) | https://blog.platformatic.dev/introducing-next-gen-flamegraphs-for-nodejs | article | 20 min | Intermediate | New CPU profiling and flamegraph tools with WebGL graphics for Node.js performance optimization. |
| Node.js Flame Graphs: Visualizing Performance Bottlenecks (Medium) | https://medium.com/@kotiansachin/node-js-flame-graphs-visualizing-performance-bottlenecks-with-clarity-a6a5d6041755 | article | 20 min | Intermediate | Practical guide to running Node.js apps with profiling and generating flame graph SVG files. |
| Understanding Flame Graphs in Node.js (NodeSource) | https://nodesource.com/blog/understanding-flame-graphs-in-nodejs/ | article | 25 min | Intermediate | Explains flame graph visualization with AI-assisted analysis for identifying performance bottlenecks. |
| Tracing Node.js Applications with OpenTelemetry (Medium/Zigbang) | https://medium.com/zigbang/tracing-nodejs-applications-with-opentelemetry-624958d38d4d | article | 30 min | Intermediate | Setting up a complete observability stack with Node.js, TypeScript, and OpenTelemetry. |

### 2.3 Online Courses

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Debugging Your Node.js Project with Sentry (Workshop) | https://sentry.io/resources/debugging-your-nodejs-project/ | course | 1-2 hrs | Beginner | Free Sentry workshop walking through setup, error monitoring, and debugging context for Node.js applications. |
| OpenTelemetry Getting Started (Official) | https://opentelemetry.io/docs/languages/js/getting-started/nodejs/ | course | 2-3 hrs | Beginner | Free official tutorial series covering traces, metrics, and instrumentation for Node.js with hands-on examples. |
| New Relic TypeScript Quickstart | https://newrelic.com/instant-observability/typescript | course | 1 hr | Beginner | Free New Relic quickstart for instrumenting and monitoring TypeScript-built apps with the Node.js agent. |

### 2.4 YouTube Videos

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Node.js Microservices with APM Tools | https://www.youtube.com/watch?v=PlXfkoLfZbU | video | ~30 min | Intermediate | Explores how APM tools identify bottlenecks, optimize resources, and ensure microservices handle increasing load. |
| What is Application Performance Monitoring in Node.js? | https://www.youtube.com/watch?v=Rzz8uf_j0uM | video | ~25 min | Beginner | Deep-dive into APM for Node.js - monitoring outages, improving reliability, and debugging performance issues. |

### 2.5 GitHub Repositories

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| open-telemetry/opentelemetry-js | https://github.com/open-telemetry/opentelemetry-js | repo | 3-5 hrs | Intermediate | Official OpenTelemetry JavaScript SDK - includes Node.js SDK, auto-instrumentation, exporters, and examples. |
| elastic/apm-agent-nodejs | https://github.com/elastic/apm-agent-nodejs | repo | 2-3 hrs | Intermediate | Official Elastic APM Node.js agent - automatic error capture, tracing, and performance metrics with built-in framework support. |
| DataDog/dd-trace-js | https://github.com/DataDog/dd-trace-js | repo | 2-3 hrs | Intermediate | Official Datadog APM tracer for Node.js - captures APM data with auto-instrumentation for popular frameworks. |
| mehmeCelenk/new-relic | https://github.com/mehmeCelenk/new-relic | repo | 1 hr | Beginner | New Relic Node.js monitoring examples with TypeScript and JavaScript implementations, custom events, and metrics. |
| Surya07102000/New-Relic-Integration-POC | https://github.com/Surya07102000/New-Relic-Integration-POC | repo | 1 hr | Beginner | Proof of Concept for New Relic monitoring with Node.js, PostgreSQL + TypeORM, and full TypeScript implementation. |
| Clinic.js (includes Flame) | https://clinicjs.org/flame/ | repo | 1-2 hrs | Intermediate | Node.js performance profiling suite - Clinic.js Flame creates flamegraphs via CPU sampling for identifying hot code paths. |
| 0x - Flame Graph Profiling | https://www.npmjs.com/package/0x | repo | 30 min | Beginner | Single-step flame graph generation tool for Node.js - the simplest way to profile and visualize CPU performance. |

### 2.6 npm Packages

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| @sentry/node | https://www.npmjs.com/package/@sentry/node | package | 15 min | Beginner | Sentry Node SDK (v10.x) with OpenTelemetry-based performance instrumentation. 2,722+ dependents. |
| elastic-apm-node | https://www.npmjs.com/package/elastic-apm-node | package | 15 min | Beginner | Official Elastic APM agent for Node.js (v4.15.0). 323+ dependents. |
| dd-trace | https://www.npmjs.com/package/dd-trace | package | 15 min | Beginner | Datadog APM tracer for Node.js - captures traces, metrics, and logs. |
| newrelic | https://www.npmjs.com/package/newrelic | package | 15 min | Beginner | New Relic Node.js agent with Next.js support, custom instrumentation, and transaction naming. |
| @opentelemetry/sdk-node | https://www.npmjs.com/package/@opentelemetry/sdk-node | package | 15 min | Beginner | OpenTelemetry Node.js SDK - vendor-neutral instrumentation with pluggable exporters. |

---

## 3. Health Checks and Readiness Probes

Health checks and readiness probes are essential for running Node.js applications in Kubernetes and other orchestrated environments. They enable the platform to determine if an application is alive (liveness), ready to accept traffic (readiness), and has completed startup (startup probes). Key libraries include `@godaddy/terminus` for graceful shutdown, `lightship` for Kubernetes probe abstraction, and `opossum` for circuit breaker patterns.

### 3.1 Official Documentation

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Health Checks and Graceful Shutdown - Express.js | https://expressjs.com/en/advanced/healthcheck-graceful-shutdown.html | docs | 30 min | Beginner | Verified: Official Express guide recommending @godaddy/terminus for health check endpoints and graceful shutdown with Kubernetes integration. |
| Configure Liveness, Readiness and Startup Probes - Kubernetes | https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-startup-probes/ | docs | 45 min | Intermediate | Official Kubernetes documentation for configuring all three probe types with HTTP, TCP, and command-based checks. |
| Liveness, Readiness, and Startup Probes - Kubernetes Concepts | https://kubernetes.io/docs/concepts/configuration/liveness-readiness-startup-probes/ | docs | 30 min | Beginner | Conceptual overview of Kubernetes probe types, their purposes, and interaction patterns. |
| Health Checks - Node.js Reference Architecture | https://nodeshift.dev/nodejs-reference-architecture/operations/healthchecks/ | docs | 20 min | Intermediate | NodeShift reference architecture guidance for implementing Kubernetes-compatible health checks in Node.js. |

### 3.2 Libraries & Tools

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| @godaddy/terminus (npm) | https://www.npmjs.com/package/@godaddy/terminus | package | 30 min | Beginner | Verified: Adds graceful shutdown and Kubernetes readiness/liveness checks to any Node.js HTTP app. Works with Express, Koa, and plain HTTP servers. Configurable health endpoints, shutdown hooks, and timeout handling. |
| godaddy/terminus (GitHub) | https://github.com/godaddy/terminus | repo | 1 hr | Beginner | Verified: Source code with examples for Express, Koa, and cluster mode. Includes beforeShutdown hook for Kubernetes pod termination race condition handling. |
| lightship (npm) | https://www.npmjs.com/package/lightship | package | 30 min | Intermediate | Verified: Abstracts readiness (/ready), liveness (/live), and startup checks with graceful shutdown. Features beacon system for in-flight task tracking, configurable timeouts, and auto-detection of non-Kubernetes environments. |
| gajus/lightship (GitHub) | https://github.com/gajus/lightship | repo | 1 hr | Intermediate | Verified: Full source with /health, /live, /ready endpoints. Supports signalReady(), signalNotReady(), shutdown(), registerShutdownHandler(), createBeacon(), and queueBlockingTask(). |
| opossum - Circuit Breaker (npm) | https://www.npmjs.com/package/opossum | package | 30 min | Intermediate | Node.js circuit breaker that monitors async function execution - fails fast when services are down, with optional fallback functions. |
| nodeshift/opossum (GitHub) | https://github.com/nodeshift/opossum | repo | 1 hr | Intermediate | Circuit breaker pattern implementation for Node.js - prevents cascading failures in distributed systems with configurable thresholds. |
| express-actuator (npm) | https://www.npmjs.com/package/express-actuator | package | 15 min | Beginner | Spring Boot Actuator-inspired middleware providing /health, /info, and /metrics endpoints for Express.js applications. |
| hmcts/nodejs-healthcheck (GitHub) | https://github.com/hmcts/nodejs-healthcheck | repo | 30 min | Beginner | Library exposing /health, /health/liveness, and /health/readiness endpoints with configurable check evaluation. |

### 3.3 Written Tutorials & Articles

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Health Checks and Readiness Probes in Node.js for Kubernetes (OneUptime) | https://oneuptime.com/blog/post/2026-01-06-nodejs-health-checks-kubernetes/view | article | 35 min | Intermediate | Comprehensive guide covering dependency checking, graceful degradation, and proper Kubernetes probe configuration for Node.js. |
| Demystifying Kubernetes Probes: Deep Dive with Node.js (Medium) | https://medium.com/@bhargavjagan/demystifying-kubernetes-probes-a-deep-dive-with-node-js-fdfc56372dc1 | article | 30 min | Intermediate | Hands-on exploration of liveness, readiness, and startup probes with a Node.js application - includes failure scenario testing. |
| How to Configure Kubernetes Probes in a Node.js Application (FAUN) | https://faun.pub/how-to-configure-kubernetes-probes-in-a-node-js-application-4cdbfd84f548 | article | 25 min | Intermediate | Practical guide to implementing all three Kubernetes probe types in Node.js with YAML configuration examples. |
| How to Add a Node.js Health Check Endpoint Using Express (Hyperping) | https://hyperping.com/blog/how-to-add-a-nodejs-health-check-endpoint-using-express | article | 15 min | Beginner | Quick tutorial for creating a health route monitored by uptime monitoring services. |
| Graceful Shutdown with NodeJS and Terminus (DEV) | https://dev.to/wakeupmh/graceful-shutdown-with-nodejs-and-terminus-1gjn | article | 20 min | Beginner | Introduction to graceful shutdown concepts and practical Terminus implementation. |
| Implement Health Checks and Graceful Shutdown with Lightship (Medium) | https://medium.com/node-depths/implement-health-checks-and-graceful-shutdown-in-expressjs-using-lightship-0599d26e7265 | article | 30 min | Intermediate | Production-grade health monitoring and graceful shutdown using Lightship with Express.js. |
| A Practical Guide to Graceful Shutdown in Node.js (Galaxy Cloud) | https://blog.galaxycloud.app/a-practical-guide-to-graceful-shutdown-in-node-js-applications/ | article | 25 min | Intermediate | Covers SIGINT/SIGTERM handling, connection draining, and production best practices for graceful shutdown. |
| Graceful Shutdown of Node.js Express for Zero-Downtime Deployments (Medium) | https://blaipratdesaba.com/graceful-shutdown-of-node-js-express-applications-for-zero-downtime-deployments-31c2a3c32467 | article | 25 min | Intermediate | Preparing Express servers for zero-downtime deployments with proper shutdown handling. |
| Don't Just Pull the Plug: Art of Graceful Shutdown in Node.js (NodeVibe) | https://nodevibe.substack.com/p/dont-just-pull-the-plug-the-art-of | article | 20 min | Beginner | Explains why graceful shutdown is essential and how to implement it to prevent data loss. |
| NodeJS Graceful Shutdown: A Beginner's Guide (DEV) | https://dev.to/yusadolat/nodejs-graceful-shutdown-a-beginners-guide-40b6 | article | 15 min | Beginner | Beginner-friendly introduction to graceful shutdown concepts and implementation in Node.js. |
| Circuit Breaker Pattern in Node.js with Opossum (Medium) | https://osvaldo-gonzalez-venegas.medium.com/circuit-breaker-pattern-in-nodejs-example-with-opossum-a3ef7bd1f512 | article | 25 min | Intermediate | Explains the circuit breaker design pattern with practical Opossum implementation examples. |
| Getting Started with Opossum in Node.js (piresfernando) | https://piresfernando.com/blog/node-opossum | article | 20 min | Beginner | Introduction to Opossum circuit breaker library for improving application resilience. |
| Circuit Breaker Pattern in Node.js (Medium/Tech Tonic) | https://medium.com/deno-the-complete-reference/circuit-breaker-pattern-in-node-js-a61fe2c4f2a4 | article | 25 min | Intermediate | Practical field guide to using the circuit breaker pattern with the Opossum library in Node.js. |
| Implementing Circuit Breaker Pattern in Node.js (ReadMedium) | https://readmedium.com/implementing-the-circuit-breaker-pattern-in-node-js-a-comprehensive-guide-8868441a3cd5 | article | 30 min | Intermediate | Comprehensive guide with real-world use cases and step-by-step Opossum implementation tutorial. |
| Graceful Shutdown with Node.js and Kubernetes (RisingStack) | https://blog.risingstack.com/graceful-shutdown-node-js-kubernetes/ | article | 25 min | Intermediate | Explains graceful shutdown benefits and implementation for Node.js applications running on Kubernetes. |
| Implementing Graceful Shutdown in Node.js with Kubernetes (piresfernando) | https://piresfernando.com/blog/graceful-shutdown-node | article | 25 min | Intermediate | Ensuring reliable and smooth rolling updates for Node.js applications on Kubernetes. |
| Add Health Checks - Kube by Example (Red Hat) | https://kubebyexample.com/learning-paths/developing-nodejs/add-health-checks | article | 20 min | Beginner | Red Hat learning path for adding HTTP-based health checks to Node.js applications on OpenShift/Kubernetes. |
| Kubernetes Health Probes Explained (k8s.guide) | https://www.k8s.guide/configuration/probes/ | article | 20 min | Beginner | Clear explanation of how Kubernetes health probes work and how to design them correctly. |

### 3.4 GitHub Repositories & Examples

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| tesfa27/kubernetes-demo | https://github.com/tesfa27/kubernetes-demo | repo | 1 hr | Beginner | Node.js Express API with Kubernetes deployment, Docker containerization, 2-replica setup, readiness/liveness probes, and service discovery. |
| neurocode-io/k8s-graceful-shutdown | https://awesome.ecosyste.ms/projects/github.com%2Fneurocode-io%2Fk8s-graceful-shutdown | repo | 30 min | Intermediate | Library providing resources to implement graceful shutdown with Kubernetes for Node.js applications. |
| Opossum Documentation | https://nodeshift.dev/opossum/ | docs | 30 min | Intermediate | Complete API documentation for the Opossum circuit breaker library with configuration options and examples. |
| Terminus on Ts.ED | https://tsed.dev/tutorials/terminus.html | docs | 20 min | Intermediate | Using Terminus with Express.js/Koa.js, TypeScript, and the Ts.ED framework for health checks and graceful shutdown. |

---

## Recommended Learning Path

### Week 1-2: Error Tracking with Sentry
1. Read the [Sentry Node.js SDK Guide](https://docs.sentry.io/platforms/javascript/guides/node/) (1-2 hrs)
2. Follow the [freeCodeCamp Sentry + TypeScript tutorial](https://www.freecodecamp.org/news/how-to-add-sentry-to-your-node-js-project-with-typescript/) (30 min)
3. Set up source maps using the [official TypeScript guide](https://docs.sentry.io/platforms/javascript/guides/node/sourcemaps/uploading/typescript/) (30 min)
4. Watch [Sentry 101: Error Monitoring](https://www.youtube.com/watch?v=DzhVEK65eYg) (25 min)
5. Explore the [ts-node-sentry-example](https://github.com/AlbertHernandez/ts-node-sentry-example) repo (30 min)
6. Read [Error Handling Best Practices](https://www.meerako.com/blogs/error-handling-logging-best-practices-nodejs-sentry) (30 min)

### Week 3-4: APM Tools & Distributed Tracing
1. Complete the [OpenTelemetry Node.js Getting Started](https://opentelemetry.io/docs/languages/js/getting-started/nodejs/) tutorial (1 hr)
2. Follow the [BetterStack OpenTelemetry Tracing Guide](https://betterstack.com/community/guides/observability/opentelemetry-nodejs-tracing/) (1.5 hrs)
3. Read the [APM Tools Comparison (Last9)](https://last9.io/blog/apm-tools-for-node-js-performance-monitoring/) (40 min)
4. Learn flame graphs from the [Node.js official guide](https://nodejs.org/en/learn/diagnostics/flame-graphs) (30 min)
5. Explore the [opentelemetry-js](https://github.com/open-telemetry/opentelemetry-js) repository examples (2-3 hrs)
6. Watch [APM for Node.js Microservices](https://www.youtube.com/watch?v=PlXfkoLfZbU) (30 min)

### Week 5-6: Health Checks, Graceful Shutdown & Resilience
1. Read the [Express Health Checks Guide](https://expressjs.com/en/advanced/healthcheck-graceful-shutdown.html) (30 min)
2. Implement Terminus using the [godaddy/terminus](https://github.com/godaddy/terminus) examples (1 hr)
3. Study [Kubernetes Probes Configuration](https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-startup-probes/) (45 min)
4. Follow the [Lightship implementation guide](https://medium.com/node-depths/implement-health-checks-and-graceful-shutdown-in-expressjs-using-lightship-0599d26e7265) (30 min)
5. Implement circuit breakers with [Opossum](https://github.com/nodeshift/opossum) (1 hr)
6. Read [Graceful Shutdown with Kubernetes](https://blog.risingstack.com/graceful-shutdown-node-js-kubernetes/) (25 min)
7. Deploy the [kubernetes-demo](https://github.com/tesfa27/kubernetes-demo) example project (1 hr)

---

