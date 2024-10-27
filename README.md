# Systems Project Ideas
This repository is for maintaining project ideas for the Systems and Security SIG.

---

## 1. Create a PostgreSQL Database Extension
- **Details**: Creating an extension for PostgreSQL can be done in C. The usefulness of the extension depends on the problem it aims to solve. For example, we could build an extension that displays the query plan of the SQL engine. Open to additional suggestions for potential functionalities.
- **References**: [List of Extensions](https://gist.github.com/joelonsql/e5aa27f8cc9bd22b8999b7de8aee9d47), [Tutorial](https://www.percona.com/blog/writing-postgresql-extensions-is-fun-c-language/), [Postgres docs for extension](https://www.postgresql.org/docs/current/sql-createextension.html).

## 2. Idea: Build a Serverless Function-as-a-Service (FaaS) Application
- **Details**: Develop a lightweight serverless Function-as-a-Service platform that allows users to deploy and manage isolated functions in response to events. The platform should support multiple languages (e.g., Python, Node.js) and offer features like auto-scaling, event-driven triggers, and simple API integration. Additional functionalities can include a dashboard for monitoring function performance, error logs, and usage metrics.
  
  - **Core Features**:
    - **Multi-language support**: Enable users to deploy functions in various programming languages.
    - **Event-driven triggers**: Integrate with popular services (like HTTP endpoints or message queues) to trigger functions.
    - **Auto-scaling**: Dynamically scale up/down based on workload demands.
    - **Monitoring and logging**: Provide real-time logs, usage metrics, and error tracking for deployed functions.

- **References**: 
  - [AWS Lambda Documentation](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)
  - [Serverless Framework](https://www.serverless.com/)
