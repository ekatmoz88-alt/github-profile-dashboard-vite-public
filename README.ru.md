# GitHub Portfolio Dashboard

[English](README.md) | [Русский](README.ru.md)

**Публичный дашборд:** https://github-profile-dashboard-vite.vercel.app/  
**GitHub Pages:** https://ekatmoz88-alt.github.io/github-profile-dashboard-vite-public/  

## Назначение

Дашборд показывает выбранные кейсы технического письма и динамический список публичных репозиториев GitHub-аккаунта.

## Состав дашборда

- **6 избранных карточек** — отобранные кейсы технического письма.
- Динамический индекс публичных репозиториев загружается через GitHub API.
- АРМ «Дешифратор» представлен как один проект; проектное описание и исходниковый анализ опубликованы в двух взаимодополняющих репозиториях.

## Избранные направления

- [ППО «Территория» — отдельный документационный трек](https://github.com/ekatmoz88-alt/territory-descriptor-unified-public) — не следует отождествлять его с АРМ «Дешифратор». В историческом проектном описании «Дешифратора» ППО «Территория» упоминается как внешний информационный контекст ПОШ ВБД.
- [АРМ «Дешифратор» — опубликованная документация](https://ekatmoz88-alt.github.io/deshifrator-docs-public/) · [исходниковый анализ](https://github.com/ekatmoz88-alt/deshifrator-docs-public) · [проектное описание](https://github.com/ekatmoz88-alt/descriptor-arm-spec) — один исторический программный проект. «Дискриптор» — ранее использовавшееся название того же проекта, а не отдельное ПО. Первый репозиторий содержит анализ выбранных C#-фрагментов, второй — проектное описание ПОСС, ПОМС и ПОШ ВБД. Требования и подтверждённая реализация разделяются.
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
