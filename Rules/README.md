# Rules Structure

Эта папка содержит правила (rules) для Cursor, организованные по категориям для удобного использования в различных типах проектов.

## Структура категорий

### Backend
- `backend/` - Backend фреймворки и библиотеки (Express, NestJS, FastAPI, Django, Flask, Laravel, Spring, etc.)

### Frontend
- `frontend/` - Frontend фреймворки и библиотеки (React, Vue, Angular, Next.js, Nuxt, Svelte, TypeScript, CSS, etc.)

### Языки программирования
- `dotnet/` - .NET и C# правила
- `python/` - Python и экосистема Python
- `go/` - Go язык и фреймворки
- `rust/` - Rust язык и фреймворки
- `java/` - Java и экосистема Java
- `javascript/` - JavaScript runtime (Node.js, Bun, Deno)
- `php/` - PHP и фреймворки
- `ruby/` - Ruby и фреймворки

### Mobile
- `mobile/` - Мобильная разработка (Android, React Native, Flutter, Ionic, Expo, etc.)

### Database
- `database/` - Базы данных (PostgreSQL, MongoDB, Redis, SQLite, Elasticsearch, etc.)

### Cloud
- `cloud/` - Облачные платформы (AWS, Azure, GCP, Cloudflare, Heroku, Vercel, etc.)

### DevOps
- `devops/` - DevOps инструменты (Docker, Kubernetes, Terraform, Ansible, Nginx, etc.)

### CI/CD
- `ci-cd/` - Инструменты CI/CD (GitHub Actions, GitLab CI, CircleCI, Jenkins, etc.)

### Testing
- `testing/` - Инструменты тестирования (Jest, Vitest, Cypress, Playwright, Puppeteer, Selenium, etc.)

### AI/ML
- `ai-ml/` - Искусственный интеллект и машинное обучение (OpenAI, LangChain, Transformers, etc.)

### Tools
- `tools/` - Различные инструменты разработки (Git, Bash, Vim, Emacs, Postman, etc.)

### Game Development
- `game-dev/` - Разработка игр (Unity, Unreal Engine, Godot, Pygame, etc.)

### API
- `api/` - API сервисы и интеграции (Stripe, Auth0, Firebase, Supabase, etc.)

### UI Frameworks
- `ui-frameworks/` - UI библиотеки (Material-UI, Ant Design, Chakra UI, Tailwind, etc.)

### State Management
- `state-management/` - Управление состоянием (Redux, MobX, Zustand, Riverpod, etc.)

### Data Fetching
- `data-fetching/` - Загрузка данных (React Query, Apollo, GraphQL, Axios, etc.)

### Build Tools
- `build-tools/` - Инструменты сборки (Vite, Webpack, Turbopack, esbuild, etc.)

### Validation
- `validation/` - Валидация данных (Zod, Pydantic, etc.)

### ORM
- `orm/` - ORM библиотеки (Prisma, Drizzle, SQLAlchemy, etc.)

### Monitoring
- `monitoring/` - Мониторинг и логирование (Sentry, Datadog, Grafana, etc.)

### Blockchain
- `blockchain/` - Блокчейн разработка (Solidity, Hardhat, etc.)

### Media
- `media/` - Работа с медиа (FFmpeg, etc.)

### Robotics
- `robotics/` - Робототехника (ROS, etc.)

## Использование

Для добавления правил в проект:

1. **Backend проект**: Скопируйте нужные правила из `backend/`, `dotnet/`, `python/`, `go/`, `rust/`, `java/`, `php/`, `ruby/`, `database/`, `orm/`, `api/`, `devops/`, `ci-cd/`, `testing/`, `monitoring/`

2. **Frontend проект**: Скопируйте нужные правила из `frontend/`, `ui-frameworks/`, `state-management/`, `data-fetching/`, `build-tools/`, `validation/`, `testing/`

3. **Mobile проект**: Скопируйте нужные правила из `mobile/`, `frontend/` (если используете React Native), `testing/`

4. **Full-stack проект**: Комбинируйте правила из соответствующих категорий

## Пример структуры для проекта

```
.cursor/
  rules/
    dotnet/
      asp-net.mdc
      c-sharp.mdc
    backend/
      fastapi.mdc
    database/
      postgresql.mdc
    testing/
      pytest.mdc
```

