# GitHub Portfolio Dashboard

[English](README.md) | [Русский](README.ru.md)

**Публичный дашборд:** https://github-profile-dashboard-vite.vercel.app/  
**GitHub Pages:** https://ekatmoz88-alt.github.io/github-profile-dashboard-vite-public/  

## Назначение

Дашборд показывает выбранные кейсы технического письма и динамический список публичных репозиториев GitHub-аккаунта.

## Состав дашборда

- **6 избранных карточек** — отобранные кейсы технического письма.
- Динамический индекс публичных репозиториев загружается через GitHub API.
- Материалы по ППО «Территория» и связанным компонентам представлены как единый документационный проект.

## Избранные направления

- [ППО «Территория» и связанные компоненты](https://github.com/ekatmoz88-alt/territory-descriptor-unified-public) — единый документационный проект, объединяющий материалы по системе «Территория», АРМ «Дискриптор», «Дешифратор» и связанным программным компонентам. [Архитектурный каталог EN/RU](https://ekatmoz88-alt.github.io/territory-descriptor-unified-public/materials/architecture/architecture.html) · [Контекст системы и границы — RU](https://github.com/ekatmoz88-alt/territory-descriptor-unified-public/blob/main/materials/architecture/system-context-and-scope.ru.md) · [System context and scope — EN](https://github.com/ekatmoz88-alt/territory-descriptor-unified-public/blob/main/materials/architecture/system-context-and-scope.en.md).
- [Документация «Дешифратора»](https://github.com/ekatmoz88-alt/deshifrator-docs-public) — архитектура, обмен данными, анализ рисков и C# / SQLite data-access layer.
- API documentation и OpenAPI.
- Архитектура корпоративных систем и документация связанных программных компонентов.
- C++ UI component documentation.
- Fintech workflows и security documentation.
- Docs-as-Code и автоматизация QA.
- Hardware documentation.

## Технологии

React 18 · Vite 6 · JavaScript · GitHub REST API · GitHub Actions · GitHub Pages · Vercel.

## Запуск локально

Требования: Node.js 24 и npm.

```bash
npm ci
npm run dev
npm run build
npm run preview
```

## Избранная архитектурная документация

- [Обмен данными и администрирование — RU](https://github.com/ekatmoz88-alt/territory-descriptor-unified-public/blob/main/materials/architecture/data-exchange-and-administration.ru.md)
- [Data exchange and administration — EN](https://github.com/ekatmoz88-alt/territory-descriptor-unified-public/blob/main/materials/architecture/data-exchange-and-administration.en.md)

## Границы и доказательность

Дашборд — индекс портфолио, а не заявление о том, что автор разработал все перечисленные системы. Описания различают документационные кейсы, анализ исходного кода, демонстрационные проекты и исторические системы. Общая навигация не означает общую исполняемую архитектуру.

## Теги

`portfolio-dashboard` · `react` · `vite` · `github-api` · `technical-writing` · `repository-audit` · `en-ru`
