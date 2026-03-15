# 🎓 Node.js + TypeScript + Event-Driven Architecture
# Complete Daily Learning Guide (2 Hours/Day)

> **Format**: 2 hours per day, structured curriculum
> **Duration**: ~90 days (12-13 weeks)
> **Level**: Beginner → Advanced
> **Compiled**: 2026-03-15
> **Source**: 4 comprehensive research documents with 1,700+ curated URLs

---

## 📋 How to Use This Guide

1. **Each day has a 2-hour block** split into theory (reading/watching) and practice (coding)
2. **🎥 = YouTube video** | **📖 = Article/Docs** | **💻 = Hands-on practice** | **📚 = Book chapter**
3. Resources are linked from the companion reference documents (see bottom)
4. Adjust pace as needed — some days may take longer depending on experience
5. **Weekend days** are lighter — review + mini-projects

---

## 📅 PHASE 1: FOUNDATIONS (Weeks 1-3)
### Node.js Core + TypeScript Basics

---

### Week 1: Node.js Fundamentals

#### Day 1 — What is Node.js & Setup
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 🎥 Watch: Node.js crash course overview | Traversy Media — Node.js Crash Course |
| 30 min | 📖 Read: Node.js official "Introduction to Node.js" | https://nodejs.org/en/learn/getting-started/introduction-to-nodejs |
| 30 min | 📖 Read: Node.js "Getting Started" guide | https://nodejs.org/en/learn |
| 30 min | 💻 Practice: Install Node.js (via nvm), create first script, explore REPL | — |

#### Day 2 — Modules & Package Management
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Node.js modules (CommonJS vs ESM) | Node.js docs — Modules section |
| 30 min | 🎥 Watch: npm crash course | Traversy Media — NPM Crash Course |
| 30 min | 📖 Read: pnpm vs npm vs yarn comparison | https://dev.to search "pnpm vs npm vs yarn 2024" |
| 30 min | 💻 Practice: Create a project with package.json, install packages, use ESM imports | — |

#### Day 3 — Async Programming (Callbacks, Promises)
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Node.js async programming guide | Node.js official learn section |
| 30 min | 🎥 Watch: JavaScript Promises explained | Fireship — Promises in 100 Seconds + deep dive |
| 30 min | 📖 Read: Callbacks → Promises → Async/Await evolution | freeCodeCamp guide |
| 30 min | 💻 Practice: Convert callback-based code to Promises, then to async/await | — |

#### Day 4 — The Event Loop Deep Dive
| Time | Activity | Resource |
|------|----------|----------|
| 25 min | 🎥 Watch: "What the heck is the event loop anyway?" | Philip Roberts — JSConf EU (classic, ~8M views) |
| 25 min | 📖 Read: Builder.io visual event loop guide | https://www.builder.io/blog/visual-guide-to-nodejs-event-loop |
| 25 min | 🎥 Watch: Node.js event loop — Beyond the Basics | Hussein Nasser |
| 25 min | 📖 Read: Squash.io advanced event loop internals | Squash.io Node.js event loop article |
| 20 min | 💻 Practice: Write code demonstrating microtasks vs macrotasks, setImmediate vs setTimeout | — |

#### Day 5 — Streams & Buffers
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Node.js Streams official docs | https://nodejs.org/api/stream.html |
| 30 min | 🎥 Watch: Node.js Streams tutorial | The Net Ninja or Codevolution |
| 30 min | 📖 Read: Buffers in Node.js | Node.js official docs |
| 30 min | 💻 Practice: Read large file with streams, pipe data, create transform stream | — |

#### Day 6 — File System & Path
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: fs module (promises API) | Node.js official docs |
| 20 min | 📖 Read: path module | Node.js official docs |
| 30 min | 💻 Practice: Build a CLI file organizer (read dir, sort files by extension) | — |
| 40 min | 📖 Review: Week 1 summary, revisit weak areas | — |

#### Day 7 — Week 1 Review & Mini-Project
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Review: Revisit event loop, streams, async concepts | Notes from the week |
| 90 min | 💻 Mini-Project: Build a CLI tool that reads a CSV file via streams, processes data async, and outputs results | — |

---

### Week 2: TypeScript Fundamentals

#### Day 8 — TypeScript Introduction & Setup
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 🎥 Watch: TypeScript in 100 Seconds + crash course | Fireship |
| 30 min | 📖 Read: TypeScript Handbook — "TypeScript for JS Programmers" | https://www.typescriptlang.org/docs/handbook/ |
| 30 min | 📖 Read: Setting up Node.js with TypeScript (2025 guide) | Better Stack or DEV Community guide |
| 30 min | 💻 Practice: Set up a Node.js + TypeScript project with tsconfig.json, ts-node | — |

#### Day 9 — Basic Types & Interfaces
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: TypeScript Handbook — Everyday Types | https://www.typescriptlang.org/docs/handbook/2/everyday-types.html |
| 30 min | 📖 Read: Interfaces vs Types | Matt Pocock article or Total TypeScript |
| 30 min | 🎥 Watch: TypeScript types deep dive | Matt Pocock / Total TypeScript YouTube |
| 30 min | 💻 Practice: Type a small Express-like app, define interfaces for request/response | — |

#### Day 10 — Generics & Utility Types
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: TypeScript Handbook — Generics | https://www.typescriptlang.org/docs/handbook/2/generics.html |
| 30 min | 🎥 Watch: TypeScript Generics explained | Matt Pocock or Jack Herrington |
| 30 min | 📖 Read: Utility Types (Partial, Required, Pick, Omit, Record) | TypeScript docs |
| 30 min | 💻 Practice: Build a generic Repository class, use utility types | — |

#### Day 11 — Enums, Decorators & Advanced Types
| Time | Activity | Resource |
|------|----------|----------|
| 25 min | 📖 Read: Enums in TypeScript | TypeScript Handbook |
| 25 min | 📖 Read: Decorators (experimental → TC39 stage 3) | TypeScript docs + DEV Community |
| 25 min | 📖 Read: Discriminated Unions, Type Guards, Narrowing | TypeScript Handbook |
| 25 min | 🎥 Watch: Advanced TypeScript patterns | Total TypeScript / Matt Pocock |
| 20 min | 💻 Practice: Implement discriminated unions for API responses, type guards | — |

#### Day 12 — TypeScript with Node.js in Practice
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: tsconfig.json deep dive | https://www.typescriptlang.org/tsconfig |
| 30 min | 📖 Read: Build tools — esbuild, tsx, ts-node comparison | Better Stack or DEV Community |
| 30 min | 📖 Read: Error handling patterns in TypeScript | LogRocket or Medium article |
| 30 min | 💻 Practice: Configure strict tsconfig, set up esbuild for fast compilation | — |

#### Day 13 — TypeScript Deep Dive (Book)
| Time | Activity | Resource |
|------|----------|----------|
| 60 min | 📚 Read: "TypeScript Deep Dive" by Basarat — Chapters on Project Setup + Types | https://basarat.gitbook.io/typescript |
| 60 min | 💻 Practice: Exercises from the book, type challenges | https://github.com/type-challenges/type-challenges |

#### Day 14 — Week 2 Review & Mini-Project
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Review: TypeScript concepts from the week | — |
| 90 min | 💻 Mini-Project: Rewrite Day 7's CLI tool in TypeScript with strict types, generics, and proper error handling | — |

---

### Week 3: Express/Fastify + TypeScript

#### Day 15 — Express.js with TypeScript
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Express + TypeScript setup guide | Toptal or Auth0 guide |
| 30 min | 🎥 Watch: Express + TypeScript crash course | Traversy Media or similar |
| 60 min | 💻 Practice: Build a REST API with Express + TypeScript (CRUD for a resource) | — |

#### Day 16 — Fastify with TypeScript
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Fastify official TypeScript docs | https://fastify.dev/docs/latest/Reference/TypeScript/ |
| 30 min | 📖 Read: Fastify vs Express comparison | Better Stack or DEV Community |
| 60 min | 💻 Practice: Rebuild yesterday's API with Fastify + TypeScript, compare DX | — |

#### Day 17 — Middleware, Validation & Error Handling
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Zod for runtime validation | https://zod.dev |
| 30 min | 📖 Read: Error handling middleware patterns | LogRocket guide |
| 30 min | 🎥 Watch: Zod + TypeScript validation | Matt Pocock or Theo |
| 30 min | 💻 Practice: Add Zod validation and centralized error handling to your API | — |

#### Day 18 — Database Integration (Prisma)
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Prisma quickstart | https://www.prisma.io/docs/getting-started |
| 30 min | 🎥 Watch: Prisma crash course | Traversy Media or Fireship |
| 60 min | 💻 Practice: Add Prisma to your API, define schema, run migrations, implement CRUD | — |

#### Day 19 — Authentication (JWT + Passport)
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: JWT authentication with Node.js + TypeScript | DEV Community or Medium |
| 30 min | 🎥 Watch: JWT auth implementation | Web Dev Simplified or similar |
| 60 min | 💻 Practice: Add JWT auth to your API — register, login, protected routes | — |

#### Day 20 — API Documentation & Testing Intro
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: OpenAPI/Swagger with Express/Fastify | swagger-jsdoc or fastify-swagger docs |
| 30 min | 📖 Read: Introduction to Jest with TypeScript | Jest docs + ts-jest setup |
| 60 min | 💻 Practice: Add Swagger docs + write first unit tests for your API | — |

#### Day 21 — Week 3 Review & Project
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Review: Express/Fastify, Prisma, Auth, Testing | — |
| 90 min | 💻 Project: Complete REST API with auth, validation, Prisma, Swagger, basic tests | — |

---

## 📅 PHASE 2: INTERMEDIATE (Weeks 4-6)
### Testing, NestJS & Design Patterns

---

### Week 4: Testing in Depth

#### Day 22 — Jest Deep Dive
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Jest with TypeScript — advanced config | ts-jest docs |
| 30 min | 🎥 Watch: Jest testing tutorial | Net Ninja Jest playlist |
| 60 min | 💻 Practice: Write unit tests — mocking, spying, async testing | — |

#### Day 23 — Vitest (Modern Alternative)
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Vitest docs — why Vitest over Jest | https://vitest.dev |
| 30 min | 🎥 Watch: Vitest crash course | Net Ninja Vitest playlist |
| 60 min | 💻 Practice: Migrate Jest tests to Vitest, compare speed and DX | — |

#### Day 24 — Integration & E2E Testing
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Supertest for API integration testing | Supertest docs + guides |
| 30 min | 📖 Read: Testcontainers for database testing | https://testcontainers.com |
| 60 min | 💻 Practice: Write integration tests with Supertest, test database operations | — |

#### Day 25 — TDD Workflow
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: TDD with TypeScript guide | DEV Community or Medium |
| 30 min | 🎥 Watch: TDD in practice | YouTube TDD tutorial |
| 60 min | 💻 Practice: Build a small feature using strict TDD (red-green-refactor) | — |

#### Day 26-28 — NestJS Introduction (3 days)

#### Day 26 — NestJS Basics
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: NestJS official first steps | https://docs.nestjs.com/first-steps |
| 30 min | 🎥 Watch: NestJS crash course | Traversy Media or Marius Espejo |
| 60 min | 💻 Practice: Create NestJS app, understand modules/controllers/providers | — |

#### Day 27 — NestJS Intermediate
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: NestJS middleware, guards, interceptors, pipes | NestJS docs |
| 30 min | 🎥 Watch: NestJS deep dive | NestJS playlist (Codevolution or similar) |
| 60 min | 💻 Practice: Add validation pipes, auth guards, logging interceptor | — |

#### Day 28 — NestJS + Prisma + Testing
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: NestJS + Prisma integration | NestJS recipes or Prisma docs |
| 30 min | 📖 Read: Testing NestJS applications | NestJS testing docs |
| 60 min | 💻 Practice: Build a complete NestJS CRUD module with Prisma and tests | — |

---

### Week 5: Design Patterns & Architecture

#### Day 29 — SOLID Principles in TypeScript
| Time | Activity | Resource |
|------|----------|----------|
| 40 min | 📖 Read: SOLID principles with TypeScript examples | DEV Community or Medium |
| 40 min | 🎥 Watch: SOLID in TypeScript | YouTube tutorial |
| 40 min | 💻 Practice: Refactor code to follow SOLID principles | — |

#### Day 30 — Repository & Dependency Injection Patterns
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Repository pattern in TypeScript | DEV Community |
| 30 min | 📖 Read: DI containers — tsyringe, InversifyJS | GitHub repos + docs |
| 60 min | 💻 Practice: Implement repository pattern with DI in a NestJS app | — |

#### Day 31 — Clean Architecture
| Time | Activity | Resource |
|------|----------|----------|
| 40 min | 📖 Read: Clean Architecture with TypeScript | DEV Community or blog posts |
| 40 min | 🎥 Watch: Clean Architecture explained | CodeOpinion or similar |
| 40 min | 💻 Practice: Structure a project following clean architecture layers | — |

#### Day 32 — Domain-Driven Design (DDD) Basics
| Time | Activity | Resource |
|------|----------|----------|
| 40 min | 📖 Read: DDD with TypeScript introduction | Khalil Stemmler's blog or DEV Community |
| 40 min | 🎥 Watch: DDD explained | CodeOpinion |
| 40 min | 💻 Practice: Model a domain with entities, value objects, aggregates | — |

#### Day 33 — GoF Patterns in TypeScript
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Factory, Strategy, Observer patterns | Refactoring.guru + TypeScript examples |
| 30 min | 📖 Read: Decorator pattern (TypeScript decorators) | TypeScript docs |
| 60 min | 💻 Practice: Implement 3 design patterns in TypeScript | — |

#### Day 34-35 — Week 5 Project
| Time | Activity | Resource |
|------|----------|----------|
| 2h × 2 | 💻 Project: Build a NestJS app with clean architecture, repository pattern, DI, and full test coverage | — |

---

### Week 6: DevOps & Deployment

#### Day 36 — Docker for Node.js
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 🎥 Watch: Docker crash course | TechWorld with Nana (6.1M views) |
| 30 min | 📖 Read: Docker multi-stage builds for Node.js | Docker docs + Better Stack |
| 60 min | 💻 Practice: Dockerize your NestJS app with multi-stage build | — |

#### Day 37 — Docker Compose & Local Dev
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Docker Compose for multi-service apps | Docker docs |
| 30 min | 🎥 Watch: Docker Compose tutorial | TechWorld with Nana |
| 60 min | 💻 Practice: docker-compose.yml with Node.js + PostgreSQL + Redis | — |

#### Day 38 — CI/CD with GitHub Actions
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: GitHub Actions for Node.js | GitHub docs |
| 30 min | 🎥 Watch: GitHub Actions CI/CD tutorial | Fireship or TechWorld with Nana |
| 60 min | 💻 Practice: Set up CI pipeline — lint, test, build, Docker push | — |

#### Day 39 — PM2, Clustering & Production
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: PM2 process manager | https://pm2.keymetrics.io/docs |
| 30 min | 📖 Read: Node.js clustering | Node.js cluster module docs |
| 30 min | 📖 Read: Production best practices | Node.js official best practices |
| 30 min | 💻 Practice: Configure PM2 with cluster mode, health checks | — |

#### Day 40 — Logging & Monitoring
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Pino logger (fastest Node.js logger) | https://getpino.io |
| 30 min | 📖 Read: OpenTelemetry for Node.js | https://opentelemetry.io/docs/languages/js/ |
| 30 min | 🎥 Watch: Observability for Node.js | YouTube tutorial |
| 30 min | 💻 Practice: Add structured logging (Pino) + basic OpenTelemetry traces | — |

#### Day 41-42 — Phase 2 Capstone
| Time | Activity | Resource |
|------|----------|----------|
| 2h × 2 | 💻 Capstone: Fully tested NestJS API, Dockerized, with CI/CD, logging, deployed locally | — |

---

## 📅 PHASE 3: EVENT-DRIVEN ARCHITECTURE (Weeks 7-10)
### EDA Patterns, Message Brokers & Microservices

---

### Week 7: EDA Fundamentals

#### Day 43 — Event-Driven Architecture Concepts
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 🎥 Watch: Event-Driven Architecture explained | CodeOpinion or freeCodeCamp |
| 30 min | 📖 Read: EDA fundamentals handbook | freeCodeCamp EDA handbook |
| 30 min | 📖 Read: EDA patterns overview | Plain English deep dive |
| 30 min | 💻 Practice: Diagram an event-driven system for an e-commerce app | — |

#### Day 44 — Node.js EventEmitter Deep Dive
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: EventEmitter API docs | https://nodejs.org/api/events.html |
| 30 min | 📖 Read: Typed EventEmitter patterns | DEV Community |
| 60 min | 💻 Practice: Build a custom typed event system, EventEmitter2 | — |

#### Day 45 — Redis Pub/Sub
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Redis Pub/Sub docs | https://redis.io/docs/interact/pubsub/ |
| 30 min | 🎥 Watch: Redis Pub/Sub with Node.js | Hussein Nasser or similar |
| 60 min | 💻 Practice: Build a real-time notification system with Redis Pub/Sub + ioredis | — |

#### Day 46 — BullMQ (Job Queues)
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: BullMQ docs | https://docs.bullmq.io |
| 30 min | 📖 Read: Background jobs patterns | DEV Community |
| 60 min | 💻 Practice: Implement email queue with BullMQ, retries, dead letter queue | — |

#### Day 47 — WebSockets & Real-Time
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Socket.IO docs | https://socket.io/docs |
| 30 min | 🎥 Watch: WebSockets + Socket.IO tutorial | Traversy Media or similar |
| 60 min | 💻 Practice: Build a real-time chat with Socket.IO + TypeScript | — |

#### Day 48-49 — Week 7 Project
| Time | Activity | Resource |
|------|----------|----------|
| 2h × 2 | 💻 Project: Real-time dashboard with EventEmitter + Redis Pub/Sub + WebSockets | — |

---

### Week 8: Message Brokers

#### Day 50 — Apache Kafka Introduction
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 🎥 Watch: Kafka explained in 100 seconds + deep dive | Fireship + Hussein Nasser |
| 30 min | 📖 Read: KafkaJS docs | https://kafka.js.org |
| 60 min | 💻 Practice: Set up Kafka with Docker, produce/consume messages with KafkaJS | — |

#### Day 51 — Kafka Patterns & Partitioning
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Kafka partitioning, consumer groups | Confluent docs |
| 30 min | 🎥 Watch: Kafka deep dive | Hussein Nasser |
| 60 min | 💻 Practice: Multi-partition topic, consumer groups, message ordering | — |

#### Day 52 — RabbitMQ
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: RabbitMQ tutorials | https://www.rabbitmq.com/tutorials |
| 30 min | 🎥 Watch: RabbitMQ crash course | Hussein Nasser or similar |
| 60 min | 💻 Practice: Set up RabbitMQ with Docker, implement work queues with amqplib | — |

#### Day 53 — NATS
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: NATS docs + JetStream | https://docs.nats.io |
| 30 min | 📖 Read: NATS vs Kafka vs RabbitMQ comparison | DEV Community |
| 60 min | 💻 Practice: NATS with JetStream, request-reply pattern | — |

#### Day 54 — Kafka vs RabbitMQ vs NATS Comparison
| Time | Activity | Resource |
|------|----------|----------|
| 40 min | 📖 Read: When to use which broker | Multiple comparison articles |
| 40 min | 🎥 Watch: Message broker comparison | CodeOpinion or Hussein Nasser |
| 40 min | 💻 Practice: Decision matrix — choose broker for different scenarios | — |

#### Day 55-56 — Week 8 Project
| Time | Activity | Resource |
|------|----------|----------|
| 2h × 2 | 💻 Project: Order processing system with Kafka (order placed → payment → shipping events) | — |

---

### Week 9: CQRS, Event Sourcing & Sagas

#### Day 57 — CQRS Pattern
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 🎥 Watch: CQRS explained | CodeOpinion (Derek Comartin) |
| 30 min | 📖 Read: CQRS with NestJS | NestJS CQRS module docs |
| 60 min | 💻 Practice: Implement CQRS in NestJS — separate command/query handlers | — |

#### Day 58 — Event Sourcing
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 🎥 Watch: Event Sourcing explained | Oskar Dudycz YouTube |
| 30 min | 📖 Read: Oskar Dudycz's Event Sourcing guides | https://event-driven.io |
| 60 min | 💻 Practice: Build event-sourced aggregate (e.g., shopping cart) | — |

#### Day 59 — Event Sourcing with TypeScript
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: oskardudycz/EventSourcing.NodeJS repo | GitHub |
| 30 min | 📖 Read: Emmett framework | https://github.com/event-driven-io/emmett |
| 60 min | 💻 Practice: Implement event store, projections, snapshots | — |

#### Day 60 — Saga Pattern
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Saga pattern for distributed transactions | Microservices.io |
| 30 min | 🎥 Watch: Saga pattern explained | CodeOpinion |
| 30 min | 📖 Read: Temporal for durable execution | https://temporal.io |
| 30 min | 💻 Practice: Implement a choreography-based saga | — |

#### Day 61 — NestJS Microservices
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: NestJS Microservices docs | https://docs.nestjs.com/microservices/basics |
| 30 min | 🎥 Watch: NestJS microservices tutorial | YouTube |
| 60 min | 💻 Practice: Split NestJS app into 2 microservices communicating via Redis/NATS | — |

#### Day 62-63 — Week 9 Project
| Time | Activity | Resource |
|------|----------|----------|
| 2h × 2 | 💻 Project: Event-sourced microservice with CQRS, projections, and saga for order management | — |

---

### Week 10: Advanced EDA Topics

#### Day 64 — Event Schema Design & AsyncAPI
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: AsyncAPI specification | https://www.asyncapi.com |
| 30 min | 📖 Read: Event schema versioning strategies | DEV Community |
| 60 min | 💻 Practice: Design event schemas with AsyncAPI, generate docs | — |

#### Day 65 — Serverless EDA (AWS)
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: AWS EventBridge docs | AWS docs |
| 30 min | 📖 Read: Lambda + EventBridge patterns | AWS best practices |
| 60 min | 💻 Practice: Design a serverless event-driven architecture (diagram + pseudo-code) | — |

#### Day 66 — Testing Event-Driven Systems
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Testing EDA patterns | DEV Community |
| 30 min | 📖 Read: Contract testing for events | Pact or similar |
| 60 min | 💻 Practice: Write tests for event handlers, test message flow | — |

#### Day 67 — Monitoring & Observability for EDA
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Distributed tracing with OpenTelemetry | OpenTelemetry docs |
| 30 min | 🎥 Watch: Observability for microservices | YouTube |
| 60 min | 💻 Practice: Add distributed tracing across microservices | — |

#### Day 68-70 — Phase 3 Capstone
| Time | Activity | Resource |
|------|----------|----------|
| 2h × 3 | 💻 Capstone: Full event-driven microservices system — 3 services, Kafka/NATS, CQRS, event sourcing, Docker Compose, monitoring | — |

---

## 📅 PHASE 4: ADVANCED & PRODUCTION (Weeks 11-13)
### Performance, Security, Monorepos & Production Readiness

---

### Week 11: Performance & Caching

#### Day 71 — Node.js Performance Profiling
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Clinic.js for profiling | https://clinicjs.org |
| 30 min | 🎥 Watch: Node.js performance optimization | YouTube |
| 60 min | 💻 Practice: Profile your app with Clinic.js, identify bottlenecks | — |

#### Day 72 — Memory Leaks & Worker Threads
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Memory leak detection in Node.js | Better Stack or LogRocket |
| 30 min | 📖 Read: Worker threads for CPU-intensive tasks | Node.js docs |
| 60 min | 💻 Practice: Detect and fix a memory leak, offload work to worker threads | — |

#### Day 73 — Redis Caching Patterns
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Caching strategies (cache-aside, write-through, write-behind) | Redis docs |
| 30 min | 🎥 Watch: Redis caching with Node.js | Hussein Nasser |
| 60 min | 💻 Practice: Implement cache-aside pattern with Redis in your NestJS app | — |

#### Day 74 — Benchmarking & Load Testing
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: autocannon for HTTP benchmarking | GitHub |
| 30 min | 📖 Read: k6 for load testing | https://k6.io |
| 60 min | 💻 Practice: Benchmark your API, identify and fix performance issues | — |

#### Day 75-77 — Security (3 days)

#### Day 75 — Security Fundamentals
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: OWASP Top 10 for Node.js | OWASP docs |
| 30 min | 📖 Read: Helmet.js for HTTP headers | https://helmetjs.github.io |
| 30 min | 📖 Read: Rate limiting (express-rate-limit) | npm docs |
| 30 min | 💻 Practice: Add Helmet, rate limiting, CORS to your API | — |

#### Day 76 — Input Validation & SQL Injection Prevention
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Zod vs class-validator vs Joi comparison | DEV Community |
| 30 min | 📖 Read: SQL injection prevention with ORMs | OWASP + Prisma docs |
| 60 min | 💻 Practice: Comprehensive input validation layer, security audit | — |

#### Day 77 — Security Auditing & Dependencies
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: npm audit, Snyk for dependency scanning | Snyk docs |
| 30 min | 📖 Read: Content Security Policy | MDN docs |
| 60 min | 💻 Practice: Run security audit, fix vulnerabilities, set up Snyk | — |

---

### Week 12: Monorepos & GraphQL

#### Day 78 — Monorepo with Nx
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Nx docs — getting started | https://nx.dev |
| 30 min | 🎥 Watch: Nx monorepo tutorial | YouTube |
| 60 min | 💻 Practice: Set up Nx workspace with shared libraries | — |

#### Day 79 — Turborepo & pnpm Workspaces
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Turborepo docs | https://turbo.build |
| 30 min | 📖 Read: pnpm workspaces | https://pnpm.io/workspaces |
| 60 min | 💻 Practice: Compare Nx vs Turborepo, set up pnpm workspace | — |

#### Day 80 — GraphQL with TypeScript
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Apollo Server with TypeScript | Apollo docs |
| 30 min | 🎥 Watch: GraphQL crash course | Ben Awad or Traversy Media |
| 60 min | 💻 Practice: Build a GraphQL API with Apollo + TypeScript + Prisma | — |

#### Day 81 — GraphQL Advanced (Code-First)
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: TypeGraphQL or Pothos for code-first GraphQL | Docs |
| 30 min | 📖 Read: NestJS GraphQL module | NestJS docs |
| 60 min | 💻 Practice: Code-first GraphQL with NestJS, resolvers, guards | — |

#### Day 82-84 — Week 12 Project
| Time | Activity | Resource |
|------|----------|----------|
| 2h × 3 | 💻 Project: Monorepo with shared libs, GraphQL gateway, 2 microservices | — |

---

### Week 13: Production Readiness & Final Project

#### Day 85 — Production Checklist
| Time | Activity | Resource |
|------|----------|----------|
| 60 min | 📖 Read: Node.js production best practices | https://github.com/goldbergyoni/nodebestpractices |
| 60 min | 💻 Practice: Audit your project against the checklist | — |

#### Day 86 — Prometheus + Grafana
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Prometheus metrics for Node.js | prom-client docs |
| 30 min | 🎥 Watch: Grafana + Prometheus setup | TechWorld with Nana |
| 60 min | 💻 Practice: Add custom metrics, set up Grafana dashboard | — |

#### Day 87 — Health Checks & Graceful Shutdown
| Time | Activity | Resource |
|------|----------|----------|
| 30 min | 📖 Read: Health check patterns | Terminus (NestJS) or custom |
| 30 min | 📖 Read: Graceful shutdown in Node.js | Better Stack |
| 60 min | 💻 Practice: Implement health checks, readiness probes, graceful shutdown | — |

#### Day 88-90 — FINAL CAPSTONE PROJECT
| Time | Activity | Resource |
|------|----------|----------|
| 2h × 3 | 💻 **Final Project**: Production-ready event-driven e-commerce system | — |

**Final Project Requirements:**
- ✅ NestJS monorepo (Nx or Turborepo)
- ✅ 3+ microservices (Orders, Payments, Inventory)
- ✅ Event-driven communication (Kafka or NATS)
- ✅ CQRS + Event Sourcing for at least one service
- ✅ Saga pattern for distributed transactions
- ✅ GraphQL gateway
- ✅ Prisma + PostgreSQL
- ✅ Redis caching
- ✅ Full test suite (unit + integration + E2E)
- ✅ Docker Compose for local dev
- ✅ CI/CD with GitHub Actions
- ✅ Structured logging (Pino) + OpenTelemetry
- ✅ Prometheus metrics + Grafana dashboard
- ✅ Security hardened (Helmet, rate limiting, validation)
- ✅ API documentation (Swagger + AsyncAPI)

---

## 📚 Companion Reference Documents

These detailed resource files contain all URLs, descriptions, and metadata:

| Document | Content | Size |
|----------|---------|------|
| `nodejs_ts_fundamentals_resources.md` | Node.js + TypeScript basics — 122 URLs | 289 lines |
| `eda_resources.md` | Event-Driven Architecture — ~198 URLs | 410 lines |
| `advanced_nodejs_ts_resources.md` | Advanced topics (NestJS, testing, DevOps, patterns) — ~1,249 URLs | 3,093 lines |
| `youtube_nodejs_ts_eda.md` | YouTube videos, playlists, channels — 204 URLs | 768 lines |

**Total: ~1,773 curated URLs across all documents**

---

## 🎯 Key YouTube Channels to Subscribe

| Channel | Focus | Why |
|---------|-------|-----|
| **Fireship** | Quick concepts, trends | Fast overviews of any topic |
| **Matt Pocock / Total TypeScript** | TypeScript mastery | Best TypeScript educator |
| **Hussein Nasser** | Backend architecture | Deep dives on protocols, databases, architecture |
| **CodeOpinion** (Derek Comartin) | CQRS, Event Sourcing, DDD | Go-to for EDA patterns |
| **Oskar Dudycz** | Event Sourcing with TS | Hands-on ES tutorials |
| **Traversy Media** | Full-stack tutorials | Great crash courses |
| **TechWorld with Nana** | DevOps, Docker, K8s | Best DevOps tutorials |
| **ThePrimeagen** | Performance, opinions | Entertaining + educational |
| **The Net Ninja** | Step-by-step series | Excellent for following along |
| **Theo (t3.gg)** | Modern web dev opinions | Stays current with trends |

---

## 📊 Time Investment Summary

| Phase | Weeks | Days | Hours |
|-------|-------|------|-------|
| Phase 1: Foundations | 3 | 21 | 42h |
| Phase 2: Intermediate | 3 | 21 | 42h |
| Phase 3: Event-Driven Architecture | 4 | 28 | 56h |
| Phase 4: Advanced & Production | 3 | 20 | 40h |
| **Total** | **13** | **90** | **180h** |

---

> 💡 **Tip**: Don't just watch/read — always code along. The practice sections are where real learning happens.
> 
> 🔄 **Iteration**: After completing the guide, revisit weak areas. The companion documents have hundreds more resources for deeper dives.
> 
> 🏆 **Goal**: By Day 90, you'll have built a production-ready, event-driven microservices system from scratch.
