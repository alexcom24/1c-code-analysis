# 1c-code-analysis

Cursor skill: разбор XML-выгрузки 1С на скорость и оптимальность. Результат — один офлайн-HTML: **карточки проблем с цитатами ИТС** и **самодостаточные вставки** (процедура/область целиком, запрос уже внутри).

## Установка

```
Поставь skill 1c-code-analysis
https://github.com/<АККАУНТ>/1c-code-analysis
```

Агент копирует репозиторий в `%USERPROFILE%\.cursor\skills\1c-code-analysis`.

Нужны файлы `SKILL.md`, `protocol.md` и `html-report.md` в корне.

## Рядом

MCP: [BSL Language Server](https://github.com/1c-syntax/bsl-language-server) (`analyze_file`) и [v8std](https://ai.v8std.ru/mcp).

Skills (из [Desko77/cursor-1c-skills](https://github.com/Desko77/cursor-1c-skills), только эти папки):

- `skills/composing-1c-queries`
- `skills/1c-query-optimization`
- `skills/1c-bsp-api`

## Лицензия

MIT
