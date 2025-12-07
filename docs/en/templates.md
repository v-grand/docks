# Project Templates

This section describes the standardized templates used to create new platform components.

---

### `template-platform`

**Purpose:** Main repository: combines all services, manages startup and CI/CD
**Inherits from:** —

---

### `template-service`

**Purpose:** Basic microservice (Model + Controller), Docker, tests, CI
**Inherits from:** —

---

### `template-docs`

**Purpose:** Project documentation (MkDocs + Material, Jupyter, GitHub Pages)
**Inherits from:** —

---

### `template-infra-deployer`

**Purpose:** CLI/service for deploying infrastructure (Terraform, Helm, Ansible)
**Inherits from:** —

---

### `template-frontend`

**Purpose:** SPA-client (React/Vue), Web3 connection, build, deploy
**Inherits from:** —

---

### `template-model`

**Purpose:** Data models, ORM, migrations, business logic
**Inherits from:** template-service

---

### `template-controller`

**Purpose:** REST/GraphQL API, validation, OpenAPI, connection to models
**Inherits from:** template-service

---

### `template-worker`

**Purpose:** Asynchronous tasks, queues, cron, Celery/RQ
**Inherits from:** template-service

---

### `template-llm-router`

**Purpose:** Service for routing between LLMs (GigaChat, YandexGPT, Ollama, etc.)
**Inherits from:** template-service

---

### `template-nft-service`

**Purpose:** Minting and managing NFTs, interacting with blockchain
**Inherits from:** template-service

---

### `template-wallet-service`

**Purpose:** Working with Web3 wallets, signing transactions, storing addresses
**Inherits from:** template-service

---

### `template-payment-service`

**Purpose:** Accepting crypto payments, integration with Web3 and fiat gateways
**Inherits from:** template-service

---

### `template-monitoring`

**Purpose:** Prometheus, Grafana, Loki, alerts, exporters
**Inherits from:** —

---

### `template-testing`

**Purpose:** Integration and e2e tests (pytest, Playwright, Postman, k6)
**Inherits from:** —

---

### `template-lab`

**Purpose:** Isolated laboratories: scenarios, environments, mini-platforms
**Inherits from:** template-platform

---

### `template-devtools`

**Purpose:** Set of utilities, CLI, generators, pre-commit hooks
**Inherits from:** —

---

### `template-course`

**Purpose:** Training courses, tutorials, steps, assignments
**Inherits from:** template-docs

---

### `template-demo`

**Purpose:** Demo examples, showcase, public stands
**Inherits from:** template-platform
