# Шаблоны проектов

Этот раздел содержит описание стандартизированных шаблонов, используемых для создания новых компонентов платформы.

---

### `template-platform`

**Назначение:** Главный репозиторий: объединяет все сервисы, управляет запуском и CI/CD
**Наследуется от:** —

---

### `template-service`

**Назначение:** Базовый микросервис (Model + Controller), Docker, тесты, CI
**Наследуется от:** —

---

### `template-docs`

**Назначение:** Документация проекта (MkDocs + Material, Jupyter, GitHub Pages)
**Наследуется от:** —

---

### `template-infra-deployer`

**Назначение:** CLI/сервис для развёртывания инфраструктуры (Terraform, Helm, Ansible)
**Наследуется от:** —

---

### `template-frontend`

**Назначение:** SPA-клиент (React/Vue), подключение к Web3, сборка, деплой
**Наследуется от:** —

---

### `template-model`

**Назначение:** Модели данных, ORM, миграции, бизнес-логика
**Наследуется от:** template-service

---

### `template-controller`

**Назначение:** REST/GraphQL API, валидация, OpenAPI, подключение к моделям
**Наследуется от:** template-service

---

### `template-worker`

**Назначение:** Асинхронные задачи, очереди, cron, Celery/RQ
**Наследуется от:** template-service

---

### `template-llm-router`

**Назначение:** Сервис маршрутизации между LLM (GigaChat, YandexGPT, Ollama и др.)
**Наследуется от:** template-service

---

### `template-nft-service`

**Назначение:** Минтинг и управление NFT, взаимодействие с блокчейном
**Наследуется от:** template-service

---

### `template-wallet-service`

**Назначение:** Работа с Web3-кошельками, подпись транзакций, хранение адресов
**Наследуется от:** template-service

---

### `template-payment-service`

**Назначение:** Приём крипто-платежей, интеграция с Web3 и fiat-шлюзами
**Наследуется от:** template-service

---

### `template-monitoring`

**Назначение:** Prometheus, Grafana, Loki, алерты, экспортёры
**Наследуется от:** —

---

### `template-testing`

**Назначение:** Интеграционные и e2e-тесты (pytest, Playwright, Postman, k6)
**Наследуется от:** —

---

### `template-lab`

**Назначение:** Изолированные лаборатории: сценарии, окружения, мини-платформы
**Наследуется от:** template-platform

---

### `template-devtools`

**Назначение:** Набор утилит, CLI, генераторов, pre-commit хуков
**Наследуется от:** —

---

### `template-course`

**Назначение:** Учебные курсы, туториалы, шаги, задания
**Наследуется от:** template-docs

---

### `template-demo`

**Назначение:** Демо-примеры, showcase, публичные стенды
**Наследуется от:** template-platform
