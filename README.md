# LabGit-Settings

Учебный проект для настройки репозитория Git и GitHub.

## Назначение
Изучение работы с фильтрами .gitignore, атрибутами .gitattributes и структурой каталогов.

## Структура каталогов
* src/ — исходный код (C#)
* docs/ — документация
* tests/ — тестовые материалы
* assets/ — вспомогательные материалы

## Исключаемые файлы (.gitignore)
* Сборка: build/, bin/, obj/
* Временные: temp/, *.tmp, *.temp
* Логи: logs/, *.log
* Настройки: .env, appsettings.Local.json
* Системные: Thumbs.db, .DS_Store
* Среда разработки: .vs/, .vscode/, *.user, *.suo
* Тесты: TestResults/

## Настройки (.gitattributes)
* * text=auto — автоопределение текстовых файлов
* *.cs text eol=crlf — окончания строк Windows для C#
* *.md, *.txt text eol=lf — окончания строк Unix для документов
* *.png, *.jpg, *.pdf, *.zip binary — бинарные файлы


