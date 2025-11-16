# Cursor Utils

Централизованное хранилище правил (rules) и команд (commands) для Cursor, организованное по категориям для удобного использования в различных типах проектов.

## Структура

```
Cursor-utils/
├── rules/           # Правила для различных технологий и фреймворков
│   ├── dotnet/      # .NET и C# правила
│   ├── frontend/    # Frontend фреймворки и библиотеки
│   ├── backend/     # Backend фреймворки
│   ├── python/      # Python экосистема
│   ├── go/          # Go язык
│   ├── rust/        # Rust язык
│   ├── java/        # Java экосистема
│   ├── javascript/  # JavaScript runtime
│   ├── php/         # PHP фреймворки
│   ├── ruby/        # Ruby фреймворки
│   ├── mobile/      # Мобильная разработка
│   ├── database/    # Базы данных
│   ├── cloud/       # Облачные платформы
│   ├── devops/      # DevOps инструменты
│   ├── ci-cd/       # CI/CD инструменты
│   ├── testing/     # Инструменты тестирования
│   ├── ai-ml/       # AI/ML библиотеки
│   ├── tools/       # Инструменты разработки
│   ├── game-dev/    # Разработка игр
│   ├── api/         # API сервисы
│   ├── ui-frameworks/      # UI библиотеки
│   ├── state-management/   # Управление состоянием
│   ├── data-fetching/       # Загрузка данных
│   ├── build-tools/         # Инструменты сборки
│   ├── validation/          # Валидация данных
│   ├── orm/                 # ORM библиотеки
│   ├── monitoring/          # Мониторинг
│   ├── blockchain/          # Блокчейн
│   ├── media/               # Работа с медиа
│   └── robotics/            # Робототехника
│
├── commands/        # Команды для различных задач
│   ├── general/     # Общие команды
│   ├── backend/     # Backend команды
│   ├── frontend/    # Frontend команды
│   ├── devops/      # DevOps команды
│   ├── testing/     # Команды тестирования
│   ├── security/    # Команды безопасности
│   ├── documentation/  # Команды документации
│   ├── git/         # Git команды
│   └── code-quality/    # Команды качества кода
│
├── Mcps/            # MCP серверы
└── prompts/         # Промпты
```

## Использование

### Для Backend проекта (.NET, Python, Go, etc.)

1. Скопируйте нужные правила из соответствующих категорий:
   ```bash
   # Пример для .NET проекта
   cp rules/dotnet/* .cursor/rules/
   cp rules/backend/fastapi.mdc .cursor/rules/  # если используете FastAPI
   cp rules/database/postgresql.mdc .cursor/rules/
   cp rules/testing/pytest.mdc .cursor/rules/
   ```

2. Скопируйте нужные команды:
   ```bash
   cp commands/backend/* .cursor/commands/
   cp commands/general/* .cursor/commands/
   cp commands/testing/* .cursor/commands/
   ```

### Для Frontend проекта (React, Vue, Angular, etc.)

1. Скопируйте нужные правила:
   ```bash
   # Пример для React проекта
   cp rules/frontend/react.mdc .cursor/rules/
   cp rules/frontend/typescript.mdc .cursor/rules/
   cp rules/ui-frameworks/tailwind.mdc .cursor/rules/
   cp rules/state-management/redux.mdc .cursor/rules/
   cp rules/build-tools/vite.mdc .cursor/rules/
   ```

2. Скопируйте нужные команды:
   ```bash
   cp commands/frontend/* .cursor/commands/
   cp commands/general/* .cursor/commands/
   cp commands/testing/* .cursor/commands/
   ```

### Для Full-stack проекта

Комбинируйте правила и команды из соответствующих категорий для backend и frontend частей проекта.

## Категории правил

- **dotnet/** - .NET, ASP.NET, C#
- **frontend/** - React, Vue, Angular, Next.js, Nuxt, Svelte, TypeScript, CSS
- **backend/** - Express, NestJS, FastAPI, Django, Flask, Laravel, Spring
- **python/** - Python, Django, Flask, FastAPI, NumPy, Pandas, PyTorch, TensorFlow
- **go/** - Go, Fiber, Rocket
- **rust/** - Rust, Actix-web
- **java/** - Java, Spring, Spring Boot, JUnit, Maven, Gradle
- **javascript/** - Node.js, Bun, Deno
- **php/** - PHP, Laravel
- **ruby/** - Ruby
- **mobile/** - Android, React Native, Flutter, Ionic, Expo
- **database/** - PostgreSQL, MongoDB, Redis, SQLite, Elasticsearch
- **cloud/** - AWS, Azure, GCP, Cloudflare, Heroku, Vercel
- **devops/** - Docker, Kubernetes, Terraform, Ansible, Nginx
- **ci-cd/** - GitHub Actions, GitLab CI, CircleCI, Jenkins
- **testing/** - Jest, Vitest, Cypress, Playwright, Puppeteer, Selenium
- **ai-ml/** - OpenAI, LangChain, Transformers, PyTorch, TensorFlow
- **tools/** - Git, Bash, Vim, Emacs, Postman
- **game-dev/** - Unity, Unreal Engine, Godot, Pygame
- **api/** - Stripe, Auth0, Firebase, Supabase
- **ui-frameworks/** - Material-UI, Ant Design, Chakra UI, Tailwind
- **state-management/** - Redux, MobX, Zustand, Riverpod
- **data-fetching/** - React Query, Apollo, GraphQL, Axios
- **build-tools/** - Vite, Webpack, Turbopack, esbuild
- **validation/** - Zod, Pydantic
- **orm/** - Prisma, Drizzle, SQLAlchemy
- **monitoring/** - Sentry, Datadog, Grafana
- **blockchain/** - Solidity, Hardhat
- **media/** - FFmpeg
- **robotics/** - ROS

## Категории команд

- **general/** - Общие команды (code-review, refactor-code, optimize-performance, etc.)
- **backend/** - Backend команды (database-migration, add-error-handling)
- **frontend/** - Frontend команды (accessibility-audit)
- **devops/** - DevOps команды
- **testing/** - Команды тестирования (run-all-tests-and-fix, write-unit-tests)
- **security/** - Команды безопасности (security-audit, security-review)
- **documentation/** - Команды документации (add-documentation, generate-api-docs)
- **git/** - Git команды (fix-git-issues, create-pr, address-github-pr-comments)
- **code-quality/** - Команды качества кода (lint-fix, lint-suite)

## Примечания

- Все правила имеют расширение `.mdc`
- Все команды имеют расширение `.md`
- Структура организована для удобного копирования нужных категорий в проекты
- Каждая категория может содержать несколько файлов правил/команд

