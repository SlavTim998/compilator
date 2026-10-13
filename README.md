# Compilator 🐍

Онлайн-компилятор Python 3, работающий в браузере через Pyodide.

## Возможности
- Редактор Python и окно вывода
- Кнопка запуска и Ctrl+Enter
- Адаптивный интерфейс

## Запуск на Render
1. Откройте https://dashboard.render.com/select-repo?type=blueprint или в Render выберите **New → Blueprint**.
2. Подключите GitHub и выберите приватный репозиторий `SlavTim998/compilator`.
3. Подтвердите развёртывание по файлу `render.yaml`.

Для локального запуска: `python -m http.server 8000`.

Примечание: интерактивный `input()` не поддерживается; бесконечные циклы могут блокировать вкладку.