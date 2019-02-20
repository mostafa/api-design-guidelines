# API Design Guidelines

Basic Design Guidelines for Developing &lt;Any Type of> APIs

This project is born from the idea of **Rocky Jaiswal**, which he pointed out in [his tweet](https://twitter.com/var_log_rockyj/status/1097176759542431745) a set of basics to have in mind while developing a new API. I thought that it would be a nice move to make it an open-source awesome-like repository on GitHub for others to be able to contribute to the idea and build upon it.

Here is the initial list which should be expanded:

- Build + dependency management tool (e.g. npm, gradle)
- Testing
  - Unit
  - Integration (request / db level)
  - Contract / Pact
  - CI testing with test DB etc.
- Linting / style check
- Multi env. configuration
  - Local, QA, Production
- Secrets management
- CORS in development
- Hot reload in development (automatic restart)
- JSON + XML parsing / generation
- HTTP client (for service level integration)
- Request param validation
- Logging + log format customization
- DB connection pooling
- ORM / Query builder
- DB migration
- DB seeding / data loading
- Error handling + reporting
- CI / CD
- Code quality measurement
- Dependency Injection (if applicable, for better testable code)
- Authenticated paths / Non-Authenticated paths
- JWT Authentication
- Authorization
- API documentation (e.g. Swagger)
- Docker + Docker-Compose setup
