# Welcome to Docks

This is the central documentation for our project, describing the architecture, templates, and services.

## 📚 Architecture Overview

The project is built on a microservice architecture using Git submodules to manage dependencies.

```
┌─────────────────────┐
│        docks        │  ← This documentation
└─────────────────────┘
          │
          ├─► template-service (Template for new services)
          ├─► template-platform (Template for a new platform)
          └─► template-docks (Template for documentation)
```

## 🗂️ Repository Guide

### Templates

| Repository | Purpose |
|:------------|:-----------|
| **[template-service]** | Template for creating new microservices. |
| **[template-platform]**| Template for deploying the entire platform. |
| **[template-docks]**   | Template for creating a documentation site. |

## 🚀 Quick Start

### Creating a new service

1. **Clone the template:**
   ```bash
   git clone https://github.com/v-grand/template-service.git my-new-service
   ```

2. **Set up and run:**
   ```bash
   cd my-new-service
   # Follow the instructions in the template's README.md
   ```

## 📖 Documentation Structure

- **[Architecture](architecture.md)** - Description of the project architecture.
- **[Templates](templates.md)** - Detailed description of each template.
