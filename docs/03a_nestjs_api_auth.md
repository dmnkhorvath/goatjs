# Advanced Node.js + TypeScript: Comprehensive Learning Resources Guide

> A curated collection of 700+ verified learning resources for mastering advanced Node.js and TypeScript development.
> Compiled: March 2026

---

## Table of Contents

1. [NestJS Framework, API Design & Authentication](#part-1-nestjs-framework-api-design--authentication)
2. [ORMs, Databases & Design Patterns](#part-2-orms-databases--design-patterns)
3. [Testing, Security & Logging/Monitoring](#part-3-testing-security--loggingmonitoring)
4. [Deployment/DevOps, Performance & Monorepo Tools](#part-4-deploymentdevops-performance--monorepo-tools)
5. [Recommended Learning Path](#recommended-learning-path)

---

## How to Use This Guide

- **Beginners to Node.js/TS**: Start with official documentation links, then progress to tutorials
- **Intermediate developers**: Focus on advanced articles, design patterns, and architecture resources
- **Senior developers**: Dive into performance optimization, microservices patterns, and monorepo strategies
- **Each resource includes**: Title, URL, Type, Estimated Time, Difficulty Level, and Description

---

## Topics Covered

| Category | Topics |
|----------|--------|
| Frameworks | NestJS (modules, controllers, providers, middleware, guards, interceptors, pipes, microservices) |
| ORMs & Databases | Prisma, TypeORM, Drizzle ORM, PostgreSQL, MongoDB |
| Testing | Jest, Vitest, Supertest, unit/integration/E2E testing, TDD |
| API Design | REST best practices, GraphQL (Apollo, TypeGraphQL), OpenAPI/Swagger |
| Auth | Passport.js, JWT, OAuth2, session management, RBAC |
| DevOps | Docker, Docker Compose, CI/CD (GitHub Actions), PM2, clustering |
| Performance | Profiling, memory leaks, worker threads, caching (Redis) |
| Architecture | Repository pattern, DI, clean architecture, DDD, SOLID |
| Monorepo | Nx, Turborepo, pnpm workspaces |
| Observability | Winston, Pino, OpenTelemetry, Prometheus, Grafana |
| Security | Helmet, rate limiting, Zod, class-validator, CORS, OWASP |

---


# Part 1: NestJS, API Design & Authentication

# Learning Resources: NestJS Framework, API Design & Authentication/Authorization
## Advanced Node.js + TypeScript Development

> Compiled: 2026-03-15 | 150+ curated resources with verified URLs
> Topics: NestJS Framework, API Design (REST & GraphQL), Authentication & Authorization

---

## Table of Contents
1. [NestJS Framework](#1-nestjs-framework)
   - [Official Documentation](#11-official-documentation)
   - [Written Tutorials & Articles](#12-written-tutorials--articles)
   - [Online Courses](#13-online-courses)
   - [YouTube Videos & Playlists](#14-youtube-videos--playlists)
   - [Books](#15-books)
   - [GitHub Repositories](#16-github-repositories)
2. [API Design](#2-api-design)
   - [REST API Design](#21-rest-api-design)
   - [GraphQL with TypeScript](#22-graphql-with-typescript)
   - [OpenAPI/Swagger Integration](#23-openapiswagger-integration)
   - [API Versioning, Pagination & Error Handling](#24-api-versioning-pagination--error-handling)
3. [Authentication & Authorization](#3-authentication--authorization)
   - [Passport.js with NestJS](#31-passportjs-with-nestjs)
   - [JWT Authentication Patterns](#32-jwt-authentication-patterns)
   - [OAuth2 Implementation](#33-oauth2-implementation)
   - [Session Management](#34-session-management)
   - [Role-Based Access Control (RBAC)](#35-role-based-access-control-rbac)
4. [Curated Collections & Roadmaps](#4-curated-collections--roadmaps)
5. [Recommended Learning Path](#5-recommended-learning-path)

---

## 1. NestJS Framework

### 1.1 Official Documentation

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| NestJS Official Documentation | https://docs.nestjs.com/ | docs | Ongoing | All | Comprehensive official docs covering controllers, providers, modules, middleware, guards, interceptors, pipes, and more |
| NestJS Controllers | https://docs.nestjs.com/controllers | docs | 30 min | Beginner | Official guide to routing, request handling, and controller decorators |
| NestJS Providers | https://docs.nestjs.com/providers | docs | 30 min | Beginner | Dependency injection, services, and provider patterns |
| NestJS Modules | https://docs.nestjs.com/modules | docs | 30 min | Beginner | Module system, dynamic modules, and global modules |
| NestJS Middleware | https://docs.nestjs.com/middleware | docs | 20 min | Beginner | Middleware implementation and configuration |
| NestJS Guards | https://docs.nestjs.com/guards | docs | 25 min | Intermediate | Authorization guards and execution context |
| NestJS Interceptors | https://docs.nestjs.com/interceptors | docs | 25 min | Intermediate | Response mapping, cache management, and logging interceptors |
| NestJS Pipes | https://docs.nestjs.com/pipes | docs | 25 min | Intermediate | Validation and transformation pipes |
| NestJS Exception Filters | https://docs.nestjs.com/exception-filters | docs | 25 min | Intermediate | Built-in and custom exception handling |
| NestJS Custom Decorators | https://docs.nestjs.com/custom-decorators | docs | 20 min | Intermediate | Creating custom route and parameter decorators |
| NestJS Microservices | https://docs.nestjs.com/microservices/basics | docs | 1 hr | Advanced | Microservices architecture with various transport layers |
| NestJS GraphQL Quick Start | https://docs.nestjs.com/graphql/quick-start | docs | 45 min | Intermediate | Code-first and schema-first GraphQL approaches |
| NestJS Techniques: Versioning | https://docs.nestjs.com/techniques/versioning | docs | 20 min | Intermediate | URI, header, and media type API versioning |
| NestJS Techniques: Session | https://docs.nestjs.com/techniques/session | docs | 20 min | Intermediate | Session management with express-session |
| NestJS Recipes: Prisma | https://docs.nestjs.com/recipes/prisma | docs | 30 min | Intermediate | Prisma ORM integration guide |
| NestJS Recipes: Passport | https://docs.nestjs.com/recipes/passport | docs | 45 min | Intermediate | Passport.js authentication integration |
| NestJS Security: Authentication | https://docs.nestjs.com/security/authentication | docs | 45 min | Intermediate | JWT and Passport-based authentication |
| NestJS Security: Authorization | https://docs.nestjs.com/security/authorization | docs | 30 min | Intermediate | RBAC implementation with guards |

### 1.2 Written Tutorials & Articles

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| The NestJS Handbook (freeCodeCamp) | https://www.freecodecamp.org/news/the-nestjs-handbook-learn-to-use-nest-with-code-examples/ | article | 1.5 hr | Beginner | Comprehensive handbook covering NestJS core concepts with practical code examples |
| NestJS Tutorial: Complete Guide to Building Scalable Apps (2025) | https://generalistprogrammer.com/tutorials/nestjs-tutorial-complete-guide | article | 2 hr | Beginner | Full tutorial covering modules, controllers, services, and deployment |
| Best NestJS Practices and Advanced Techniques | https://medium.com/@boyinbodedev/best-nestjs-practices-and-advanced-techniques-e6d59d85366a | article | 30 min | Advanced | Advanced patterns including custom decorators, interceptors, and microservices |
| Mastering Advanced NestJS Concepts | https://medium.com/@ghadabenkhalifa/mastering-advanced-nestjs-concepts-essential-knowledge-for-every-frontend-developer-e3ea8c270a3c | article | 45 min | Advanced | Deep dive into custom decorators, interceptors, exception filters, and pipes |
| Guards vs Middlewares vs Interceptors vs Pipes in NestJS | https://medium.com/@kevinpatelcse/guards-vs-middlewares-vs-interceptors-vs-pipes-in-nestjs-a-comprehensive-guide-37841a7873f1 | article | 30 min | Intermediate | Comprehensive comparison of NestJS request pipeline components |
| NestJS Middleware vs Guards vs Interceptors | https://www.devcentrehouse.eu/blogs/nestjs-middleware-vs-guards-vs-interceptors/ | article | 25 min | Intermediate | Key differences and when to use each component |
| NestJS Guards, Interceptors, and Pipes: Request Processing | https://imnaeem.dev/blogs/nestjs-guards-interceptors-pipes | article | 20 min | Intermediate | Request processing order and practical usage patterns |
| 2025 NestJS BE Roadmap: Beginner to Senior Level | https://dev.to/tak089/nestjs-roadmap-for-2025-5jj | article | 20 min | All | Comprehensive roadmap from beginner to senior NestJS developer |
| Building Production-Ready NestJS Microservices | https://levelup.gitconnected.com/building-production-ready-nestjs-microservices-tcp-implementation-guide-0b4a4b8df166 | article | 45 min | Advanced | TCP transport microservices implementation guide |
| Building Microservices with NestJS and NATS - Complete Guide | https://blog.akashjavali.com/building-microservices-with-nestjs-a-complete-guide | article | 1 hr | Advanced | Complete guide to NestJS microservices with NATS transport |
| Create NestJS Microservices using RabbitMQ | https://dev.to/hmake98/create-nestjs-microservices-using-rabbitmq-part-1-441m | article | 45 min | Advanced | Step-by-step RabbitMQ microservices with Docker |
| Build Type-Safe Event-Driven Microservices with NestJS & RabbitMQ | https://js.elitedev.in/js/build-type-safe-event-driven-microservices-with-nestjs-rabbitmq-and-typescript-complete-guide-43a552a6/ | article | 1 hr | Advanced | Type-safe event-driven architecture with RabbitMQ |
| NestJS Expert Series: Database Integration with Prisma & TypeORM | https://dev.to/devto_with_yog/nestjs-expert-series-part-2-database-integration-with-prisma-typeorm-ica | article | 45 min | Intermediate | Comparing Prisma and TypeORM integration patterns |
| How to use Prisma ORM with NestJS (Official Prisma Guide) | https://www.prisma.io/docs/guides/frameworks/nestjs | article | 1 hr | Intermediate | Official Prisma guide for NestJS REST API with Prisma Postgres |
| Connecting to PostgreSQL with TypeORM or Prisma in NestJS | https://syskool.com/connecting-to-postgresql-with-typeorm-or-prisma-in-nestjs/ | article | 40 min | Intermediate | Side-by-side comparison of TypeORM and Prisma with PostgreSQL |

### 1.3 Online Courses

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| NestJS Fundamentals (Official) | https://learn.nestjs.com/p/fundamentals | course | 6 hr | Beginner | Official NestJS course covering all building blocks with certificate |
| NestJS Architecture & Advanced Patterns (Official) | https://learn.nestjs.com/p/architecture-and-advanced-patterns | course | 8 hr | Advanced | N-Tier, Hexagonal, DDD patterns for complex NestJS systems |
| NestJS GraphQL Bundle (Official) | https://learn.nestjs.com/p/nestjs-graphql-bundle-code-first-and-schema-first-approaches | course | 6 hr | Intermediate | Both code-first and schema-first GraphQL approaches |
| All Official NestJS Courses | https://courses.nestjs.com/ | course | 30+ hr | All | Complete catalog of official NestJS courses |
| Comprehensive NestJS Course (freeCodeCamp) | https://www.freecodecamp.org/news/comprehensive-nestjs-course/ | course | 4 hr | Beginner | Free comprehensive course covering REST APIs, middleware, auth, and more |
| NestJS Zero to Hero (Udemy) | https://www.udemy.com/course/nestjs-zero-to-hero/ | course | 10 hr | Beginner | Bestselling NestJS course on Udemy with TypeScript |
| Fundamentals of NestJS (Coursera) | https://www.coursera.org/learn/fundamentals-of-nestjs | course | 4 hr | Beginner | Free audit available; covers modern backend development fundamentals |
| Mastering NestJS (Coursera/Packt) | https://www.coursera.org/learn/packt-mastering-nestjs-4opl7 | course | 6 hr | Intermediate | Pipes, middleware, guards, interceptors, and advanced features |
| Free NestJS Courses Collection (Class Central) | https://www.classcentral.com/subject/nest | course | Varies | All | Aggregated list of 40+ free and paid NestJS courses |
| Free NestJS Tutorials (Coursesity) | https://coursesity.com/free-tutorials-learn/nest-js | course | Varies | All | Curated list of 25+ free NestJS tutorials and courses |

### 1.4 YouTube Videos & Playlists

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| NestJS Complete Tutorial Playlist | https://www.youtube.com/playlist?list=PL2NZAYdLkYviHnr4kfw3bm0vANXA6dZ0k | playlist | 10+ hr | All | Complete NestJS playlist from scratch to advanced with TypeScript |
| Nest.js Full Course for Beginners (3 Hours) | https://www.youtube.com/watch?v=8_X0nSrzrCw | video | 3 hr | Beginner | All-in-one beginner tutorial covering core NestJS concepts |
| Learn NestJS - Complete Course (freeCodeCamp) | https://www.youtube.com/watch?v=sFnAHC9lLaw | video | 3.5 hr | Beginner | freeCodeCamp comprehensive NestJS course on YouTube |
| NestJS Course for Beginners (Scrimba/freeCodeCamp) | https://www.youtube.com/watch?v=21_I-12f5JE | video | 2 hr | Beginner | Build server-side applications with NestJS from scratch |
| Nest.js Tutorial for Beginners - Full Course 2025 | https://www.youtube.com/watch?v=I7xfoLdNqP0 | video | 2.5 hr | Beginner | Updated 2025 beginner tutorial |
| NestJS Full Course 2025 | https://www.youtube.com/watch?v=XVZ10uFY9DU | video | 3 hr | Beginner | Complete 2025 course with source code |
| NestJS Full Course | https://www.youtube.com/watch?v=JDJ0zQLvpOA | video | 2.5 hr | Beginner | Modular architecture, DI, and built-in support walkthrough |
| NestJS Microservices - TCP, Redis, gRPC, Kafka, RabbitMQ & NATS | https://www.youtube.com/watch?v=3V5cbvXVbdA | video | 1 hr | Advanced | All communication patterns in NestJS microservices explained |
| Node JS Full Course 2025 - PostgreSQL, Prisma, NestJS | https://www.youtube.com/watch?v=pa9xqOnorx0 | video | 4+ hr | Intermediate | Comprehensive Node.js course with NestJS, Prisma, and PostgreSQL |

### 1.5 Books

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| NestJS - Build a RESTful CRUD API (Free eBook) | https://ultimatecourses.com/ebooks/nestjs-restful-crud-api | book | 2 hr | Beginner | Free 37-page PDF covering NestJS basics and CRUD API development |
| Nest.js: A Progressive Node.js Framework (Free PDF) | https://github.com/Shah-Shishir/Textbooks/blob/master/Nest-js-A-Progressive-Node-js-Framework-pdf.pdf | book | 3 hr | Beginner | Free PDF textbook on NestJS fundamentals |
| Scalable Application Development with NestJS (Packt) | https://www.packtpub.com/en-us/product/scalable-application-development-with-nestjs-9781835463956 | book | 15 hr | Intermediate | Core concepts, design patterns, and best practices (includes free PDF with purchase) |
| The TypeScript Handbook (Official) | https://www.typescriptlang.org/docs/handbook/intro.html | book | 5 hr | Beginner | Official TypeScript handbook - essential prerequisite for NestJS |
| Learning TypeScript eBook (Free PDF) | https://riptutorial.com/ebook/typescript | book | 4 hr | Beginner | Free community-contributed TypeScript eBook |

### 1.6 GitHub Repositories

| Title | URL | Type | Stars | Level | Description |
|-------|-----|------|-------|-------|-------------|
| nestjs/nest (Official) | https://github.com/nestjs/nest | repo | 70k+ | All | Official NestJS framework repository |
| nestjs/awesome-nestjs | https://github.com/nestjs/awesome-nestjs | repo | 9k+ | All | Official curated list of awesome NestJS resources, libraries, and projects |
| Awesome NestJS Website | https://awesome-nestjs.com/ | repo | - | All | Browsable website version of the awesome-nestjs list |
| NarHakobyan/awesome-nest-boilerplate | https://github.com/NarHakobyan/awesome-nest-boilerplate | repo | 2k+ | Intermediate | Enterprise-grade NestJS boilerplate with TypeScript, Postgres, TypeORM |
| NestJS Boilerplate Topic (GitHub) | https://github.com/topics/nestjs-boilerplate | repo | - | All | Collection of NestJS boilerplate repositories on GitHub |
| NestJS Starter Topic (GitHub) | https://github.com/topics/nestjs-starter | repo | - | All | Collection of NestJS starter templates on GitHub |
| NestJS Microservices Boilerplates (StarterIndex) | https://starterindex.com/microservices+nestjs-boilerplates | repo | - | Advanced | 31 curated NestJS microservices boilerplates |
| NestJS Boilerplates Collection (StarterIndex) | https://starterindex.com/nestjs-boilerplates | repo | - | All | 72 curated NestJS boilerplates and starter kits |

---

## 2. API Design

### 2.1 REST API Design

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| REST API Best Practices (Postman Blog) | https://blog.postman.com/rest-api-best-practices/ | article | 30 min | Intermediate | HTTP methods, status codes, versioning, auth, pagination, and error handling |
| RESTful API Design Best Practices Guide 2024 (Daily.dev) | https://daily.dev/blog/restful-api-design-best-practices-guide-2024 | article | 40 min | Intermediate | Resource-based architecture, stateless communication, URI design, security |
| Best Practices in API Design (Swagger) | https://swagger.io/resources/articles/best-practices-in-api-design/ | article | 25 min | Intermediate | API design principles from the Swagger/OpenAPI team |
| REST API Design Best Practices: A Complete Guide (Medium) | https://medium.com/@aksasync/rest-api-design-best-practices-a-complete-guide-986fccff849a | article | 35 min | Intermediate | Comprehensive guide with 2024 survey data on API design impact |
| How to Build a Scalable REST API with TypeScript and NestJS | https://codezup.com/building-a-scalable-rest-api-with-typescript-nestjs/ | article | 1 hr | Intermediate | Hands-on tutorial building a scalable REST API |
| RESTful API Best Practices: Versioning, Error Handling, and Responses | https://agungpp.medium.com/restful-api-best-practices-versioning-error-handling-and-responses-15663c41a0ac | article | 25 min | Intermediate | Pagination, filtering, sorting, and response structure patterns |
| How to Design APIs Like a Senior Engineer | https://www.youtube.com/watch?v=7iHl71nt49o | video | 30 min | Intermediate | REST, GraphQL, authentication, and security best practices |
| Web API Design Series (Ambient Coder) | https://www.youtube.com/playlist?list=PLP_rkG1reBjrCKy2Pb1bvjJKbKfantijk | playlist | 2 hr | Intermediate | REST vs RPC vs GraphQL, webhooks, websockets, HTTP streaming |

### 2.2 GraphQL with TypeScript

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| NestJS GraphQL Quick Start (Official) | https://docs.nestjs.com/graphql/quick-start | docs | 45 min | Intermediate | Official NestJS GraphQL integration with code-first and schema-first |
| Intro to GraphQL with TypeScript & Apollo Server | https://www.apollographql.com/tutorials/intro-typescript | course | 3 hr | Beginner | Official Apollo tutorial: SDL fundamentals, resolvers, TypeScript API |
| GraphQL Federation with TypeScript & Apollo Server | https://www.apollographql.com/tutorials/federation-typescript | course | 4 hr | Advanced | Federated graph architecture, subgraphs, entities, and directives |
| Pothos GraphQL Schema Builder | https://pothos-graphql.dev/ | docs | 2 hr | Intermediate | Most type-safe way to build GraphQL schemas in TypeScript, plugin-based |
| Learn GraphQL (Official graphql.org) | https://graphql.org/learn/ | docs | 3 hr | Beginner | Official GraphQL learning resources: schemas, versioning, caching |
| Getting Started with GraphQL, TypeScript and Apollo | https://www.howtographql.com/typescript-apollo/1-getting-started/ | article | 1.5 hr | Beginner | Step-by-step GraphQL server setup with TypeScript and Apollo |
| Revisiting GraphQL in 2025: Type-Safe Stack with Pothos and Relay | https://dev.to/tigawanna/revisiting-graphql-in-2025-a-type-safe-stack-with-pothos-and-relay-ka8 | article | 30 min | Advanced | Modern type-safe GraphQL stack exploration |
| NestJS + GraphQL: Code-First API Design Guide | https://medium.com/@pratikkumar2210/nestjs-graphql-a-comprehensive-guide-to-code-first-api-design-9064a581fc10 | article | 40 min | Intermediate | Comprehensive guide to NestJS GraphQL code-first approach |
| A Guide to Building GraphQL APIs with NestJS (Telerik) | https://www.telerik.com/blogs/guide-building-graphql-apis-nestjs | article | 45 min | Intermediate | Code-first vs schema-first approaches with NestJS |
| Build Type-Safe GraphQL APIs: NestJS Prisma Code-First | https://js.elitedev.in/js/build-type-safe-graphql-apis-complete-nestjs-prisma-code-first-schema-generation-tutorial-2024-1dab3b56/ | article | 1 hr | Intermediate | Complete tutorial with auth, optimization, and deployment |
| Building Production-Ready GraphQL APIs with TypeScript | https://js.elitedev.in/js/building-production-ready-graphql-apis-with-typescript-complete-apollo-server-and-dataloader-implem-d99908e9/ | article | 1 hr | Advanced | Apollo Server 4, DataLoader, N+1 query solving, testing |
| GraphQL Apollo Server Tutorial with TypeScript | https://www.youtube.com/watch?v=KbJT6Ld15-M | video | 1 hr | Intermediate | Hands-on Apollo Server tutorial with TypeScript |
| Build a GraphQL API with Node.js, TypeGraphQL | https://www.youtube.com/watch?v=4Sei6fdYZuQ | video | 1.5 hr | Intermediate | TypeGraphQL with Typegoose for MongoDB integration |
| GraphQL Tutorial Playlist | https://www.youtube.com/playlist?list=PLsvvBhdpMqBxk9kcmRCUX7QbGFjiMOmX1 | playlist | 5+ hr | All | Complete GraphQL tutorial series with Node.js |
| NestJS GraphQL Code-First and Schema-First #04 | https://www.youtube.com/watch?v=qJ51ppYxm48 | video | 30 min | Intermediate | Practical NestJS GraphQL implementation |

### 2.3 OpenAPI/Swagger Integration

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| NestJS OpenAPI Introduction (Official) | https://docs.nestjs.com/openapi/introduction | docs | 30 min | Intermediate | Official guide to @nestjs/swagger module setup and configuration |
| NestJS OpenAPI CLI Plugin (Official) | https://docs.nestjs.com/openapi/cli-plugin | docs | 20 min | Intermediate | Auto-derive @ApiProperty() from TypeScript types and class-validator |
| API Documentation with Swagger - NestJS DeepWiki | https://deepwiki.com/nestjs/nest/9.2-api-documentation-with-swagger | article | 30 min | Intermediate | Comprehensive guide to @nestjs/swagger module with metadata reflection |
| Documenting APIs in NestJS with Swagger: Modular Approach | https://medium.com/@patrick.cunha336/documenting-apis-in-nestjs-with-swagger-a-modular-approach-92e777594eaf | article | 25 min | Intermediate | Module-based documentation organization for scalable projects |
| Integrating Swagger with NestJS: Step-by-Step Guide | https://anshusharma98204.medium.com/integrating-swagger-with-nestjs-a-step-by-step-guide-b79db952ca0e | article | 20 min | Beginner | Quick start guide for NestJS Swagger integration |
| Generating OpenAPI Specs on the Fly with NestJS | https://andyprimawan.com/generating-openapi-specs-on-the-fly-with-nestjs-and-typescript/ | article | 25 min | Intermediate | Automating OpenAPI documentation with decorators and DTOs |
| How to Generate an OpenAPI Document with NestJS (Speakeasy) | https://www.speakeasy.com/openapi/frameworks/nestjs | article | 20 min | Intermediate | OpenAPI spec generation and SDK generation pipeline |
| NestJS Swagger: Generate JSON/YAML Documentation | https://www.codestudy.net/blog/generate-swagger-documentation-as-json-yaml-in-nestjs/ | article | 20 min | Intermediate | Generate Swagger docs as JSON/YAML files for CI/CD |

### 2.4 API Versioning, Pagination & Error Handling

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| NestJS Versioning (Official Docs) | https://docs.nestjs.com/techniques/versioning | docs | 20 min | Intermediate | URI, header, and media type versioning strategies |
| NestJS Exception Filters (Official Docs) | https://docs.nestjs.com/exception-filters | docs | 25 min | Intermediate | Built-in HttpException and custom exception filters |
| API Versioning with NestJS (alckor.dev) | https://alckor.dev/en/blog/versioning-api-with-nestjs | article | 30 min | Intermediate | URI, header, media type versioning with folder structure best practices |
| API Versioning Strategies in NestJS | https://medium.com/@jradzik4/api-versioning-strategies-in-nestjs-f1f0576c92fa | article | 20 min | Intermediate | Comparison of versioning strategies with practical examples |
| Version NestJS APIs Without Breaking Everyone | https://medium.com/@Quaxel/version-nestjs-apis-without-breaking-everyone-ef908d2d253b | article | 20 min | Intermediate | Practical versioning patterns with sunset plans |
| NestJS API Versioning Strategies (This Dot Labs) | https://www.thisdot.co/blog/nestjs-api-versioning-strategies | article | 25 min | Intermediate | URI, custom header, and media type versioning deep dive |
| NestJS Error Handling Patterns (Better Stack) | https://betterstack.com/community/guides/scaling-nodejs/error-handling-nestjs/ | article | 35 min | Intermediate | Comprehensive error handling patterns for resilient applications |
| Error Handling in NestJS: Best Practices and Examples | https://dev.to/geampiere/error-handling-in-nestjs-best-practices-and-examples-5e76 | article | 25 min | Intermediate | Built-in exceptions, global filters, and custom strategies |
| Versioning Best Practices in REST API Design (Speakeasy) | https://www.speakeasy.com/api-design/versioning | article | 20 min | Intermediate | General REST API versioning best practices and evolution strategies |

---

## 3. Authentication & Authorization

### 3.1 Passport.js with NestJS

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| NestJS Passport Recipe (Official) | https://docs.nestjs.com/recipes/passport | docs | 45 min | Intermediate | Official guide to Passport.js integration with NestJS |
| NestJS Authentication (Official) | https://docs.nestjs.com/security/authentication | docs | 45 min | Intermediate | JWT authentication with Passport local and JWT strategies |
| Passport.js Official Documentation | https://www.passportjs.org/ | docs | 1 hr | Intermediate | Official Passport.js docs with 500+ authentication strategies |
| Passport.js Strategies Documentation | https://www.passportjs.org/concepts/authentication/strategies/ | docs | 30 min | Intermediate | Understanding and implementing Passport strategies |
| Passport Strategies in NestJS: JWT, Local, OAuth2, Google | https://syskool.com/passport-strategies-in-nestjs-jwt-local-oauth2-and-google-login/ | article | 40 min | Intermediate | Comprehensive guide to multiple Passport strategies in NestJS |
| Advanced Authentication in NestJS with Passport.js | https://bhargavacharyb.medium.com/nestjs-12-advanced-authentication-in-nestjs-with-passport-js-65d221aa16b2 | article | 35 min | Advanced | Pluggable strategies, centralized auth flow, and middleware integration |
| NestJS Passport Strategies Overview | https://dev.to/wakeup_flower_8591a6cb6a9/nestjs-passport-strategies-344d | article | 15 min | Intermediate | Quick reference for common Passport strategies in NestJS |
| How to Use Passport.js in NestJS (Sling Academy) | https://www.slingacademy.com/article/how-to-use-passportjs-in-nestjs/ | article | 30 min | Intermediate | Step-by-step Passport.js integration guide |
| Implement Google OAuth in NestJS using Passport | https://dev.to/chukwutosin_/implement-google-oauth-in-nestjs-using-passport-1j3k | article | 30 min | Intermediate | Google OAuth2 implementation with Passport in NestJS |

### 3.2 JWT Authentication Patterns

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| JWT Authentication in NestJS with Passport: Step-by-Step | https://inside.caratlane.com/jwt-authentication-in-nestjs-with-passport-a-step-by-step-guide-22314e8999b1 | article | 40 min | Intermediate | Secure, extensible JWT authentication system |
| Implementing Authentication in NestJS using Passport and JWT | https://medium.com/@camillefauchier/implementing-authentication-in-nestjs-using-passport-and-jwt-5a565aa521de | article | 35 min | Intermediate | Step-by-step JWT implementation with Passport middleware |
| Secure Your NestJS APIs: JWT Authentication with Passport.js | https://www.linkedin.com/pulse/secure-your-nestjs-apis-jwt-authentication-passportjs-course-casts-xqorf | article | 30 min | Intermediate | JWT authentication walkthrough for NestJS APIs |
| Secure Authentication with JWTs & Rotating Refresh Tokens | https://dev.to/wiljeder/secure-authentication-with-jwts-rotating-refresh-tokens-typescript-express-vanilla-js-4f41 | article | 45 min | Advanced | JWT with refresh token rotation, XSS prevention, TypeScript + Express |
| How to Build a Secure Auth System with JWT and Refresh Tokens (freeCodeCamp) | https://www.freecodecamp.org/news/how-to-build-a-secure-authentication-system-with-jwt-and-refresh-tokens/ | article | 40 min | Intermediate | Access tokens, refresh tokens, and security best practices |
| 7 Best Practices for JWT Rotation in Node.js APIs | https://article.arunangshudas.com/7-best-practices-for-jwt-rotation-in-node-js-apis-5b5643c096eb | article | 25 min | Advanced | JWT rotation security patterns for production APIs |
| JWT Authentication With Refresh Tokens (GeeksforGeeks) | https://www.geeksforgeeks.org/node-js/jwt-authentication-with-refresh-tokens/ | article | 30 min | Intermediate | HttpOnly cookies, refresh token implementation, and session management |
| Build an Authentication API with Node.js, TypeScript | https://www.youtube.com/watch?v=qylGaki0JhY | video | 1.5 hr | Intermediate | Complete auth API tutorial with TypeScript (TomDoesTech) |

### 3.3 OAuth2 Implementation

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Building a Complete OAuth 2.0 Provider with NestJS | https://medium.com/@shivaji.kattimani/building-a-complete-oauth-2-0-provider-with-nestjs-a-comprehensive-tutorial-7098cbcd275d | article | 1 hr | Advanced | Production-ready OAuth provider with social login, PKCE, and scope management |
| NestJS Authentication with OAuth2.0: Configuration and Operations | https://dev.to/tugascript/nestjs-authentication-with-oauth20-configuration-and-operations-41k | article | 45 min | Advanced | Full OAuth2.0 authentication implementation series |
| NestJS: Google OAuth2 Authentication with Passport | https://riochndr.com/posts-nestjs-google-auth2-with-passport/ | article | 30 min | Intermediate | Google OAuth2 with Passport strategy in NestJS |
| Secure Your NestJS App: Authentication With Auth0 | https://hackernoon.com/secure-your-nestjs-app-how-to-implement-authentication-with-auth0 | article | 35 min | Intermediate | Auth0 integration with NestJS using Passport and JWT |
| Implementing IAM in NestJS: The Essential Guide (Andela) | https://www.andela.com/blog-posts/implementing-iam-in-nestjs-the-essential-guide | article | 40 min | Advanced | Identity and Access Management with JWT and OAuth2 |
| Google OAuth 2.0 with NestJS (GitHub) | https://github.com/boybothere/google-oauth2-nestjs | repo | 1 hr | Intermediate | Complete OAuth 2.0 Authorization Code Flow with session management |
| OAuth2 Implementation Example using NestJS (GitHub) | https://github.com/leduyminh48/nestjs-oauth2-example | repo | 1 hr | Advanced | Full OAuth2 provider implementation with authorization code flow |

### 3.4 Session Management

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| NestJS Session (Official Docs) | https://docs.nestjs.com/techniques/session | docs | 20 min | Intermediate | Official express-session middleware integration guide |
| Session Management with Express in NestJS (CodeSignal) | https://codesignal.com/learn/courses/securing-and-testing-your-mvc-nestjs-app/lessons/session-management-with-express-in-nestjs | course | 30 min | Intermediate | Session setup, Handlebars rendering, and visit tracking |
| Setting Up Sessions with NestJS, Passport, and Redis | https://dev.to/nestjs/setting-up-sessions-with-nestjs-passport-and-redis-210 | article | 35 min | Intermediate | Session store with Redis for NestJS applications |
| How to Set Up Session-Based Authentication in NestJS | https://medium.com/@gerogewilson/how-to-set-up-session-based-authentication-in-nestjs-cb90b068c0c1 | article | 30 min | Intermediate | Complete session-based auth setup guide |

### 3.5 Role-Based Access Control (RBAC)

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| NestJS Authorization (Official Docs) | https://docs.nestjs.com/security/authorization | docs | 30 min | Intermediate | Official RBAC implementation with guards and decorators |
| Mastering Complex RBAC in NestJS: CASL with Prisma ORM | https://blog.devgenius.io/mastering-complex-rbac-in-nestjs-integrating-casl-with-prisma-orm-for-granular-authorization-767941a05ef1 | article | 45 min | Advanced | Hybrid RBAC/ABAC with CASL and Prisma for granular permissions |
| Role-Based Access Control (RBAC) in NestJS | https://medium.com/@chandantechie/role-based-access-control-rbac-in-nestjs-a5963bcd70bd | article | 25 min | Intermediate | Foundational RBAC implementation patterns |
| Custom Role-Based Access Control in NestJS Using Custom Guards | https://dev.to/imzihad21/custom-role-based-access-control-in-nestjs-using-custom-guards-jol | article | 30 min | Intermediate | Production-ready RBAC with custom guards and metadata reflection |
| Demystifying Access Control: RBAC vs CASL in NestJS | https://medium.com/@kathishcivil94/demystifying-access-control-rbac-vs-casl-in-nestjs-e1cde782e5c0 | article | 25 min | Intermediate | Comparing RBAC and CASL approaches with pros/cons |
| Integrating CASL with NestJS: Step-by-Step Guide | https://blog.bytescrum.com/integrating-casl-with-nestjs-a-step-by-step-guide | article | 30 min | Intermediate | Declarative permission management with CASL |
| Extensible and Secure Authorization with NestJS and CASL | https://mfi.engineering/extensible-and-secure-authorization-with-nestjs-and-casl-c6f6d1ceefd5 | article | 35 min | Advanced | Enterprise-grade authorization with dynamic permission changes |
| Role-Based Access Control in NestJS (DEV Community) | https://dev.to/luffy_p1r4t3/role-based-access-control-in-nestjs-2cl2 | article | 20 min | Intermediate | Practical RBAC implementation tutorial |
| Mastering Authorization in NestJS: RBAC, Claim-Based, and CASL | https://www.youtube.com/watch?v=4rw_9chhV_Q | video | 45 min | Intermediate | Comprehensive authorization tutorial covering multiple approaches |
| Master Role-Based Authorization in NestJS (Full Guide) | https://www.youtube.com/watch?v=ttLIQPQmLKc | video | 40 min | Intermediate | Guards, decorators, and metadata for role-based security |

---

## 4. Curated Collections & Roadmaps

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Awesome NestJS (Official) | https://github.com/nestjs/awesome-nestjs | repo | - | All | Official curated list of NestJS resources, libraries, tools, and projects |
| Awesome NestJS Website | https://awesome-nestjs.com/ | docs | - | All | Browsable categorized collection of NestJS resources |
| Awesome NestJS Examples | https://awesome-nestjs.com/resources/examples.html | docs | - | All | Curated example projects and implementations |
| Awesome NestJS Boilerplate | https://awesome-nestjs.com/resources/boilerplate.html | docs | - | All | Enterprise-grade boilerplates and starter templates |
| 2025 NestJS BE Roadmap | https://dev.to/tak089/nestjs-roadmap-for-2025-5jj | article | 20 min | All | Comprehensive roadmap from beginner to senior level |
| 6 Best NestJS Courses For Beginners in 2025 | https://coursesity.com/blog/best-nestjs-courses/ | article | 10 min | Beginner | Curated course recommendations with reviews |
| Top NestJS Courses (Udemy) | https://www.udemy.com/topic/nestjs/ | course | - | All | Udemy's top-rated NestJS courses collection |
| NestJS Authentication GitHub Topic | https://github.com/topics/nestjs-authentication | repo | - | All | GitHub topic page for NestJS authentication projects |

---

## 5. Recommended Learning Path

### Week 1-2: NestJS Foundations
1. Complete the [NestJS Official Documentation](https://docs.nestjs.com/) (controllers, providers, modules)
2. Watch [Nest.js Full Course for Beginners](https://www.youtube.com/watch?v=8_X0nSrzrCw) (3 hrs)
3. Read [The NestJS Handbook](https://www.freecodecamp.org/news/the-nestjs-handbook-learn-to-use-nest-with-code-examples/) on freeCodeCamp
4. Practice: Build a basic CRUD API with NestJS + Prisma

### Week 3-4: Advanced NestJS & API Design
1. Study middleware, guards, interceptors, and pipes from [official docs](https://docs.nestjs.com/guards)
2. Read [Guards vs Middlewares vs Interceptors vs Pipes](https://medium.com/@kevinpatelcse/guards-vs-middlewares-vs-interceptors-vs-pipes-in-nestjs-a-comprehensive-guide-37841a7873f1)
3. Learn [REST API Best Practices](https://blog.postman.com/rest-api-best-practices/) from Postman
4. Implement [OpenAPI/Swagger](https://docs.nestjs.com/openapi/introduction) in your project
5. Add [API versioning](https://docs.nestjs.com/techniques/versioning) and error handling

### Week 5-6: GraphQL with NestJS
1. Complete [NestJS GraphQL Quick Start](https://docs.nestjs.com/graphql/quick-start)
2. Take [Intro to GraphQL with TypeScript & Apollo Server](https://www.apollographql.com/tutorials/intro-typescript)
3. Explore [Pothos GraphQL](https://pothos-graphql.dev/) for type-safe schema building
4. Practice: Build a GraphQL API with code-first approach

### Week 7-8: Authentication & Authorization
1. Implement [Passport.js with NestJS](https://docs.nestjs.com/recipes/passport) (local + JWT strategies)
2. Add [JWT with refresh tokens](https://www.freecodecamp.org/news/how-to-build-a-secure-authentication-system-with-jwt-and-refresh-tokens/)
3. Implement [Google OAuth2](https://dev.to/chukwutosin_/implement-google-oauth-in-nestjs-using-passport-1j3k)
4. Study [RBAC with guards](https://docs.nestjs.com/security/authorization) and implement role-based access
5. Explore [CASL integration](https://blog.devgenius.io/mastering-complex-rbac-in-nestjs-integrating-casl-with-prisma-orm-for-granular-authorization-767941a05ef1) for granular permissions

### Week 9-10: Microservices & Production Patterns
1. Study [NestJS Microservices](https://docs.nestjs.com/microservices/basics) documentation
2. Watch [NestJS Microservices Communication Patterns](https://www.youtube.com/watch?v=3V5cbvXVbdA)
3. Build a microservices project with RabbitMQ or NATS
4. Study [NestJS Architecture & Advanced Patterns](https://learn.nestjs.com/p/architecture-and-advanced-patterns)
5. Review [awesome-nestjs](https://github.com/nestjs/awesome-nestjs) for production tools and libraries

---

## Key GitHub Repositories for Practice

| Repository | URL | Description |
|-----------|-----|-------------|
| nestjs/nest | https://github.com/nestjs/nest | Official framework - study the source code |
| vladwulf/nestjs-jwts | https://github.com/vladwulf/nestjs-jwts | JWT auth with access + refresh tokens, integration tests |
| abouroubi/nestjs-auth-jwt | https://github.com/abouroubi/nestjs-auth-jwt | JWT auth with short-lived access and long-lived refresh tokens |
| quan-vu/nestjs-auth-jwt-template | https://github.com/quan-vu/nestjs-auth-jwt-template | Simple JWT auth template with registration and login |
| leduyminh48/nestjs-oauth2-example | https://github.com/leduyminh48/nestjs-oauth2-example | Complete OAuth2 provider implementation |
| boybothere/google-oauth2-nestjs | https://github.com/boybothere/google-oauth2-nestjs | Google OAuth2 with session management |
| NarHakobyan/awesome-nest-boilerplate | https://github.com/NarHakobyan/awesome-nest-boilerplate | Enterprise boilerplate with TypeORM, Swagger, JWT |

---

> Total resources: 150+ | Last updated: 2026-03-15
> All URLs verified through web search results


---

# Part 2: ORMs, Databases & Design Patterns

# Advanced Node.js + TypeScript Learning Resources
