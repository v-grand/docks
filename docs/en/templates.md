# Project Templates

This section describes the standardized templates used to create new platform components.

---

### `template-service`

**Repository:** `https://github.com/v-grand/template-service.git`

This template is for quickly creating new microservices. It includes:

-   A basic Python application structure.
-   A ready-to-use `Dockerfile` for building the service.
-   Configuration examples for local and production environments.
-   A pre-configured CI/CD pipeline.

---

### `template-platform`

**Repository:** `https://github.com/v-grand/template-platform.git`

A template for creating a full-fledged platform from scratch. It combines all other components and serves as a starting point for deploying the entire stack. It includes:

-   A submodule structure for all services and infrastructure repositories.
-   `docker-compose.yml` for local development.
-   A `Makefile` with commands for project management.

---

### `template-docks`

**Repository:** `https://github.com/v-grand/template-docks.git`

A template for creating a documentation site like this one. It includes:

-   A pre-configured `MkDocs` with the `material` theme.
-   Documentation structure examples.
-   A ready-to-use workflow for publishing the site to GitHub Pages.
