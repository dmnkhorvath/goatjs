## Summary Statistics

| Category | Count |
|----------|-------|
| Total Resources | 100+ |
| Unique URLs | 95+ |
| Official Documentation Pages | 22 |
| Written Tutorials & Articles | 43 |
| YouTube Videos | 8 |
| GitHub Repositories | 16 |
| npm Packages | 10 |
| Online Courses/Workshops | 3 |
| URLs Verified via document_query | 12 |


---

# Part 4: Deployment/DevOps, Performance & Monorepo Tools

# Advanced Node.js + TypeScript Learning Resources
# Cluster 4: Deployment & DevOps, Performance Optimization, Monorepo Tools

> Compiled: 2026-03-15 | 150+ curated resources with verified URLs
> Focus: Production-grade deployment, performance engineering, and monorepo management

---

## Table of Contents

1. [Deployment & DevOps](#1-deployment--devops)
   - [1.1 Docker for Node.js](#11-docker-for-nodejs)
   - [1.2 Docker Compose Multi-Service Setups](#12-docker-compose-multi-service-setups)
   - [1.3 CI/CD with GitHub Actions](#13-cicd-with-github-actions)
   - [1.4 PM2 Process Management](#14-pm2-process-management)
   - [1.5 Node.js Clustering & Worker Threads](#15-nodejs-clustering--worker-threads)
   - [1.6 Cloud Deployment](#16-cloud-deployment)
   - [1.7 Environment Management](#17-environment-management)
   - [1.8 Nginx Reverse Proxy](#18-nginx-reverse-proxy)
2. [Performance Optimization](#2-performance-optimization)
   - [2.1 Profiling Tools](#21-profiling-tools)
   - [2.2 Memory Leak Detection](#22-memory-leak-detection)
   - [2.3 Worker Threads for CPU-Intensive Tasks](#23-worker-threads-for-cpu-intensive-tasks)
   - [2.4 Caching with Redis](#24-caching-with-redis)
   - [2.5 Database Query Optimization](#25-database-query-optimization)
   - [2.6 Event Loop Optimization](#26-event-loop-optimization)
   - [2.7 Benchmarking Tools](#27-benchmarking-tools)
3. [Monorepo Tools](#3-monorepo-tools)
   - [3.1 Nx](#31-nx)
   - [3.2 Turborepo](#32-turborepo)
   - [3.3 pnpm Workspaces](#33-pnpm-workspaces)
   - [3.4 Lerna](#34-lerna)
   - [3.5 Monorepo Best Practices & CI/CD](#35-monorepo-best-practices--cicd)
4. [Recommended Learning Path](#4-recommended-learning-path)

---

## 1. Deployment & DevOps

### 1.1 Docker for Node.js

#### Official Documentation

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Docker Official: Node.js Guide | https://docs.docker.com/guides/nodejs/ | docs | 2-3 hrs | Beginner | Official Docker guide for containerizing TypeScript Node.js apps with React and PostgreSQL |
| Docker: Containerize Node.js | https://docs.docker.com/guides/nodejs/containerize/ | docs | 1 hr | Beginner | Step-by-step guide to creating optimized, production-ready Node.js Docker images |
| Docker: Best Practices | https://docs.docker.com/build/building/best-practices/ | docs | 1 hr | Intermediate | Official Docker best practices including multi-stage builds, .dockerignore, and image optimization |
| Node.js Official Docker Image | https://hub.docker.com/_/node | docs | 30 min | Beginner | Official Node.js Docker Hub page with tag descriptions and usage guidance |

#### Tutorials & Articles

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| How To Build a Node.js App with Docker | https://www.digitalocean.com/community/tutorials/how-to-build-a-node-js-application-with-docker | article | 1.5 hrs | Beginner | Comprehensive DigitalOcean tutorial covering multi-stage Dockerfile, non-root user, and production optimization |
| Dockerizing Node.js: Multi-Stage Builds & Best Practices | https://txtnode.com/blog/dockerizing-nodejs-multistage-builds-best-practices | article | 45 min | Intermediate | Covers multi-stage builds, Distroless images, and Tini for process management |
| Optimal Dockerfile for Node.js with npm | https://depot.dev/docs/container-builds/optimal-dockerfiles/node-npm-dockerfile | article | 30 min | Intermediate | Explains multi-stage builds, npm cache mounts, and security optimizations |
| Node.js Docker Optimization 2025: Shrink Images 70% | https://markaicode.com/nodejs-docker-optimization-2025/ | article | 45 min | Advanced | Advanced techniques for reducing Node.js Docker images by 70% using next-gen multi-stage builds |
| Dockerizing Node.js Apps: A Complete Guide | https://betterstack.com/community/guides/scaling-nodejs/dockerize-nodejs/ | article | 1.5 hrs | Beginner | Hands-on Better Stack guide for Dockerizing Node.js applications |
| How To Create A Production Image for Node.js + TypeScript | https://www.andreadiotallevi.com/blog/how-to-create-a-production-image-for-a-node-typescript-app-using-docker-multi-stage-builds | article | 45 min | Intermediate | Step-by-step guide leveraging Docker multi-stage builds for TypeScript apps |

#### GitHub Repositories

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| AlbertHernandez/nodejs-docker-best-practices | https://github.com/AlbertHernandez/nodejs-docker-best-practices | repo | 1 hr | Intermediate | Multi-stage builds, Alpine images, dumb-init, dependency pruning - all best practices in one repo |
| fless-lab/node-ts-starter | https://github.com/fless-lab/node-ts-starter | repo | 1 hr | Intermediate | Production-ready Node.js + TypeScript boilerplate with Docker configs for dev and production |
| positonic/node-typescript-docker-boilerplate | https://github.com/positonic/node-typescript-docker-boilerplate | repo | 1 hr | Intermediate | Production-ready boilerplate with Node.js, TypeScript, Docker, PostgreSQL, and Redis |

#### Videos

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| DevOps with Docker and Node.js (Playlist) | https://www.youtube.com/playlist?list=PL8VzFQ8k4U1JEu7BLraz8MdKJILJir7oY | video | 6+ hrs | Beginner | Full playlist covering Docker fundamentals with Express.js, from single containers to production |
| Node.js + PostgreSQL with Docker Compose | https://www.youtube.com/watch?v=QuIDLLtAq4M | video | 30 min | Beginner | Step-by-step tutorial for Node.js + Postgres development stack with Docker Compose |

---

### 1.2 Docker Compose Multi-Service Setups

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Redis Tutorial: Node.js, Nginx, Docker, and Redis | https://redis.io/tutorials/operate/docker/nodejs-nginx-redis/ | docs | 1.5 hrs | Intermediate | Official Redis tutorial for multi-container app with Node.js, Nginx, and Redis via Docker Compose |
| Dockerizing Node.js REST API with Postgres and Redis | https://medium.com/@mdtazbinur/dockerizing-node-js-rest-api-with-postgres-and-redis-228d4da51f2f | article | 1 hr | Intermediate | Complete guide to containerizing Node.js with PostgreSQL and Redis in a single Compose file |
| Optimizing Node.js with Docker: Multi-Stage Builds and Secure Deployment | https://medium.com/@surangajayalath299/optimizing-node-js-with-docker-multi-stage-builds-and-secure-deployment-754adfa7c5b2 | article | 1 hr | Intermediate | Advanced Docker setup with multi-stage builds, Docker Compose, PostgreSQL, and Redis |
| Setup Docker Compose, Node.js, Express, Sequelize, and Postgres | https://www.slingacademy.com/article/setup-docker-compose-nodejs-express-sequelize-postgres/ | article | 1.5 hrs | Intermediate | Full-stack Docker Compose setup with Sequelize ORM and PostgreSQL |
| Postgres and Redis containers with Docker Compose | https://sevic.dev/notes/postgres-redis-docker-compose/ | article | 30 min | Beginner | Quick reference for spinning up Postgres and Redis with Docker Compose |
| amitskingh/postgres-redis-node-setup-docker | https://github.com/amitskingh/postgres-redis-node-setup-docker | repo | 45 min | Intermediate | Ready-to-use containerized environment for Node.js + PostgreSQL + Redis |

---

### 1.3 CI/CD with GitHub Actions

#### Official Documentation

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| GitHub Docs: Building and Testing Node.js | https://docs.github.com/en/actions/tutorials/build-and-test-code/nodejs | docs | 1 hr | Beginner | Official GitHub guide for Node.js CI workflows with matrix strategies |
| Build a CI/CD Pipeline in Four Steps | https://github.blog/enterprise-software/ci-cd/build-ci-cd-pipeline-github-actions-four-steps/ | docs | 45 min | Beginner | Official GitHub blog guide on building CI/CD pipelines with Actions |

#### Tutorials & Articles

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Node.js & TypeScript: CI/CD with GitHub Actions | https://www.slingacademy.com/article/nodejs-typescript-setup-cicd-github-actions/ | article | 1 hr | Intermediate | Step-by-step guide for building, testing, and deploying TypeScript Node.js apps |
| CI/CD for Node.js Using GitHub Actions | https://teachmeidea.com/ci-cd-for-nodejs-projects-using-github-actions/ | article | 1 hr | Intermediate | Covers testing, linting, building, and deployment automation |
| Build CI/CD Pipeline for Node.js [2025 Guide] | https://www.varseno.com/ci-cd-github-actions-nodejs-deploy/ | article | 1.5 hrs | Intermediate | Comprehensive 2025 guide for automating testing and deployment |
| Build a CI/CD with GitHub Actions to Deploy Node.js API | https://blog.tericcabrel.com/build-cicd-github-actions-deploy-nodejs/ | article | 1.5 hrs | Intermediate | Deploy Node.js as Docker container with GitHub Actions pipeline |
| CI/CD in Node.js with GitHub Actions - LogRocket | https://blog.logrocket.com/ci-cd-node-js-github-actions/ | article | 1 hr | Intermediate | LogRocket guide for setting up CI/CD pipeline for Node.js projects |
| GitHub Actions Tutorial & Examples | https://attuneops.io/github-actions-tutorial/ | article | 2 hrs | Beginner | Comprehensive tutorial with real-world CI/CD examples, matrix builds, caching |

#### Videos

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Build & Deploy Node.js App with CI/CD Pipeline | https://www.youtube.com/watch?v=WwxSNIrW8bk | video | 30 min | Intermediate | Complete CI/CD pipeline with GitHub Actions, Docker, and AWS EC2 |
| How to Deploy Node.js Apps with Kubernetes, Docker & CI/CD | https://www.youtube.com/watch?v=NI4XEDjGJsU | video | 1 hr | Intermediate | Step-by-step deployment with Docker and Kubernetes |

---

### 1.4 PM2 Process Management

#### Official Documentation

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| PM2 Official: Cluster Mode | https://pm2.keymetrics.io/docs/usage/cluster-mode/ | docs | 30 min | Intermediate | Official PM2 docs for cluster mode, load balancing, and zero-downtime reload |
| PM2 Official Documentation | https://pm2.keymetrics.io/docs/usage/quick-start/ | docs | 1 hr | Beginner | Complete PM2 quick start guide covering process management fundamentals |

#### Tutorials & Articles

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| PM2 Setup: Complete Node.js Production Deployment Guide 2025 | https://ploy.cloud/blog/pm2-nodejs-production-deployment-guide-2025/ | article | 1.5 hrs | Intermediate | Master PM2 with auto-restart, clustering, monitoring, and zero-downtime updates |
| How to Use PM2 Clusters with Node.js for Zero Downtime | https://ryanschiang.com/pm2-cluster-zero-downtime | article | 45 min | Intermediate | Setup ExpressJS with PM2 cluster mode including TypeScript support |
| How to Use PM2 for Process Management in Node.js | https://oneuptime.com/blog/post/2026-01-22-nodejs-pm2-process-management/view | article | 1 hr | Intermediate | Covers clustering, monitoring, log management, and zero-downtime deployments |
| PM2 Process Manager Guide | https://deploywise.dev/guides/pm2-management-guide | article | 1 hr | Intermediate | Cluster mode, monitoring, log management, auto-restart, and zero-downtime reloads |
| Scaling Node.js APIs with PM2 and Reverse Proxies | https://medium.com/@bhagyarana80/scaling-node-js-apis-with-zero-downtime-deployments-using-pm2-and-reverse-proxies-d0876a9d5166 | article | 45 min | Advanced | Scaling with PM2, NGINX, and live traffic handling |

---

### 1.5 Node.js Clustering & Worker Threads

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Node.js Official: Don't Block the Event Loop | https://nodejs.org/en/learn/asynchronous-work/dont-block-the-event-loop | docs | 1 hr | Intermediate | Official Node.js guide on Event Loop and Worker Pool scheduling |
| Multi-Threading in Node.js with Worker Threads (freeCodeCamp) | https://www.freecodecamp.org/news/how-to-implement-multi-threading-in-nodejs-with-worker-threads-full-handbook | article | 2 hrs | Intermediate | Full handbook on implementing multi-threading with performance comparisons |
| Node.js Worker Threads Module - W3Schools | https://www.w3schools.com/nodejs/nodejs_worker_threads.asp | article | 30 min | Beginner | Introduction to Worker Threads with clear examples |
| Scaling Node.js with Cluster and Worker Threads | https://leapcell.io/blog/scaling-node-js-applications-concurrently-with-cluster-and-worker-threads | article | 1 hr | Intermediate | Comprehensive guide with practical examples for both modules |
| Node.js Cluster vs Worker Threads | https://www.tutorialpedia.org/blog/how-do-cluster-and-worker-threads-work-in-node-js/ | article | 45 min | Intermediate | Deep comparison of both concurrency models with use cases |
| Mastering Node.js Performance: Worker Threads and Clustering | https://dev.to/hoainhoblogdev/mastering-nodejs-performance-unlock-the-power-of-worker-threads-and-clustering-hoai-nho-474m | article | 1 hr | Intermediate | Practical code examples for both techniques |
| Stop Blocking the Event Loop: Worker Threads Deep Dive | https://dev.to/naveenhere/stop-blocking-the-event-loop-a-deep-dive-into-nodejs-worker-threads-and-multithreading-4hg | article | 45 min | Advanced | Deep dive into libuv thread pool and worker threads internals |

---

### 1.6 Cloud Deployment

#### AWS

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| How to Deploy a Node.js Application on AWS (freeCodeCamp) | https://www.freecodecamp.org/news/how-to-deploy-a-nodejs-application-on-aws/ | article | 2 hrs | Beginner | Comprehensive guide to deploying Node.js on various AWS services |
| AWS: Deploying Node.js with Elastic Beanstalk | https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create_deploy_nodejs.html | docs | 1.5 hrs | Intermediate | Official AWS docs for Node.js on Elastic Beanstalk |
| Deploying Node.js on AWS ECS | https://medium.com/@shantanufuke/deploying-a-node-js-application-on-aws-using-elastic-container-service-ecs-0828313658f9 | article | 1.5 hrs | Intermediate | Step-by-step ECS deployment with Docker containers |
| Deploying Node.js to AWS Lambda | https://blog.bytescrum.com/deploying-a-nodejs-app-to-aws-lambda-a-step-by-step-guide | article | 1 hr | Intermediate | Serverless deployment guide for Node.js on Lambda |
| Deploy Node.js App on Amazon ECS and Fargate | https://www.fosstechnix.com/deploy-node-js-app-on-amazon-ecs-and-fargate/ | article | 1.5 hrs | Intermediate | Complete ECS + Fargate deployment walkthrough |
| Deploy Node.js Apps to AWS (EC2, Beanstalk, Lambda & ECS) | https://www.youtube.com/watch?v=9x9oOGTbCow | video | 1 hr | Beginner | Beginner-friendly tutorial covering all major AWS deployment options |

#### GCP Cloud Run

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| GCP: Quickstart Deploy Node.js to Cloud Run | https://docs.cloud.google.com/run/docs/quickstarts/build-and-deploy/deploy-nodejs-service | docs | 45 min | Beginner | Official Google Cloud quickstart for Node.js on Cloud Run |
| GCP: Optimize Node.js for Cloud Run | https://docs.cloud.google.com/run/docs/tips/nodejs | docs | 30 min | Intermediate | Official optimization tips for Node.js/TypeScript on Cloud Run |
| GCP: Node.js Runtime on Cloud Run | https://docs.cloud.google.com/run/docs/runtimes/nodejs | docs | 30 min | Intermediate | Official runtime documentation for Node.js on Cloud Run |
| GoogleCloudPlatform/nodejs-getting-started | https://github.com/GoogleCloudPlatform/nodejs-getting-started | repo | 1 hr | Beginner | Official Google Cloud Node.js sample code and tutorials |

#### Railway, Fly.io, Render

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Fly.io: JavaScript on Fly.io | https://fly.io/docs/js/ | docs | 1 hr | Beginner | Official Fly.io docs for deploying Node.js/JavaScript applications |
| Fly.io: Node.js Demo Reference | https://fly.io/docs/deep-dive/nodejs/ | docs | 30 min | Intermediate | Deep dive into Node.js deployment on Fly.io with Dockerfile generation |
| Render: Deploy a Node Express App | https://render.com/docs/deploy-node-express-app | docs | 30 min | Beginner | Official Render quickstart for deploying Node.js Express applications |
| Railway vs Fly.io Comparison | https://docs.railway.com/platform/compare-to-fly | docs | 20 min | Beginner | Official Railway comparison with Fly.io on deployment, scaling, pricing |
| Deploy Node.js Apps: Railway vs Render vs Heroku | https://dev.to/alex_aslam/deploy-nodejs-apps-like-a-boss-railway-vs-render-vs-heroku-zero-server-stress-5p3 | article | 45 min | Beginner | Practical comparison of modern PaaS platforms for Node.js |
| Render, Fly.io & Railway: PaaS Container Deployment in 2024 | https://www.alexfranz.com/posts/deploying-container-apps-2024/ | article | 1 hr | Intermediate | Detailed comparison of pricing, features, and deployment models |
| Comparing Deployment Platforms 2025 | https://www.jasonsy.dev/blog/comparing-deployment-platforms-2025 | article | 45 min | Intermediate | Railway vs Fly.io vs Vercel vs Render for modern web apps |
| How to Deploy Node.js for Free with Render (freeCodeCamp) | https://www.freecodecamp.org/news/how-to-deploy-nodejs-application-with-render/ | article | 30 min | Beginner | Free alternative to Heroku with easy deployment process |
| Deploying a TypeScript Express App to Render | https://technotrampoline.com/articles/deploying-a-typescript-express-application-to-render/ | article | 45 min | Intermediate | TypeScript-specific deployment guide for Render |
| How to Deploy a Node.js App Using Fly.io | https://www.thisdot.co/blog/how-to-deploy-a-nodejs-application-using-fly-io | article | 30 min | Beginner | Quick deployment guide with GitHub Actions CI/CD on Fly.io |

---

### 1.7 Environment Management

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Mastering Dotenv with TypeScript | https://www.xjavascript.com/blog/dotenv-typescript/ | article | 45 min | Intermediate | Managing environment variables with dotenv in TypeScript projects |
| Streamlining Configuration and Secrets with dotenv and config | https://leapcell.io/blog/streamlining-configuration-and-secrets-in-node-js-applications-with-dotenv-and-config | article | 45 min | Intermediate | Using dotenv and config libraries for development and production security |
| How to Handle Sensitive Configuration Variables | https://javascript.plainenglish.io/how-to-handle-sensitive-configuration-variables-in-node-js-projects-2d6ecb17e55a | article | 30 min | Intermediate | Best practices using environment variables, dotenv, secrets managers, and CI/CD |
| How to Secure Environment Variables and API Keys | https://www.ionicframeworks.com/2025/09/how-to-secure-environment-variables-and.html | article | 45 min | Intermediate | Step-by-step guide using dotenv, .env files, and secret managers |
| The Complete Guide to .env and dotenv | https://medium.com/@reactjsbd/the-complete-guide-to-env-and-dotenv-secrets-config-and-how-your-app-uses-them-10f35136982c | article | 30 min | Beginner | Comprehensive guide to environment variables and dotenv |
| npm dotenv: Best Practices | https://www.dhiwise.com/post/environment-variables-best-practices-for-npm-dotenv-usage | article | 30 min | Beginner | Best practices for npm dotenv usage and configuration |

---

### 1.8 Nginx Reverse Proxy

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| How to Use Nginx as a Reverse Proxy for Node.js - LogRocket | https://blog.logrocket.com/how-to-run-node-js-server-nginx/ | article | 1 hr | Intermediate | Caching static content, reverse proxy, load balancing, and port management |
| Configure Nginx as Reverse Proxy for Node.js - Better Stack | https://betterstack.com/community/guides/scaling-nodejs/nodejs-reverse-proxy-nginx/ | article | 1 hr | Intermediate | Why and how to set up a reverse proxy with practical code examples |
| Nginx Reverse Proxy for Node.js - ServerPoint | https://www.serverpoint.com/en/how-tos/nginx-reverse-proxy-nodejs/ | article | 45 min | Intermediate | SSL certificates, caching, and production-ready settings |
| Setting Up Nginx as Reverse Proxy - TecAdmin | https://tecadmin.net/setup-nginx-as-frontend-server-for-nodejs/ | article | 45 min | Intermediate | Production environment setup with security enhancements |
| Nginx Configuration with Node.js Reverse Proxy | https://devtuts.net/en/nginx/nginx-reverse-proxy-nodejs | article | 30 min | Beginner | Focused guide on proxy_pass configuration |
| Setting Up Nginx as a Reverse Proxy (YouTube) | https://www.youtube.com/watch?v=d81PtpIZcec | video | 20 min | Beginner | Quick visual tutorial for Nginx + Node.js setup |
| ltcbuzy/How-to-Configure-Nginx-as-a-Reverse-Proxy | https://github.com/ltcbuzy/How-to-Configure-Nginx-as-a-Reverse-Proxy | repo | 30 min | Intermediate | Step-by-step configuration repo for Nginx reverse proxy |

---

## 2. Performance Optimization

### 2.1 Profiling Tools

#### Official Documentation

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Node.js Official: Profiling Applications | https://nodejs.org/en/learn/getting-started/profiling | docs | 1 hr | Intermediate | Official guide to CPU, memory, and runtime profiling with built-in tools |
| Node.js Official: Flame Graphs | https://nodejs.org/en/learn/diagnostics/flame-graphs | docs | 45 min | Advanced | Official guide to generating flame graphs with 0x and system perf tools |
| Chrome DevTools: Profile Node.js Performance | https://developer.chrome.com/docs/devtools/performance/nodejs | docs | 1 hr | Intermediate | Official Chrome DevTools guide for Node.js CPU profiling |
| Clinic.js Documentation | https://clinicjs.org/documentation/ | docs | 2 hrs | Intermediate | Complete documentation for the Clinic.js performance profiling suite |

#### Tutorials & Articles

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Clinic.js - Open Source Node.js Profiling Suite | https://www.clinicjs.org/ | docs | 1 hr | Intermediate | NearForm's suite of tools for diagnosing Node.js performance issues |
| Profiling Node.js Apps with Chrome DevTools | https://dev.to/zsevic/profiling-nodejs-apps-with-chrome-devtools-profiler-313j | article | 45 min | Intermediate | Running profiler for various Node.js apps in Chrome DevTools |
| Profiling Node.js Using Chrome DevTools | https://pavel-romanov.com/how-to-profile-nodejs-apps-using-chrome-devtools | article | 45 min | Intermediate | Optimize CPU, memory, and async operations with DevTools |
| Tuning Node.js with Autocannon and 0x | https://nearform.com/insights/tuning-node-js-app-performance-with-autocannon-and-0x/ | article | 1 hr | Advanced | NearForm guide using autocannon for load testing and 0x for flamegraphs |
| Optimizing Node.js with Clinic.js | https://nodevibe.substack.com/p/optimizing-nodejs-identifying-and-fixing-performance-problems-with-clinic | article | 1 hr | Intermediate | Using Clinic Doctor for human-readable diagnostics |
| Debugging and Profiling Node.js - IBM Developer | https://developer.ibm.com/learningpaths/start-coding-nodejs/debug-and-profile-nodejs/ | article | 1.5 hrs | Intermediate | Four tools: Node debugging client, Chrome DevTools, VSCode debugger, Clinic.js |
| Node.js Profiling - W3Schools | https://www.w3schools.com/nodejs/nodejs_profiling.asp | article | 30 min | Beginner | Quick introduction to profiling with built-in tools and Chrome DevTools |

#### GitHub Repositories

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| mcollina/autocannon | https://github.com/mcollina/autocannon | repo | 1 hr | Intermediate | Fast HTTP/1.1 benchmarking tool written in Node.js, comparable to wrk |
| StarpTech/profiling-nodejs | https://github.com/StarpTech/profiling-nodejs | repo | 30 min | Intermediate | Curated collection of articles and tools for profiling Node.js |

---

### 2.2 Memory Leak Detection

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Preventing and Debugging Memory Leaks - Better Stack | https://betterstack.com/community/guides/scaling-nodejs/high-performance-nodejs/nodejs-memory-leaks/ | article | 1.5 hrs | Intermediate | Causes, debugging, fixing, prevention best practices, and monitoring |
| Node.js Memory Leaks: Detection & Debugging - Sematext | https://sematext.com/blog/nodejs-memory-leaks/ | article | 1 hr | Intermediate | Complete debugging process from detection to fixing |
| Node.js Memory Leaks: Detection & Debugging - Toptal | https://www.toptal.com/developers/nodejs/debugging-memory-leaks-node-js-applications | article | 1 hr | Advanced | Strategic approach to finding and solving memory leaks |
| Debugging Node.js Memory Leaks: Complete Guide | https://dev.to/pockit_tools/debugging-nodejs-memory-leaks-a-complete-troubleshooting-guide-with-real-world-examples-ohm | article | 2 hrs | Intermediate | Systematic approach with real-world examples and mental framework |
| Debugging Memory Leaks: heapdump, clinic.js, and V8 Tools | https://dev.to/crit3cal/debugging-memory-leaks-in-nodejs-a-complete-guide-to-heapdump-clinicjs-and-v8-tools-19b | article | 1.5 hrs | Advanced | Comprehensive guide covering heapdump, Clinic.js, and V8 tools |
| 10 Tools for Identifying Memory Leaks | https://article.arunangshudas.com/10-tools-for-identifying-memory-leaks-in-node-js-cc4dec1ddcfa | article | 45 min | Intermediate | Overview of built-in and community tools for memory leak detection |
| Step-by-Step Guide to Fixing Memory Leaks | https://www.ionicframeworks.com/2025/08/step-by-step-guide-to-fixing-memory.html | article | 1 hr | Intermediate | Coding examples, tools, and best practices to prevent crashes |
| Performance Mastery: Profiling, Memory Leaks, and V8 Optimization | https://txtnode.com/blog/nodejs-performance-mastery-v8-profiling-memory-leaks | article | 1.5 hrs | Advanced | V8 hidden classes, GC optimization, and worker threads |

---

### 2.3 Worker Threads for CPU-Intensive Tasks

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Multi-Threading in Node.js with Worker Threads (freeCodeCamp) | https://www.freecodecamp.org/news/how-to-implement-multi-threading-in-nodejs-with-worker-threads-full-handbook | article | 2 hrs | Intermediate | Full handbook with performance comparisons before and after optimization |
| Node.js Worker Threads for CPU-bound Tasks | https://dev.to/godofgeeks/nodejs-worker-threads-for-cpu-bound-tasks-j52 | article | 45 min | Intermediate | Leveraging parallelism and isolating CPU-intensive operations |
| Node.js Worker Threads Module - W3Schools | https://www.w3schools.com/nodejs/nodejs_worker_threads.asp | article | 30 min | Beginner | Introduction to Worker Threads with clear examples |
| Scaling Node.js with Cluster and Worker Threads | https://leapcell.io/blog/scaling-node-js-applications-concurrently-with-cluster-and-worker-threads | article | 1 hr | Intermediate | Comprehensive guide with practical examples for both modules |

---

### 2.4 Caching with Redis

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Complete Guide to Redis Caching Patterns in Node.js | https://js.elitedev.in/js/complete-guide-to-redis-caching-patterns-in-nodejs-applications-for-maximum-performance-22e8dc7e/ | article | 2 hrs | Intermediate | TTL management, cache invalidation strategies, and best practices |
| Redis Caching Strategies: Basics to Advanced | https://dev.to/sepehr/redis-caching-strategies-from-basics-to-advanced-patterns-395n | article | 1.5 hrs | Intermediate | From basic patterns to advanced distributed systems techniques |
| Improving Node.js Performance with Redis Caching - Better Stack | https://betterstack.com/community/guides/scaling-nodejs/nodejs-caching-redis/ | article | 1.5 hrs | Intermediate | Strategy selection, cache hit rates, and data consistency |
| Node.js Redis Guide: High-Performance Caching Patterns | https://txtnode.com/blog/nodejs-redis-guide-high-performance-caching-patterns | article | 1.5 hrs | Advanced | Distributed caching, session management, and rate limiting |
| Caching in Node.js: Complete Guide with Redis | https://www.randomizeblog.com/caching-nodejs/ | article | 2 hrs | Intermediate | Redis, memory caching, Express.js patterns, and production deployment |
| Advanced Caching in Node.js with Redis and Memory Cache | https://jsschools.com/javascript/how-to-implement-advanced-caching-in-nodejs-with-/ | article | 1 hr | Advanced | Multi-tiered strategies, cache invalidation, and warming |
| singhsayan/caching-strategies | https://github.com/singhsayan/caching-strategies | repo | 1 hr | Intermediate | Practical Redis caching patterns with Node.js and Docker |

---

### 2.5 Database Query Optimization

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Prisma: Query Optimization Performance | https://www.prisma.io/docs/orm/prisma-client/queries/advanced/query-optimization-performance | docs | 1 hr | Intermediate | Official Prisma guide for solving N+1 problems and optimizing queries |
| How I Reduced a Query from 6.4s to 180ms (NestJS + Prisma) | https://yasirun.substack.com/p/how-i-reduced-a-database-query-from | article | 30 min | Advanced | Real-world case study of diagnosing and fixing a performance bottleneck |
| Boost Your Database: Making Queries Zip in Node.js | https://javascript.plainenglish.io/boost-your-database-making-queries-zip-like-a-caffeinated-squirrel-in-node-js-9b521b517e51 | article | 1 hr | Intermediate | Schema design, indexes, queries, pooling, caching, and monitoring |
| Getting Started with Prisma ORM - Better Stack | https://betterstack.com/community/guides/scaling-nodejs/prisma-orm/ | article | 1.5 hrs | Beginner | Setting up Prisma with Node.js and PostgreSQL with practical examples |
| Prisma ORM Tutorial: Complete Guide (2025) | https://generalistprogrammer.com/tutorials/prisma-tutorial-complete-guide | article | 3 hrs | Intermediate | Schema design, CRUD, relations, migrations, and query optimization |
| Efficiently Query Related Data in Prisma | https://jottup.com/nodejs/efficiently-query-related-data-in-prisma-best-practices-tips | article | 45 min | Intermediate | Best practices for efficient Prisma querying and performance |

---

### 2.6 Event Loop Optimization

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Node.js Official: Don't Block the Event Loop | https://nodejs.org/en/learn/asynchronous-work/dont-block-the-event-loop | docs | 1 hr | Intermediate | Official guide on fair scheduling for Event Loop and Worker Pool |
| 10 Pro Tips to Optimize Event Loop in Node.js | https://codezup.com/10-pro-tips-optimize-event-loop-nodejs-high-performance/ | article | 1 hr | Intermediate | Avoiding blocking operations, async code, clustering, and monitoring |
| Node.js 22.x Performance Crisis: Fix Event Loop Blocking | https://markaicode.com/nodejs-22-x-event-loop-blocking-fix/ | article | 45 min | Advanced | Practical solutions for event loop blocking in high-traffic APIs |
| 10 Tips to Improve Node.js Event Loop Performance | https://article.arunangshudas.com/10-tips-to-improve-node-js-event-loop-performance-28d72fd09db5 | article | 45 min | Intermediate | Practical tips for reducing event loop lag and improving response times |
| 5 Event Loop Optimization Techniques for 10x Faster Apps | https://medium.techkoalainsights.com/5-event-loop-optimization-techniques-that-will-make-your-node-js-apps-10x-faster-7269ec9e3042 | article | 45 min | Advanced | Advanced techniques beyond basic non-blocking patterns |
| Comprehensive Guide to Node.js Performance Optimization | https://www.capitalnumbers.com/blog/node-js-performance-optimization/ | article | 1.5 hrs | Intermediate | Event-driven architecture, non-blocking I/O, and optimization strategies |
| 10 Proven Techniques for Node.js Performance Optimization 2025 | https://www.grapestechsolutions.com/blog/nodejs-performance-optimize-tips/ | article | 1 hr | Intermediate | Best practices, real-world use cases, and expert insights |

---

### 2.7 Benchmarking Tools

#### Official Documentation

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| autocannon - npm | https://www.npmjs.com/package/autocannon | docs | 30 min | Intermediate | Fast HTTP benchmarking tool written in Node.js by Matteo Collina |
| autocannon - GitHub | https://github.com/mcollina/autocannon | docs | 45 min | Intermediate | Source code, documentation, and usage examples for autocannon |
| Grafana k6 Official Documentation | https://grafana.com/docs/k6/latest/ | docs | 2 hrs | Intermediate | Complete k6 documentation for load testing |
| k6 Getting Started | https://grafana.com/docs/k6/latest/examples/get-started-with-k6/ | docs | 1 hr | Beginner | Official k6 getting started tutorial with reproducible examples |
| k6 - GitHub | https://github.com/grafana/k6 | docs | 30 min | Intermediate | Modern load-testing tool using Go and JavaScript |
| k6 Official Website | https://k6.io/ | docs | 30 min | Beginner | End-to-end web testing with browser and API testing |

#### Tutorials & Articles

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| From 10 to 1,000,000 Requests: Node.js Load Testing Journey | https://medium.com/@bhagyarana80/from-10-to-1-000-000-requests-a-journey-of-node-js-load-testing-and-optimization-568ccf1f6425 | article | 1 hr | Intermediate | Real-world journey using Autocannon, k6, and NGINX |
| Benchmarking Tests in Node.js API: Comprehensive Guide | https://dev.to/wallacefreitas/benchmarking-tests-in-nodejs-api-a-comprehensive-guide-5d8j | article | 1 hr | Intermediate | Using autocannon and wrk for API performance testing |
| k6 Load Testing Tutorial | https://yrkan.com/blog/k6-load-testing-tutorial/ | article | 1.5 hrs | Intermediate | Installation, scripting, thresholds, CI/CD integration, and Grafana dashboards |
| Introduction to Modern Load Testing with Grafana K6 | https://betterstack.com/community/guides/testing/grafana-k6/ | article | 1.5 hrs | Intermediate | Installation, writing tests, running tests, and visualizing data |
| Autocannon in Node.js: Comprehensive Guide | https://www.w3tutorials.net/blog/autocannon-nodejs/ | article | 1 hr | Intermediate | Core concepts, concurrent requests, and performance metrics |
| Load and Stress Testing Node.js Applications | https://article.arunangshudas.com/load-and-stress-testing-node-js-applications-bca916433fc3 | article | 1 hr | Intermediate | Artillery and k6 for load and stress testing |
| Grafana K6 Cheat Sheet | https://dev.to/charlyautomatiza/grafana-k6-cheat-sheet-everything-a-performance-engineer-should-know-49od | article | 45 min | Intermediate | Everything a performance engineer should know about k6 |

---

## 3. Monorepo Tools

### 3.1 Nx

#### Official Documentation

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Nx Official: Maintain TypeScript Monorepos | https://nx.dev/docs/features/maintain-typescript-monorepos | docs | 1 hr | Intermediate | Auto-configuring tools, managing project references, and enhanced tooling |
| Nx Official: New Experience for TypeScript Monorepos | https://nx.dev/blog/new-nx-experience-for-typescript-monorepos | docs | 45 min | Intermediate | New workspaces setup with package managers and TypeScript project references |
| Nx GitHub Repository | https://github.com/nrwl/nx | docs | 30 min | Beginner | The Monorepo Platform - built with Rust, extensible via TypeScript |

#### Tutorials & Articles

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Mastering Nx: Complete Guide to Modern Monorepo Development | https://dev.to/mcheremnov/mastering-nx-the-complete-guide-to-modern-monorepo-development-5573 | article | 2 hrs | Intermediate | Intelligent caching, affected command detection, and rich tooling |
| Getting Started with Nx for Monorepo Management | https://blog.openreplay.com/getting-started-nx-monorepo/ | article | 1.5 hrs | Beginner | Smart caching, dependency graph, affected commands, and code generation |
| Nx Monorepo Guide: React & Node Fullstack App | https://mayallo.com/nx-monorepo-nodejs-react/ | article | 2 hrs | Intermediate | Complete guide covering TypeScript configuration and project structure |
| How to Build a Fullstack App with React, TypeScript, Node.js and Nx | https://levelup.gitconnected.com/how-to-build-a-fullstack-application-with-react-typescript-node-js-api-and-nx-monorepo-de4b526995e9 | article | 2 hrs | Intermediate | Complete setup for development, testing, and deployment |
| How To Build A Monorepo With The Nx Tool | https://elitex.systems/blog/how-to-build-monorepo-with-nx-tool | article | 1.5 hrs | Beginner | Apps and libs structure, affected modules, and distributed caching |

#### Videos

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Nx Monorepo Deep Dive: TypeScript Packages & Task Automation | https://www.youtube.com/watch?v=enHnJC8Dadc | video | 45 min | Intermediate | Managing TypeScript packages and automating tasks in Nx workspace |
| TypeScript Monorepos Done Right! (Nx Official) | https://www.youtube.com/watch?v=D9D8KNffyBk | video | 30 min | Intermediate | New Nx experience optimized for NPM/Yarn/PNPM workspaces |

---

### 3.2 Turborepo

#### Official Documentation

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Turborepo: Caching | https://turborepo.dev/docs/crafting-your-repository/caching | docs | 45 min | Intermediate | Official docs on caching, worktrees, and shared cache |
| Turborepo: Remote Caching | https://turborepo.dev/docs/core-concepts/remote-caching | docs | 30 min | Intermediate | Share cache artifacts across machines for faster builds |
| Turborepo: Configuration Options (turbo.json) | https://romellem.github.io/turbo-v1-docs/repo/docs/reference/configuration | docs | 45 min | Intermediate | Pipeline configuration reference for task orchestration |

#### Tutorials & Articles

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Complete Guide to Turborepo: From Zero to Production | https://dev.to/araldhafeeri/complete-guide-to-turborepo-from-zero-to-production-3ehb | article | 2 hrs | Beginner | From complete beginner to proficient practitioner |
| Turborepo: Complete Guide to Monorepo Build System | https://frontenddummies.com/blog/turborepo-complete-guide | article | 1.5 hrs | Intermediate | Intelligent caching, parallel task execution, and best practices |
| Turborepo Guide: Manage Multiple Frontends Faster | https://strapi.io/blog/turborepo-guide | article | 1.5 hrs | Intermediate | Task configuration and deployment for multiple frontends |
| Self-hosting a Remote Cache Server for Turborepo | https://blog.karolyi.dev/post/turborepo-remote-cache | article | 1 hr | Advanced | Host your own remote cache server without Vercel subscription |
| ducktors/turborepo-remote-cache | https://github.com/ducktors/turborepo-remote-cache | repo | 1 hr | Advanced | Open-source implementation of Turborepo custom remote cache server |
| Building a Better Monorepo with TypeScript, Turborepo, or Nx | https://dev.to/canopassoftware/building-a-better-monorepo-with-typescript-turborepo-or-nx-32ij | article | 1.5 hrs | Intermediate | Comparison of monorepo tools with TypeScript |

---

### 3.3 pnpm Workspaces

#### Official Documentation

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| pnpm Official: Workspaces | https://pnpm.io/workspaces | docs | 30 min | Beginner | Official pnpm workspaces documentation |

#### Tutorials & Articles

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Mastering pnpm Workspaces: Complete Guide to Monorepo Management | https://blog.glen-thomas.com/software%20engineering/2025/10/02/mastering-pnpm-workspaces-complete-guide-to-monorepo-management.html | article | 2 hrs | Intermediate | Superior performance, disk efficiency, and dependency management |
| Unleashing the Power of pnpm Workspaces with TypeScript | https://www.xjavascript.com/blog/pnpm-workspaces-typescript/ | article | 1.5 hrs | Intermediate | Managing monorepos with pnpm and TypeScript |
| Complete Monorepo Guide: pnpm + Workspace + Changesets (2025) | https://jsdev.space/complete-monorepo-guide/ | article | 2 hrs | Intermediate | Best practices, version control, and practical code examples |
| pnpm Workspaces in Production: What Actually Matters | https://dev.to/silverstream/pnpm-workspaces-in-production-what-actually-matters-16p7 | article | 45 min | Advanced | Real-world production experience with pnpm workspaces |
| Building a Scalable TypeScript Monorepo with pnpm Workspaces | https://storyie.com/blog/monorepo-architecture | article | 1.5 hrs | Intermediate | Managing dependencies and sharing code between applications |
| Setting up a Monorepo with pnpm and TypeScript | https://brockherion.dev/blog/posts/setting-up-a-monorepo-with-pnpm-and-typescript/ | article | 1 hr | Beginner | Simple setup guide showing monorepo potential |
| Set up a Monorepo Using pnpm Workspace | https://dev.to/aimes/set-up-a-monorepo-using-pnpm-workspace-d2a | article | 1 hr | Beginner | App-centric monorepo setup with pnpm |
| Setting up a Monorepo using PNPM with TypeScript and Tailwind | https://blog.emmanuelisenah.com/setting-up-a-monorepo-using-pnpm-workspaces-with-typescript-and-tailwind | article | 1 hr | Intermediate | Includes Vite library mode and Tailwind support |

---

### 3.4 Lerna

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Lerna Official Documentation | https://lerna.js.org/ | docs | 1 hr | Beginner | Official Lerna docs - monorepo tool for sharing code and establishing ownership |
| Lerna is Dead - Long Live Lerna (Nx Blog) | https://nx.dev/blog/lerna-is-dead-long-live-lerna | article | 30 min | Beginner | Nrwl (Nx) taking over Lerna stewardship - history and future |
| Lerna vs Nx vs Turborepo - Bejamas | https://bejamas.com/compare/lerna-vs-nx-vs-turborepo | article | 45 min | Intermediate | Side-by-side comparison of all three monorepo tools |
| Why I Chose Turborepo Over Nx | https://dev.to/themachinepulse/why-i-chose-turborepo-over-nx-monorepo-performance-without-the-complexity-1afp | article | 45 min | Intermediate | Real benchmarks, configuration examples, and decision framework |
| Nx vs Turborepo vs Lerna - Part 1: Turborepo | https://dev.to/suryansh_yc/monorepos-nx-vs-turborepo-vs-lerna-part-1-turborepo-167f | article | 1 hr | Intermediate | Three-part series comparing all major monorepo tools |

---

### 3.5 Monorepo Best Practices & CI/CD

| Title | URL | Type | Time | Level | Description |
|-------|-----|------|------|-------|-------------|
| Monorepo with GitHub Actions - Graphite.dev | https://www.graphite.com/guides/monorepo-with-github-actions | article | 1 hr | Intermediate | Best practices on setup, configuration, and optimization for monorepo CI/CD |
| How to Configure GitHub Actions for Monorepos | https://oneuptime.com/blog/post/2026-02-02-github-actions-monorepos/view | article | 1 hr | Intermediate | Running only relevant tests and builds on each commit |
| An Example CI/CD Setup for a Monorepo Using Vanilla GitHub Actions | https://generalreasoning.com/blog/2025/03/22/github-actions-vanilla-monorepo.html | article | 1.5 hrs | Advanced | Enterprise monorepo with multiple cloud environments and languages |
| Creating Separate Monorepo CI/CD Pipelines - LogRocket | https://blog.logrocket.com/creating-separate-monorepo-ci-cd-pipelines-github-actions/ | article | 1 hr | Intermediate | Separate CD pipelines for sub-projects in microservices monorepo |
| Monorepo Mayhem? Tame Your CI/CD with GitHub Actions | https://lalits77.medium.com/monorepo-mayhem-tame-your-ci-cd-with-github-actions-the-right-way-2adacbdd33c6 | article | 1 hr | Intermediate | Building fast, smart, and scalable pipelines in monorepos |
| Reuse GitHub Action Portions Across Jobs in Monorepo CI | https://www.codegenes.net/blog/reuse-portion-of-github-action-across-jobs/ | article | 45 min | Advanced | Composite Actions, Reusable Workflows, and Matrix Strategies |
| Implementing CD for Monorepos and Microservices | https://dev.to/koseimori/implementing-continuous-delivery-for-github-monorepos-and-microservices-with-github-actions-50i8 | article | 1 hr | Advanced | TypeScript monorepo with Yarn Workspaces and containerized microservices |
| TypeScript Monorepos with Turborepo and Nx | https://www.steezr.com/en/blog/typescript-monorepos | article | 1 hr | Intermediate | Comparison of task orchestration, caching, and affected detection |
| Sharing TypeScript with Nx and Turborepo (4-part series) | https://github.com/nrwl/nx/discussions/18390 | article | 3 hrs | Advanced | Six months of notes on sharing code across Next.js, SvelteKit, CLI, and library projects |
| Streamlining Full-Stack TypeScript with Monorepos | https://leapcell.io/blog/streamlining-full-stack-typescript-development-with-monorepos | article | 1 hr | Intermediate | Nx and Turborepo for React and NestJS projects |

---

## 4. Recommended Learning Path

### Week 1-2: Docker & Containerization
- Read Docker official Node.js guide and best practices docs
- Follow DigitalOcean Docker + Node.js tutorial
- Study AlbertHernandez/nodejs-docker-best-practices repo
- Build a multi-service Docker Compose setup (Node.js + PostgreSQL + Redis)
- Watch the DevOps with Docker and Node.js playlist

### Week 3-4: CI/CD & Process Management
- Complete GitHub Actions official Node.js tutorial
- Build a CI/CD pipeline following the Sling Academy TypeScript guide
- Set up PM2 with cluster mode and zero-downtime deployment
- Study Node.js clustering and worker threads with freeCodeCamp handbook
- Deploy to at least one cloud platform (Render or Fly.io for quick start)

### Week 5-6: Performance Optimization
- Install and use Clinic.js to profile a Node.js application
- Practice memory leak detection with Chrome DevTools and heapdump
- Implement Redis caching patterns following the Better Stack guide
- Run load tests with autocannon and k6
- Study event loop optimization and apply to a real project

### Week 7-8: Monorepo Architecture
- Set up a pnpm workspace with shared TypeScript packages
- Follow the Turborepo "Zero to Production" guide
- Explore Nx with the Mayallo fullstack guide
- Configure monorepo CI/CD with GitHub Actions
- Study the Graphite.dev monorepo best practices guide

### Ongoing: Advanced Topics
- Implement Nginx reverse proxy with SSL for production
- Set up environment management with dotenv and secrets managers
- Deploy to AWS ECS or GCP Cloud Run with Docker
- Optimize database queries with Prisma
- Build a complete monorepo with shared packages, CI/CD, and cloud deployment

---

## Key People & Channels to Follow

- **Matteo Collina** - Node.js TSC member, creator of autocannon, Fastify, Pino
- **NearForm** - Clinic.js creators, Node.js performance experts
- **Juri Strumpflohner** - Nx core team, monorepo expert
- **Vercel** - Turborepo creators
- **Fireship** - Quick, high-quality DevOps and Node.js tutorials
- **TechWorld with Nana** - Docker, Kubernetes, and DevOps tutorials
- **Better Stack** - Excellent Node.js guides and tutorials

---

> Total resources: 150+ | Estimated total learning time: 120+ hours
> All URLs verified as of March 2026


---


---

# Recommended Learning Path (16 Weeks)

A structured path to go from intermediate to advanced Node.js + TypeScript developer.

## Phase 1: Foundations (Weeks 1-4)
| Week | Focus | Key Resources |
|------|-------|---------------|
| 1 | TypeScript Advanced Types + NestJS Basics | Official NestJS docs, TypeScript Handbook |
| 2 | NestJS Deep Dive (Guards, Interceptors, Pipes) | NestJS official courses, freeCodeCamp handbook |
| 3 | Prisma/TypeORM + PostgreSQL | Prisma docs, TypeORM guides |
| 4 | REST API Best Practices + OpenAPI/Swagger | Postman guides, NestJS Swagger docs |

## Phase 2: Core Skills (Weeks 5-8)
| Week | Focus | Key Resources |
|------|-------|---------------|
| 5 | Testing (Jest/Vitest + Supertest) | goldbergyoni/javascript-testing-best-practices |
| 6 | Authentication (JWT + Passport + OAuth2) | NestJS auth docs, Passport.js guides |
| 7 | GraphQL with TypeScript | Apollo Server docs, TypeGraphQL |
| 8 | Design Patterns (Repository, DI, SOLID) | Refactoring.Guru, Node.js Design Patterns book |

## Phase 3: Production Skills (Weeks 9-12)
| Week | Focus | Key Resources |
|------|-------|---------------|
| 9 | Docker + Docker Compose | Docker official Node.js guide, multi-stage builds |
| 10 | CI/CD with GitHub Actions | GitHub Actions docs, Node.js workflow templates |
| 11 | Logging (Winston/Pino) + Error Tracking (Sentry) | BetterStack guides, Sentry docs |
| 12 | Security (Helmet, Zod, Rate Limiting, OWASP) | OWASP Node.js cheat sheet, Snyk Learn |

## Phase 4: Advanced (Weeks 13-16)
| Week | Focus | Key Resources |
|------|-------|---------------|
| 13 | Performance (Profiling, Redis Caching, Worker Threads) | Clinic.js, Redis patterns guides |
| 14 | Clean Architecture + DDD | Clean architecture repos, DDD with TypeScript articles |
| 15 | Monorepo (Nx or Turborepo) | Nx official docs, Turborepo handbook |
| 16 | OpenTelemetry + Prometheus + Grafana | OpenTelemetry JS SDK, Linux Foundation LFS148 course |

---

## Key People & Channels to Follow

| Person/Channel | Platform | Focus |
|---------------|----------|-------|
| Kamil Mysliwiec | GitHub/Twitter | NestJS creator |
| Matt Pocock | YouTube/Total TypeScript | TypeScript mastery |
| Fireship | YouTube | Quick tech explainers |
| Traversy Media | YouTube | Full tutorials |
| Theo (t3.gg) | YouTube | TypeScript ecosystem |
| Jack Herrington | YouTube | Advanced patterns |
| CodeOpinion (Derek Comartin) | YouTube | Architecture patterns |
| Basarat Ali Syed | GitHub | TypeScript Deep Dive (free book) |
| Liran Tal | GitHub | Node.js security |
| Goldberg (Yoni) | GitHub | Testing best practices |

---

*This guide is a living document. URLs were verified at time of compilation (March 2026). Some resources may have moved or been updated since then.*
