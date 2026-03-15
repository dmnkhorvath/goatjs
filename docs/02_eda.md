# Event-Driven Architecture (EDA) with Node.js & TypeScript
## Comprehensive Learning Resources Guide

*Compiled: March 2026 | 120+ curated resources across 12 topic areas*

---

## Table of Contents
1. [Official Documentation](#1-official-documentation)
2. [Written Tutorials & Articles](#2-written-tutorials--articles)
3. [Online Courses](#3-online-courses)
4. [YouTube Videos & Playlists](#4-youtube-videos--playlists)
5. [Books](#5-books)
6. [GitHub Repositories](#6-github-repositories)
7. [Tools & Frameworks](#7-tools--frameworks)

---

## 1. Official Documentation

### Node.js Core

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Node.js Events API (EventEmitter) | https://nodejs.org/api/events.html | Official Docs | 1-2 hrs | Beginner | Complete API reference for the `events` module and `EventEmitter` class — the foundation of Node.js event-driven architecture. |
| The Node.js Event Emitter (Learn Guide) | https://nodejs.org/en/learn/asynchronous-work/the-nodejs-event-emitter | Official Guide | 30 min | Beginner | Official Node.js learning guide explaining EventEmitter basics, custom events, and how the event system underpins Node.js architecture. |
| Node.js Architecture (W3Schools) | https://www.w3schools.com/nodejs/nodejs_architecture.asp | Reference | 20 min | Beginner | Overview of Node.js single-threaded, event-driven, non-blocking architecture with diagrams. |

### NestJS

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| NestJS CQRS Module | https://docs.nestjs.com/recipes/cqrs | Official Docs | 1 hr | Intermediate | Official NestJS documentation for the `@nestjs/cqrs` module covering commands, queries, events, and sagas. |
| NestJS Microservices Overview | https://docs.nestjs.com/microservices/basics | Official Docs | 2 hrs | Intermediate | Official guide to building microservices with NestJS, covering transport layers (TCP, Redis, NATS, Kafka, RabbitMQ, gRPC). |
| NestJS NATS Microservice | https://docs.nestjs.com/microservices/nats | Official Docs | 45 min | Intermediate | Official guide for integrating NATS messaging system with NestJS microservices. |
| NestJS Events (Event Emitter) | https://docs.nestjs.com/techniques/events | Official Docs | 30 min | Beginner | Official guide for the `@nestjs/event-emitter` package for in-process event handling. |

### Message Brokers

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| RabbitMQ JavaScript Tutorials | https://www.rabbitmq.com/tutorials/tutorial-one-javascript | Official Docs | 3 hrs | Beginner | Official RabbitMQ tutorials using `amqplib` for Node.js — covers Hello World, Work Queues, Pub/Sub, Routing, Topics, and RPC patterns. |
| KafkaJS Documentation | https://kafka.js.org/ | Official Docs | 2-3 hrs | Intermediate | Official docs for KafkaJS, the most popular Apache Kafka client for Node.js. Covers producers, consumers, admin API, and configuration. |
| NATS JetStream Documentation | https://docs.nats.io/nats-concepts/jetstream | Official Docs | 2 hrs | Intermediate | Official NATS docs for JetStream — persistent messaging, streams, consumers, and exactly-once delivery semantics. |
| BullMQ Documentation | https://docs.bullmq.io/ | Official Docs | 2 hrs | Beginner | Official BullMQ docs — Redis-based job queue for Node.js with TypeScript support, covering queues, workers, flows, and events. |
| ioredis GitHub (Redis Client) | https://github.com/redis/ioredis | Official Docs | 1 hr | Beginner | Official ioredis documentation — high-performance Redis client for Node.js with built-in Pub/Sub support. |
| AsyncAPI Specification | https://www.asyncapi.com/ | Official Docs | 2 hrs | Intermediate | Industry standard for defining event-driven APIs. Provides tools for documenting, validating, and generating code for async message-based architectures. |
| AsyncAPI Event-Driven Architecture Tutorial | https://www.asyncapi.com/docs/tutorials/getting-started/event-driven-architectures | Official Guide | 45 min | Beginner | Official AsyncAPI tutorial explaining EDA concepts and how AsyncAPI helps define event-driven systems. |

### Cloud Providers

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| AWS: Transitioning to Event-Driven Architecture | https://docs.aws.amazon.com/serverless/latest/devguide/serverless-transition.html | Official Docs | 1 hr | Intermediate | AWS official guide on transitioning from traditional to event-driven architecture in serverless contexts. |
| AWS: Creating Event-Driven Architectures with Lambda | https://docs.aws.amazon.com/lambda/latest/dg/concepts-event-driven-architectures.html | Official Docs | 45 min | Intermediate | AWS Lambda documentation on event-driven design patterns and how Lambda fits into EDA paradigms. |
| AWS: Best Practices for EDA | https://aws.amazon.com/blogs/architecture/best-practices-for-implementing-event-driven-architectures-in-your-organization/ | Blog | 30 min | Intermediate | AWS Architecture Blog post on EDA best practices including event design, error handling, and organizational patterns. |

---

## 2. Written Tutorials & Articles

### EDA Fundamentals

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Event-Based Architectures in JavaScript: A Handbook for Devs | https://www.freecodecamp.org/news/event-based-architectures-in-javascript-a-handbook-for-devs/ | Article | 1.5 hrs | Beginner-Intermediate | Comprehensive freeCodeCamp handbook covering EventEmitter, Pub/Sub, message brokers, and building event-driven systems in JavaScript. |
| Understanding Event-Driven Architecture with Node.js and TypeScript | https://javascript.plainenglish.io/event-driven-architecture-with-nodejs-and-typescript-d14208452321 | Article | 30 min | Intermediate | Explains how to model event-driven applications in Node.js with TypeScript generics and type-safe event handling. |
| Implementing Event-Driven Architecture in TypeScript with Node.js and Express | https://medium.com/@elijahbanjo/implementing-event-driven-architecture-in-typescript-with-node-js-and-express-eefecadaf95f | Article | 25 min | Beginner | Practical guide implementing EDA with Express.js, focusing on single responsibility and decoupled event handlers. |
| Event-Driven Architecture in Node.js (DEV Community) | https://dev.to/learn-to-earn/event-driven-architecture-in-nodejs-1o98 | Article | 20 min | Beginner | Overview of EDA in Node.js covering core concepts, benefits, and implementation patterns. |
| Event-Driven Architecture in JavaScript: A 2025 Deep Dive | https://dev.to/hamzakhan/event-driven-architecture-in-javascript-applications-a-2025-deep-dive-4b8g | Article | 35 min | Intermediate | Modern deep dive into EDA patterns for both frontend and backend JavaScript applications. |
| Implementing Event-Driven Systems in TypeScript | https://softwarepatternslexicon.com/patterns-ts/7/5/1/ | Article | 45 min | Intermediate | Comprehensive guide to building event-driven systems using TypeScript, Node.js EventEmitter, and message brokers (RabbitMQ, Kafka, Redis). |
| Building Type-Safe Event-Driven Applications in TypeScript using Pub/Sub | https://dev.to/encore/building-type-safe-event-driven-applications-in-typescript-using-pubsub-cron-jobs-and-postgresql-50jc | Article | 40 min | Intermediate | Walks through creating a type-safe event-driven Node.js app with Pub/Sub, including local development and cloud deployment. |
| Introduction to Event-Driven Architecture in Node.js TypeScript (ABACUS) | https://medium.com/scb-abacus/introduction-to-event-driven-architecture-in-node-js-typescript-354302bc055c | Article | 25 min | Beginner | Introduction to EDA patterns with practical Node.js TypeScript examples from a fintech perspective. |

### Node.js EventEmitter Deep Dive

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Mastering Events in Node.js and TypeScript | https://mehranjnf.medium.com/mastering-events-in-node-js-and-typescript-839e51d47985 | Article | 30 min | Intermediate | Deep dive into Node.js events with TypeScript, covering custom event emitters, real-world patterns, and advanced usage. |
| Event Emitter with TypeScript — Advanced Usage | https://dev.to/ritikbanger/event-emitter-with-typescript-advanced-usage-328c | Article | 20 min | Intermediate | Advanced EventEmitter patterns in TypeScript including typed events, React integration, and decoupled component communication. |
| Mastering EventEmitter in TypeScript | https://www.xjavascript.com/blog/eventemitter-typescript/ | Article | 25 min | Intermediate | Comprehensive guide to implementing type-safe EventEmitter patterns in TypeScript with generics. |
| Creating a TypeScript Custom Event Emitter | https://www.webdevtutor.net/blog/typescript-custom-event-emitter | Article | 20 min | Beginner | Step-by-step guide to building a custom, type-safe event emitter from scratch in TypeScript. |
| Mastering the Event Emitter Pattern: A JavaScript Interview Essential | https://javascript.plainenglish.io/mastering-the-event-emitter-pattern-a-javascript-interview-essential-07efd5b48ea2 | Article | 15 min | Beginner | Covers the EventEmitter pattern across DOM events, Node.js, Redux, and custom systems — great for interview prep. |

### CQRS & Event Sourcing

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Straightforward Event Sourcing with TypeScript and NodeJS | https://event-driven.io/en/type_script_node_js_event_sourcing/ | Article | 45 min | Intermediate | Oskar Dudycz's excellent guide showing Event Sourcing doesn't have to be complex — practical TypeScript/Node.js examples with union types. |
| CQRS From Scratch With TypeScript | https://medium.com/swlh/cqrs-from-scratch-with-typescript-e2ccf7fc2b64 | Article | 35 min | Intermediate | Hands-on implementation of the CQRS pattern from scratch using Node.js and TypeScript. |
| Mastering Event Sourcing and CQRS with a Hero Adventure Game (Node.js/TS) | https://javascript.plainenglish.io/mastering-event-sourcing-and-cqrs-with-a-hero-adventure-game-example-in-node-js-and-typescript-b321fa9717ab | Article | 40 min | Intermediate | Fun, practical walkthrough of Event Sourcing and CQRS using a hero game example in Node.js/TypeScript. |
| Implement Event Sourcing and CQRS in Node.js (Bitovi) | https://www.bitovi.com/blog/implementing-event-sourcing-cqrs-in-node.js | Article | 35 min | Intermediate | Detailed implementation guide covering commands, command handlers, event stores, and projections in Node.js. |
| How to Build Event Sourcing Systems in Node.js (OneUptime) | https://oneuptime.com/blog/post/2026-01-26-nodejs-event-sourcing/view | Article | 40 min | Intermediate | Covers event stores, aggregates, projections, snapshots, and CQRS patterns with practical TypeScript examples. |
| CQRS Pattern in NestJS (DEV Community) | https://dev.to/jacobandrewsky/cqrs-pattern-in-nestjs-4n3p | Article | 30 min | Intermediate | Explains CQRS concepts and implementation using the `@nestjs/cqrs` module with real-world examples. |
| Building Modular, Event-Driven Microservices with CQRS in NestJS | https://waqarilyas.dev/blog/07-modular-event-driven-microservice-with-cqrs/ | Article | 40 min | Intermediate | Full working example of modular microservices with CQRS and Redis for event-driven communication in NestJS. |
| Microservices with CQRS and Event Sourcing in TypeScript with NestJS | https://blog.bitsrc.io/microservices-with-cqrs-and-event-sourcing-in-typescript-with-nestjs-831fba1e068b | Article | 45 min | Advanced | Advanced guide to building microservices combining CQRS and Event Sourcing patterns with NestJS. |
| Introduction to Event Sourcing — Self-Paced Kit (Oskar Dudycz) | https://event-driven.io/en/introduction_to_event_sourcing/ | Workshop | 4-6 hrs | Beginner-Intermediate | Open-source self-paced workshop by Oskar Dudycz covering Event Sourcing fundamentals with exercises in Node.js/TypeScript. |

### Message Brokers

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Mastering Message Queues in Node.js: RabbitMQ, Kafka, and BullMQ | https://javascript.plainenglish.io/mastering-message-queues-in-node-js-a-deep-dive-into-rabbitmq-kafka-and-bullmq-1e39214746eb | Article | 40 min | Intermediate | Comprehensive comparison of RabbitMQ, Kafka, and BullMQ in Node.js with use cases and implementation examples. |
| Kafka vs. RabbitMQ: Comparing Node.js Message Brokers (LogRocket) | https://blog.logrocket.com/kafka-vs-rabbitmq-comparing-node-js-message-brokers/ | Article | 30 min | Intermediate | In-depth comparison of Kafka and RabbitMQ covering architecture, message retention, performance, and Node.js integration. |
| Event-Driven Architecture with Node.js and Kafka: A Complete Setup | https://medium.com/lets-code-future/event-driven-architecture-with-node-js-and-kafka-a-complete-setup-11873d9d7f4d | Article | 35 min | Intermediate | Step-by-step guide to setting up Kafka with Node.js for event-driven microservices. |
| Using Apache Kafka with Node.js: Building Event-Driven Applications | https://dev.to/limaleandro1999/using-apache-kafka-with-nodejs-a-tutorial-on-building-event-driven-applications-1img | Article | 30 min | Beginner | Beginner-friendly tutorial on using Kafka with Node.js to create event-driven applications. |
| Getting Started with RabbitMQ in Node.js & TypeScript | https://dev.to/harshit_bhardwaj_37bd0c14/getting-started-with-rabbitmq-in-nodejs-typescript-16km | Article | 25 min | Beginner | Covers RabbitMQ basics with amqplib in TypeScript — message acknowledgment, retry mechanisms, and dead-letter queues. |
| Using RabbitMQ with NodeJS (Don't Panic Labs) | https://dontpaniclabs.com/blog/post/2024/04/04/using-rabbitmq-with-nodejs/ | Article | 20 min | Beginner | Practical guide to writing messages to RabbitMQ queues using Node.js with TypeScript. |
| Mastering amqplib with TypeScript | https://www.xjavascript.com/blog/amqplib-typescript/ | Article | 30 min | Intermediate | Detailed guide to using amqplib (AMQP client) with TypeScript for RabbitMQ integration. |
| Using Redis Pub/Sub with Node.js (LogRocket) | https://blog.logrocket.com/using-redis-pub-sub-node-js/ | Article | 25 min | Beginner | Explains the Pub/Sub pattern and implementation in Node.js using Redis with practical alternatives. |
| How to Use Redis Pub/Sub with Node.js (OneUptime) | https://oneuptime.com/blog/post/2026-01-25-redis-pubsub-nodejs/view | Article | 30 min | Beginner | Covers real-time messaging patterns for chat systems, notifications, and event broadcasting with Redis Pub/Sub. |
| Redis and Node.js with TypeScript: A Complete Guide | https://medium.com/@erickzanetti/redis-and-node-js-with-typescript-a-complete-guide-2bac6e300497 | Article | 35 min | Intermediate | Comprehensive guide covering Redis caching, Pub/Sub, and Streams with TypeScript. |
| How to Use NATS with Node.js (OneUptime) | https://oneuptime.com/blog/post/2026-02-02-nats-nodejs/view | Article | 30 min | Beginner | Covers publish-subscribe, request-reply, JetStream persistence, and production best practices with NATS and Node.js. |
| Event-Driven Systems with NATS and JetStream | https://james-carr.org/posts/2026-01-21-nats-jetstream-building-reliable-messaging/ | Article | 35 min | Intermediate | Hands-on TypeScript project exploring NATS JetStream for persistent messaging — streams, consumers, and reliability analysis. |
| Build High-Performance Event-Driven Microservices with Fastify, NATS JetStream, and TypeScript | https://js.elitedev.in/js/build-high-performance-event-driven-microservices-with-fastify-nats-jetstream-and-typescript-a1bd3117/ | Article | 40 min | Intermediate | Combines Fastify with NATS JetStream for high-performance event-driven microservices in TypeScript. |
| BullMQ for Beginners: A Friendly, Practical Guide (with TypeScript) | https://hadoan.medium.com/bullmq-for-beginners-a-friendly-practical-guide-with-typescript-examples-eb8064bef1c4 | Article | 25 min | Beginner | Beginner-friendly guide to BullMQ with mental models, minimal setup, and copy-paste TypeScript snippets. |
| Mastering BullMQ with TypeScript: A Comprehensive Guide | https://www.xjavascript.com/blog/bullmq-typescript/ | Article | 35 min | Intermediate | Detailed overview of creating and managing type-safe task queues with BullMQ and TypeScript. |
| Event-Driven Microservices: Kafka, RabbitMQ, NATS | https://dasroot.net/posts/2026/01/event-driven-microservices-kafka-rabbitmq-nats/ | Article | 40 min | Advanced | Technical comparison of Kafka 3.4, RabbitMQ 3.10, and NATS 2.9 focusing on performance, reliability, and trade-offs. |

### Saga Pattern

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Implementing Saga Pattern in Microservices with Node.js | https://blog.bitsrc.io/implementing-saga-pattern-in-a-microservices-with-node-js-aa2faddafac3 | Article | 30 min | Intermediate | Explains the Saga Pattern for managing distributed transactions with practical Node.js implementation. |
| The Saga Pattern Unleashed: Deep Dive with TypeScript | https://kisztof.medium.com/the-saga-pattern-unleashed-a-deep-dive-into-distributed-transactions-with-typescript-f7ee55d53e2d | Article | 35 min | Intermediate | Deep dive into Saga Pattern principles with real-world TypeScript code examples for distributed systems. |
| Implement Saga Patterns in Microservices with NestJS and Kafka | https://thenewstack.io/implement-saga-patterns-in-microservices-with-nestjs-and-kafka/ | Article | 40 min | Advanced | Guide to implementing the Saga pattern using NestJS, Kafka, and TypeScript for distributed transaction management. |
| How to Implement Saga Pattern in Node.js (OneUptime) | https://oneuptime.com/blog/post/2026-01-26-saga-pattern-nodejs/view | Article | 30 min | Intermediate | Covers Saga pattern implementation with compensation logic for managing distributed transactions across microservices. |
| Node.js Durable Execution with Temporal + TS: Saga Patterns | https://medium.com/@kaushalsinh73/node-js-durable-execution-with-temporal-ts-saga-patterns-without-orchestration-chaos-249132ccf609 | Article | 30 min | Advanced | Practical Saga implementation using Temporal's durable execution framework with TypeScript. |
| Saga Design Pattern (Microsoft Azure) | https://learn.microsoft.com/en-us/azure/architecture/patterns/saga | Reference | 20 min | Intermediate | Microsoft's authoritative reference on the Saga pattern for distributed transactions in microservices. |
| Pattern: Saga (Microservices.io) | https://microservices.io/patterns/data/saga.html | Reference | 15 min | Intermediate | Chris Richardson's canonical pattern description — the definitive reference for the Saga pattern. |

### Serverless EDA

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Mastering Serverless and Event-Driven Architectures with AWS | https://dev.to/aws-builders/mastering-serverless-and-event-driven-architectures-with-aws-innovations-in-lambda-eventbridge-519h | Article | 35 min | Intermediate | Explores AWS Lambda, EventBridge, and supporting services for building resilient, real-time serverless applications. |
| Building a Serverless Event-Driven Architecture with AWS | https://medium.com/@FAANG/building-a-serverless-event-driven-architecture-with-aws-a-complete-guide-4ba0bde545a0 | Article | 40 min | Intermediate | Complete guide to building practical event-driven applications with AWS serverless services. |
| Event-Driven Serverless Systems with AWS EventBridge and Lambda | https://aws.plainenglish.io/event-driven-serverless-systems-with-aws-eventbridge-and-lambda-5049ee65fa87 | Article | 30 min | Intermediate | Practical guide to building a fully event-driven, serverless system on AWS with EventBridge and Lambda. |
| Building Event-Driven Microservices with AWS Lambda and EventBridge | https://medium.com/@tito_shreyansh/building-event-driven-microservices-with-aws-lambda-and-eventbridge-aa607768453f | Article | 30 min | Intermediate | Architecture, implementation, and operational considerations for event-driven microservices with AWS. |

### WebSockets & Real-Time

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Real-Time Communication with WebSockets and Socket.IO in Node.js | https://dev.to/imsushant12/real-time-communication-with-websockets-and-socketio-in-nodejs-4p8e | Article | 30 min | Beginner | Covers WebSocket fundamentals and Socket.IO features including auto-reconnection and broadcasting. |
| Getting Started with WebSockets in TypeScript | https://blog.stackademic.com/getting-started-with-websockets-in-typescript-c48c5519f7d4 | Article | 25 min | Beginner | Practical introduction to implementing WebSockets in TypeScript with a chat application example. |
| WebSockets and Real-Time Communication in Node.js (SystemsArchitect.io) | https://www.systemsarchitect.io/docs/guides/nodejs-ts/web-sockets-realtime | Guide | 1 hr | Intermediate | Comprehensive guide covering 12 aspects of WebSocket implementation in Node.js with TypeScript. |
| Real-Time WebSockets Node.js: The Complete Guide | https://www.nordiso.com/blog/real-time-websockets-node-js-the-complete-guide | Article | 45 min | Intermediate | Complete guide to real-time WebSocket development with Node.js covering persistent connections and high-concurrency patterns. |
| Scaling Pub/Sub with WebSockets and Redis | https://ably.com/blog/scaling-pub-sub-with-websockets-and-redis | Article | 25 min | Advanced | Architecture patterns for scaling WebSocket Pub/Sub systems using Redis as the distribution layer. |

### Event Schema Design & Versioning

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Event Versioning Strategies for Event-Driven Architectures | https://theburningmonk.com/2025/04/event-versioning-strategies-for-event-driven-architectures/ | Article | 30 min | Advanced | Yan Cui's guide to event versioning approaches, pros/cons, and safely evolving schemas without breaking consumers. |
| AsyncAPI-First Design for Event-Driven Architectures (Academic Paper) | https://repositorio-aberto.up.pt/bitstream/10216/161041/2/682110.pdf | Paper | 1 hr | Advanced | Academic paper on using AsyncAPI specification for designing and validating event-driven architectures. |

### Testing Event-Driven Systems

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Testing Event-Driven Architectures in Node.js | https://article.arunangshudas.com/testing-event-driven-architectures-in-node-js-ea0660e3bd55 | Article | 30 min | Intermediate | Systematic approach to unit, integration, and E2E testing for event-driven Node.js systems. |
| Node.js Testing Best Practices (Goldbergyoni) | https://github.com/goldbergyoni/nodejs-testing-best-practices | Guide/Repo | 3 hrs | Intermediate | 50+ best practices for modern Node.js testing including event-driven patterns, message queue testing, and database interactions. |
| Tao of Node — Design, Architecture & Best Practices | https://alexkondov.com/tao-of-node/ | Article | 1 hr | Intermediate | Comprehensive guide to Node.js design patterns and best practices including event-driven architecture testing strategies. |

### NestJS Event-Driven

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Building Event-Driven Architecture with NestJS and TypeScript | https://medium.com/@sylvesterranjithfrancis/building-event-driven-architecture-with-nestjs-and-typescript-b183a3730185 | Article | 35 min | Intermediate | Modular approach to EDA with NestJS covering observability, event handling, and module structure. |
| NestJS Event-Driven Systems (OneUptime) | https://oneuptime.com/blog/post/2026-02-02-nestjs-event-driven-systems/view | Article | 35 min | Intermediate | Covers NestJS built-in event emitter, CQRS module, and microservices capabilities for event-driven systems. |
| The CQRS & Event-Driven Combo That Supercharged My NestJS App | https://medium.com/@hadiyolworld007/the-cqrs-event-driven-combo-that-supercharged-my-nestjs-app-ddc4d65ba59a | Article | 25 min | Intermediate | Real-world experience combining CQRS with event-driven architecture in NestJS for improved scalability. |
| Building NestJS Applications Following the CQRS Model (Telerik) | https://www.telerik.com/blogs/building-nestjs-applications-following-the-cqrs-model | Article | 30 min | Intermediate | Detailed guide to implementing CQRS in NestJS with the `@nestjs/cqrs` module and Kafka integration. |
| Complete Event-Driven Architecture Guide: NestJS, Redis, TypeScript | https://js.elitedev.in/js/complete-event-driven-architecture-guide-nestjs-redis-typescript-implementation-with-cqrs-pattern-fab40610/ | Article | 45 min | Advanced | Comprehensive guide covering domain events, CQRS, event sourcing, and distributed systems with NestJS and Redis. |

---

## 3. Online Courses

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Event-Driven Architecture Course — NextJS, Clerk, Webhooks (freeCodeCamp) | https://www.youtube.com/watch?v=TtvytXHLAsc | Free Course (YouTube) | 3-4 hrs | Beginner-Intermediate | freeCodeCamp course by Hitesh Choudhary teaching EDA by building a modern SaaS application with Next.js, Clerk, and webhooks. |
| The Complete Microservices & Event-Driven Architecture (Udemy) | https://www.udemy.com/course/the-complete-microservices-event-driven-architecture/ | Paid Course | 15+ hrs | Intermediate-Advanced | Comprehensive Udemy course covering microservices migration, EDA patterns, CQRS, and event sourcing. |
| Event-Driven Systems, Security, and Microservices (Coursera) | https://www.coursera.org/learn/packt-event-driven-systems-security-and-microservices-0m1v3 | Course (Audit Free) | 10+ hrs | Intermediate | Hands-on experience building secure, scalable event-driven systems (primarily .NET but concepts are universal). |
| Introduction to Event Sourcing — Self-Paced Kit (Oskar Dudycz) | https://event-driven.io/en/introduction_to_event_sourcing/ | Free Workshop | 4-6 hrs | Beginner-Intermediate | Open-source self-paced workshop with exercises in Node.js/TypeScript covering Event Sourcing fundamentals. |
| Webinar: Introduction to Event Sourcing in TypeScript & NodeJS (Kurrent/EventStoreDB) | https://www.kurrent.io/webinars/introduction-to-event-sourcing-in-typescript-nodejs | Free Webinar | 1.5 hrs | Beginner | Oskar Dudycz explains Event Sourcing with practical TypeScript/NodeJS/EventStoreDB examples. |
| AWS Serverless Developer Experience Workshop (TypeScript) | https://github.com/aws-samples/aws-serverless-developer-experience-workshop-typescript | Free Workshop | 6-8 hrs | Intermediate | AWS official workshop covering SAM, serverless best practices, and applied event-driven architectures in TypeScript. |
| Designing Event-Driven Microservices (YouTube Playlist) | https://www.youtube.com/playlist?list=PLa7VYi0yPIH0IpUKXb3q7NSjpJGO9GGGZ | Free Course (YouTube) | 5+ hrs | Intermediate | Playlist covering principles of microservices and event-driven architectures for cloud-native distributed systems. |
| Master Microservices & Event-Driven Architecture (Akhil Sharma) | https://www.youtube.com/watch?v=FDjmWxETjn8 | Free Course (YouTube) | 6 hrs | Beginner-Advanced | Complete 6-hour guide from beginner to advanced covering microservices and EDA patterns. |

---

## 4. YouTube Videos & Playlists

### EDA Fundamentals

| Title | Channel | URL | Time | Level | Description |
|-------|---------|-----|------|-------|-------------|
| Event-Driven Architecture in Node.js — Deep Dive Tutorial | — | https://www.youtube.com/watch?v=7kpHmtVCt2o | 30 min | Beginner | Deep dive into EDA concepts and implementation in Node.js. |
| Understanding Event-Driven Architecture (#20) | — | https://www.youtube.com/watch?v=e7iJNY3YwDg | 20 min | Beginner | Explains what event-driven architecture means and how Node.js uses this architecture. |
| Event-Driven Architectures for Full-Stack Devs with Temporal | Temporal | https://www.youtube.com/watch?v=VuLl5qEJ3Ok | 45 min | Intermediate | Advanced workflow orchestration with Temporal's Node.js SDK (TypeScript) and React Query integration. |
| Path to Event-Driven Architecture — Start Capturing INTENT! | CodeOpinion | https://www.youtube.com/watch?v=sPjj8tVKy6M | 20 min | Intermediate | Derek Comartin explains the path to adopting EDA by capturing business intent in events. |

### CQRS & Event Sourcing

| Title | Channel | URL | Time | Level | Description |
|-------|---------|-----|------|-------|-------------|
| Introduction to Event Sourcing in TypeScript and NodeJS with EventStoreDB | Oskar Dudycz | https://www.youtube.com/watch?v=5pc7abhle_Q | 1.5 hrs | Intermediate | Practical examples using TypeScript, NodeJS, and EventStoreDB with CQRS and DDD concepts. |
| Practical Introduction to Event Sourcing with Emmett | Oskar Dudycz | https://www.youtube.com/watch?v=SDXdcymKv-8 | 1 hr | Intermediate | Introduction to Event Sourcing using the Emmett framework for Node.js. |
| Domain-Driven Design with CQRS and Event Sourcing (Hacklunch) | Hacklunch | https://www.youtube.com/watch?v=bYH2yupPVIc | 45 min | Intermediate | Starts with a basic Node.js CRUD service and gradually applies Event Sourcing and CQRS with DDD principles. |
| Understanding Event-Sourcing, CQRS, and Implementing an Event Bus | — | https://www.youtube.com/watch?v=LrqFUeSkikc | 30 min | Intermediate | Designing an Event Bus in Node.js with TypeScript while implementing Event-Sourcing and CQRS. |
| CQRS & Event Sourcing Code Walk-Through | CodeOpinion | https://www.youtube.com/watch?v=5aznkIEvkKc | 20 min | Intermediate | Code walkthrough showing commands, domain events, event store, and projections working together. |
| Event Sourcing Example & Explained in Plain English | CodeOpinion | https://www.youtube.com/watch?v=AUj4M-st3ic | 15 min | Beginner | Clear explanation of Event Sourcing with practical examples — great starting point. |
| Event Sourcing and CQRS Explained — When Should You Use Them? | CodeOpinion | https://www.youtube.com/watch?v=p0wimdpCNGk | 20 min | Beginner | Overview of when and why to use Event Sourcing and CQRS together. |
| Master Event Sourcing in Just 10 Minutes | — | https://www.youtube.com/watch?v=ID-_ic1fLkY | 10 min | Beginner | Quick introduction to Event Sourcing as an architectural pattern for capturing state changes. |
| Event Sourcing Core Concepts | CodeOpinion | https://www.youtube.com/watch?v=HKspPiCGE2E | 20 min | Beginner | Core concepts of Event Sourcing explained clearly by Derek Comartin. |
| Matt Walters — How to CQRS in Node: Eventually Consistent Systems | Node.js Meetup | https://www.youtube.com/watch?v=4k7bLtqXb8c | 40 min | Advanced | Conference talk on building eventually consistent, unidirectional systems with CQRS in Node.js microservices. |
| NestJS CQRS: Commands, Queries, Events & Saga | — | https://www.youtube.com/watch?v=akTfrZhHc5Y | 30 min | Intermediate | NestJS advanced course covering the full CQRS module with commands, queries, events, and sagas. |
| Greg Young Answers Your Event Sourcing Questions! | CodeOpinion | https://www.youtube.com/watch?v=LGjRfgsumPk | 45 min | Advanced | Q&A with Greg Young (creator of Event Sourcing/CQRS) covering frameworks, legacy systems, projections, and more. |

### Microservices & Message Brokers

| Title | Channel | URL | Time | Level | Description |
|-------|---------|-----|------|-------|-------------|
| Kafka + Microservices + Event-Driven Architecture with NodeJS | — | https://www.youtube.com/watch?v=wdsiQEa5mQY | 45 min | Intermediate | Tutorial on using Kafka for inter-microservice communication and event passing between containers. |
| Event-Driven Microservices in Node.js with RabbitMQ | — | https://www.youtube.com/watch?v=FmV6onGR-_o | 40 min | Intermediate | Advanced tutorial building a complete event-driven microservices architecture with Node.js and RabbitMQ. |
| MicroServices, RabbitMQ, CQRS and Event Sourcing with Node | — | https://www.youtube.com/watch?v=XrkNwwVLyOY | 30 min | Intermediate | Showcases how CQRS and Event Sourcing work together with RabbitMQ in a Node.js microservices context. |
| Microservice Pub/Sub Communication Using NATS | — | https://www.youtube.com/watch?v=FugnvZs012Y | 25 min | Intermediate | Demonstrates establishing Pub/Sub communication between services using NATS and TypeScript. |
| Microservices Event-Driven Design Architecture (#17) | — | https://www.youtube.com/watch?v=z0ePqAtMAZg | 20 min | Beginner | Overview of event-driven design patterns for microservices communication. |
| Node JS Full Course 2025 — Microservices, Redis, CI/CD | — | https://www.youtube.com/watch?v=_f7h6xQXiLA | 10 hrs | Beginner-Advanced | Comprehensive Node.js course covering microservices, Redis, and CI/CD with event-driven patterns. |

### Playlists

| Title | Channel | URL | Time | Level | Description |
|-------|---------|-----|------|-------|-------------|
| Complete NodeJS Microservices Architecture Course | — | https://www.youtube.com/playlist?list=PLXXI5Oe3aCLn0VnQplrXfMKd2ApvQ6LQq | 10+ hrs | Intermediate | Full playlist covering microservices architecture with Docker and Kubernetes for production-ready applications. |
| Mastering Node.js Microservices with Kafka | — | https://www.youtube.com/playlist?list=PLaLqLOj2bk9aaZZYoH7tMDj5obE7os45_ | 5+ hrs | Intermediate | Covers Clean Architecture, Kafka in Node.js, Elastic Search, Prisma ORM, and test coverage. |
| Designing Event-Driven Microservices | — | https://www.youtube.com/playlist?list=PLa7VYi0yPIH0IpUKXb3q7NSjpJGO9GGGZ | 5+ hrs | Intermediate | Principles of microservices and event-driven architectures for cloud-native distributed systems. |
| CodeOpinion Channel (Derek Comartin) | CodeOpinion | https://www.youtube.com/@CodeOpinion | Ongoing | All Levels | Prolific channel focused on Software Architecture, CQRS, Event Sourcing, Messaging, and HTTP APIs. |

---

## 5. Books

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Building Event-Driven Microservices (Adam Bellemare, O'Reilly) | https://cdn.bookey.app/files/pdf/book/en/building-event-driven-microservices.pdf | Book (Free PDF) | 15-20 hrs | Intermediate-Advanced | The definitive guide to event-driven microservices — covers event-driven architecture, event sourcing, CQRS, and real-time data utilization. |
| Practical Microservices: Build Event-Driven Architectures with Event Sourcing and CQRS | https://dokumen.pub/practical-microservices-build-event-driven-architectures-with-event-sourcing-and-cqrs-1680506455-9781680506457.html | Book | 12-15 hrs | Intermediate | Hands-on guide to building event-driven microservices with Event Sourcing and CQRS — uses JavaScript/Node.js examples. |
| Event-Driven Architectures for Microservices: A Framework for Scalable Systems (Academic Paper) | https://www.ijsat.org/papers/2025/1/2498.pdf | Paper (Free PDF) | 2 hrs | Advanced | Academic framework for migrating from monolithic to event-driven microservices with implementation strategies and case studies. |
| Exploring Event-Driven Architecture in Microservices: Patterns, Pitfalls, and Best Practices | https://www.researchgate.net/publication/388709044_Exploring_event-driven_architecture_in_microservices-_patterns_pitfalls_and_best_practices | Paper (Free) | 1.5 hrs | Advanced | Academic paper dissecting Pub/Sub, Event Sourcing, and Saga patterns with best practices. |
| Event-Driven by Oskar Dudycz (Blog/Book) | https://event-driven.io/en/ | Blog/Resource | Ongoing | All Levels | Oskar Dudycz's comprehensive blog on Event Sourcing, CQRS, and event-driven architectures with practical Node.js/TypeScript content. |
| Architecture Weekly Newsletter (Oskar Dudycz) | https://www.architecture-weekly.com/ | Newsletter | Weekly | All Levels | Weekly curated newsletter on software architecture, Event Sourcing, CQRS, and distributed systems. |

### Recommended Paid Books

| Title | Author | Level | Description |
|-------|--------|-------|-------------|
| Building Event-Driven Microservices, 2nd Edition | Adam Bellemare (O'Reilly) | Intermediate-Advanced | Updated edition of the definitive EDA guide with new patterns and real-world case studies. |
| Designing Data-Intensive Applications | Martin Kleppmann | Advanced | The "bible" of distributed systems — covers event logs, stream processing, and data architecture. |
| Enterprise Integration Patterns | Gregor Hohpe, Bobby Woolf | Advanced | Classic reference for messaging patterns — foundational knowledge for any EDA practitioner. |
| Microservices Patterns | Chris Richardson | Intermediate | Covers Saga, CQRS, Event Sourcing, and other patterns with practical examples. |
| Domain-Driven Design | Eric Evans | Advanced | The foundational text for DDD which underpins most Event Sourcing and CQRS implementations. |

---

## 6. GitHub Repositories

### Reference Implementations & Examples

| Title | URL | Stars | Level | Description |
|-------|-----|-------|-------|-------------|
| oskardudycz/EventSourcing.NodeJS | https://github.com/oskardudycz/EventSourcing.NodeJS | 1.5k+ | Intermediate | The go-to repository for Event Sourcing examples and tutorials in Node.js/TypeScript by Oskar Dudycz. Covers EventStoreDB, CQRS, and DDD. |
| event-driven-io/emmett | https://github.com/event-driven-io/emmett | 500+ | Intermediate | Opinionated yet flexible Event Sourcing framework for Node.js — focuses on composition over magic. By Oskar Dudycz. |
| bitloops/ddd-hexagonal-cqrs-es-eda | https://github.com/bitloops/ddd-hexagonal-cqrs-es-eda | 300+ | Advanced | Complete working example of DDD, Hexagonal Architecture, CQRS, Event Sourcing, and EDA using TypeScript and NestJS. |
| meysamhadeli/booking-microservices-expressjs | https://github.com/meysamhadeli/booking-microservices-expressjs | 200+ | Intermediate | Practical microservices with Node.js, CQRS, Vertical Slice Architecture, EDA, Postgres, RabbitMQ, and Express. |
| yerinadler/typescript-event-sourcing-sample-app | https://github.com/yerinadler/typescript-event-sourcing-sample-app | 100+ | Intermediate | TypeScript API implementing CQRS & Event Sourcing with Event-Carried State Transfer pattern. |
| snatalenko/node-cqrs | https://github.com/snatalenko/node-cqrs | 100+ | Intermediate | CQRS backbone with event sourcing for Node.js — provides AbstractProjection and event store abstractions. |
| rasurathore13/nestJS_design_patterns | https://github.com/rasurathore13/nestJS_design_patterns | 50+ | Advanced | Complete working example of DDD, Hexagonal Architecture, CQRS, ES, EDA, and BDD using TypeScript and NestJS. |
| mgce/modular-monolith-nodejs | https://github.com/mgce/modular-monolith-nodejs | 100+ | Intermediate | Modular monolith architecture in Node.js with event-driven communication between modules. |
| aws-samples/aws-serverless-developer-experience-workshop-typescript | https://github.com/aws-samples/aws-serverless-developer-experience-workshop-typescript | 100+ | Intermediate | AWS official workshop for serverless development with applied event-driven architectures in TypeScript. |

### Tools & Libraries

| Title | URL | Stars | Level | Description |
|-------|-----|-------|-------|-------------|
| tulios/kafkajs | https://github.com/tulios/kafkajs | 3.5k+ | Intermediate | The most popular Apache Kafka client for Node.js — dependency-free, 100% JavaScript. |
| redis/ioredis | https://github.com/redis/ioredis | 13k+ | Beginner | Robust, performance-focused Redis client for Node.js with built-in Pub/Sub support. |
| goldbergyoni/nodejs-testing-best-practices | https://github.com/goldbergyoni/nodejs-testing-best-practices | 1k+ | Intermediate | 50+ testing best practices for Node.js including event-driven system testing patterns. |
| EventEmitter2/EventEmitter2 | https://github.com/EventEmitter2/EventEmitter2 | 2k+ | Beginner | Enhanced EventEmitter with wildcard support, namespaces, and better performance than Node.js built-in. |
| conduktor/awesome-kafka | https://github.com/conduktor/awesome-kafka | 1k+ | All Levels | Curated list of awesome Apache Kafka resources, tools, libraries, and applications. |
| reimagined/resolve (reSolve) | https://reimagined.github.io/resolve/ | 700+ | Advanced | Full-stack CQRS, DDD, Event Sourcing framework for Node.js. |

### GitHub Topics to Explore

| Topic | URL | Description |
|-------|-----|-------------|
| event-driven-architecture (TypeScript) | https://github.com/topics/event-driven-architecture?l=typescript | All TypeScript EDA repositories sorted by recent updates. |
| event-driven-microservices | https://github.com/topics/event-driven-microservices | Repositories implementing event-driven microservice patterns. |
| event-sourcing (TypeScript) | https://github.com/topics/event-sourcing?l=typescript | TypeScript Event Sourcing implementations and examples. |
| cqrs (TypeScript) | https://github.com/topics/cqrs?l=typescript | TypeScript CQRS pattern implementations. |

---

## 7. Tools & Frameworks

### Message Brokers & Event Streaming

| Tool | URL | Type | Description |
|------|-----|------|-------------|
| Apache Kafka | https://kafka.apache.org/ | Event Streaming Platform | Distributed event streaming platform for high-throughput, fault-tolerant, real-time data pipelines. Industry standard for event streaming. |
| RabbitMQ | https://www.rabbitmq.com/ | Message Broker | Open-source message broker supporting AMQP, MQTT, and STOMP. Best for reliable point-to-point and pub/sub messaging. |
| NATS | https://nats.io/ | Messaging System | High-performance, cloud-native messaging system. JetStream adds persistence, exactly-once delivery, and stream processing. |
| Redis Pub/Sub | https://redis.io/docs/interact/pubsub/ | In-Memory Pub/Sub | Ultra-fast in-memory Pub/Sub for real-time messaging. Simple but lacks persistence (use Redis Streams for durability). |
| Redis Streams | https://redis.io/docs/data-types/streams/ | Event Streaming | Persistent, append-only log data structure in Redis — combines Pub/Sub simplicity with Kafka-like durability. |
| Amazon EventBridge | https://aws.amazon.com/eventbridge/ | Serverless Event Bus | AWS serverless event bus for building event-driven architectures with SaaS integrations and AWS service events. |
| Amazon SQS/SNS | https://aws.amazon.com/sqs/ | Message Queue/Pub-Sub | AWS managed message queue (SQS) and pub/sub (SNS) services for decoupled, serverless event-driven systems. |

### Node.js Libraries & Clients

| Library | URL | Type | Description |
|---------|-----|------|-------------|
| KafkaJS | https://kafka.js.org/ | Kafka Client | Modern Apache Kafka client for Node.js — dependency-free, 100% JavaScript, TypeScript support. |
| amqplib | https://www.npmjs.com/package/amqplib | RabbitMQ Client | Standard AMQP 0-9-1 client for Node.js — the primary library for RabbitMQ integration. |
| ioredis | https://github.com/redis/ioredis | Redis Client | High-performance Redis client with built-in Pub/Sub, Streams, Cluster, and Sentinel support. |
| nats.js | https://github.com/nats-io/nats.js | NATS Client | Official NATS client for Node.js/Deno/Bun with JetStream support. |
| BullMQ | https://bullmq.io/ | Job Queue | Redis-based job queue for Node.js with TypeScript support — delays, retries, scheduling, and flows. |
| Socket.IO | https://socket.io/ | WebSocket Library | Real-time bidirectional event-based communication library with auto-reconnection and broadcasting. |
| EventEmitter2 | https://github.com/EventEmitter2/EventEmitter2 | Event Emitter | Enhanced EventEmitter with wildcards, namespaces, and async support. |
| eventemitter3 | https://www.npmjs.com/package/eventemitter3 | Event Emitter | High-performance EventEmitter — one of the fastest available for Node.js. |

### Frameworks

| Framework | URL | Type | Description |
|-----------|-----|------|-------------|
| NestJS (@nestjs/cqrs) | https://docs.nestjs.com/recipes/cqrs | CQRS Framework | NestJS module providing CQRS pattern implementation with commands, queries, events, and sagas. |
| NestJS Microservices | https://docs.nestjs.com/microservices/basics | Microservices Framework | NestJS built-in support for microservices with multiple transport layers (Kafka, RabbitMQ, NATS, Redis, gRPC). |
| Emmett | https://github.com/event-driven-io/emmett | Event Sourcing Framework | Opinionated Node.js Event Sourcing framework by Oskar Dudycz — focuses on composition and TypeScript expressiveness. |
| reSolve | https://reimagined.github.io/resolve/ | Full-Stack CQRS/ES | Full-stack CQRS, DDD, Event Sourcing framework for Node.js applications. |
| Temporal (Node.js SDK) | https://temporal.io/ | Workflow Orchestration | Durable execution platform for orchestrating event-driven workflows, sagas, and long-running processes with TypeScript SDK. |
| Serverless Framework | https://www.serverless.com/ | Serverless Deployment | Framework for deploying serverless event-driven architectures on AWS Lambda, EventBridge, and other cloud services. |

### Event Stores

| Tool | URL | Type | Description |
|------|-----|------|-------------|
| EventStoreDB | https://www.eventstore.com/ | Event Store Database | Purpose-built database for Event Sourcing — supports projections, subscriptions, and optimistic concurrency. |
| Kurrent (formerly Event Store Cloud) | https://www.kurrent.io/ | Managed Event Store | Managed EventStoreDB service with built-in projections and real-time subscriptions. |

### Schema & API Design

| Tool | URL | Type | Description |
|------|-----|------|-------------|
| AsyncAPI | https://www.asyncapi.com/ | API Specification | Industry standard for defining event-driven APIs — provides code generation, documentation, and validation tools. |
| JSON Schema | https://json-schema.org/ | Schema Validation | Standard for validating event payload structures — essential for event schema design and versioning. |
| Avro (confluent) | https://avro.apache.org/ | Schema Serialization | Data serialization system commonly used with Kafka for schema evolution and backward compatibility. |

---

## Recommended Learning Path

### Week 1-2: Foundations
1. Read the [Node.js EventEmitter docs](https://nodejs.org/api/events.html)
2. Read [Event-Based Architectures in JavaScript (freeCodeCamp)](https://www.freecodecamp.org/news/event-based-architectures-in-javascript-a-handbook-for-devs/)
3. Watch [Event Sourcing Example & Explained (CodeOpinion)](https://www.youtube.com/watch?v=AUj4M-st3ic)
4. Read [Understanding Event-Driven Architecture with Node.js and TypeScript](https://javascript.plainenglish.io/event-driven-architecture-with-nodejs-and-typescript-d14208452321)

### Week 3-4: Core Patterns
1. Read [Straightforward Event Sourcing with TypeScript and NodeJS (Oskar Dudycz)](https://event-driven.io/en/type_script_node_js_event_sourcing/)
2. Read [CQRS From Scratch With TypeScript](https://medium.com/swlh/cqrs-from-scratch-with-typescript-e2ccf7fc2b64)
3. Watch [Introduction to Event Sourcing in TypeScript and NodeJS](https://www.youtube.com/watch?v=5pc7abhle_Q)
4. Work through [Oskar Dudycz's Self-Paced Event Sourcing Kit](https://event-driven.io/en/introduction_to_event_sourcing/)
5. Read [Saga Pattern with Node.js](https://blog.bitsrc.io/implementing-saga-pattern-in-a-microservices-with-node-js-aa2faddafac3)

### Week 5-6: Message Brokers
1. Read [Mastering Message Queues: RabbitMQ, Kafka, BullMQ](https://javascript.plainenglish.io/mastering-message-queues-in-node-js-a-deep-dive-into-rabbitmq-kafka-and-bullmq-1e39214746eb)
2. Complete [RabbitMQ JavaScript Tutorials](https://www.rabbitmq.com/tutorials/tutorial-one-javascript)
3. Read [Kafka vs. RabbitMQ (LogRocket)](https://blog.logrocket.com/kafka-vs-rabbitmq-comparing-node-js-message-brokers/)
4. Try [BullMQ Quick Start](https://docs.bullmq.io/readme-1)
5. Explore [NATS with Node.js](https://oneuptime.com/blog/post/2026-02-02-nats-nodejs/view)

### Week 7-8: NestJS & Advanced Patterns
1. Read [NestJS CQRS Module docs](https://docs.nestjs.com/recipes/cqrs)
2. Read [Building Modular Event-Driven Microservices with CQRS in NestJS](https://waqarilyas.dev/blog/07-modular-event-driven-microservice-with-cqrs/)
3. Clone and study [oskardudycz/EventSourcing.NodeJS](https://github.com/oskardudycz/EventSourcing.NodeJS)
4. Clone and study [bitloops/ddd-hexagonal-cqrs-es-eda](https://github.com/bitloops/ddd-hexagonal-cqrs-es-eda)
5. Read [Event Versioning Strategies](https://theburningmonk.com/2025/04/event-versioning-strategies-for-event-driven-architectures/)

### Week 9-10: Production & Testing
1. Read [Testing Event-Driven Architectures in Node.js](https://article.arunangshudas.com/testing-event-driven-architectures-in-node-js-ea0660e3bd55)
2. Study [Node.js Testing Best Practices](https://github.com/goldbergyoni/nodejs-testing-best-practices)
3. Read [AWS Best Practices for EDA](https://aws.amazon.com/blogs/architecture/best-practices-for-implementing-event-driven-architectures-in-your-organization/)
4. Explore [AsyncAPI](https://www.asyncapi.com/) for event schema documentation
5. Build a complete project using patterns learned

---

## Key People to Follow

| Person | Platform | Focus |
|--------|----------|-------|
| Oskar Dudycz | [Blog](https://event-driven.io/en/) / [GitHub](https://github.com/oskardudycz) / [YouTube](https://www.youtube.com/@event-driven-io) | Event Sourcing, CQRS, Node.js/TypeScript, Emmett framework |
| Derek Comartin | [YouTube (CodeOpinion)](https://www.youtube.com/@CodeOpinion) / [Blog](https://codeopinion.com) | Software Architecture, CQRS, Event Sourcing, Messaging |
| Chris Richardson | [Microservices.io](https://microservices.io/) | Microservices patterns, Saga, CQRS, Event Sourcing |
| Yan Cui (theburningmonk) | [Blog](https://theburningmonk.com/) | Serverless, Event-Driven Architecture, AWS |
| Greg Young | [YouTube](https://www.youtube.com/results?search_query=greg+young+event+sourcing) | Creator of Event Sourcing/CQRS concepts |
| Martin Kleppmann | [Blog](https://martin.kleppmann.com/) | Distributed systems, data-intensive applications |

---

*Total resources: 130+ | Last updated: March 2026*
