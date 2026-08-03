# Поддержка / Support

## Русский

### Перед отправкой отчёта

1. Убедитесь, что установлена последняя версия Simpltask.
2. Перезапустите приложение.
3. Проверьте проблему после перезагрузки Windows.
4. Определите, связана ли она с конкретным файлом, папкой, монитором или масштабированием.
5. Посмотрите существующие обращения в [GitHub Issues](https://github.com/AdamAnomatik/Simpltask-Releases/issues).

### Как сообщить об ошибке

Укажите:

- версию Simpltask;
- версию Windows;
- масштаб Windows;
- количество и расположение мониторов;
- точные шаги воспроизведения;
- ожидаемый и фактический результат;
- повторяется ли проблема после перезапуска;
- безопасный скриншот или короткое видео.

Пример:

```text
Версия Simpltask: 0.5.2
Windows: Windows 11 24H2
Масштаб: 125%
Мониторы: 2

Шаги:
1. Открыть Manager.
2. Выбрать лимит 12.
3. Переместить окно на второй монитор.
4. Закрыть и снова открыть Manager.

Ожидалось:
Окно полностью находится в рабочей области.

Фактически:
Часть окна выходит за пределы экрана.
```

### Журнал событий Windows

При аварийном завершении:

1. Нажмите `Win + R`.
2. Введите `eventvwr.msc`.
3. Откройте **Журналы Windows → Приложение**.
4. Найдите ошибку Simpltask.
5. Скопируйте текст ошибки.

Удалите из отчёта имя пользователя, приватные пути и другие чувствительные данные.

### Запрос функции

Опишите проблему, текущий способ её решения, ожидаемый результат и частоту использования функции.

Не публикуйте пароли, токены, приватные документы, корпоративные сведения или подробности уязвимостей. Для уязвимостей используйте [SECURITY.md](SECURITY.md).

---

## English

### Before reporting a problem

1. Confirm that the latest Simpltask version is installed.
2. Restart the application.
3. Check the issue after restarting Windows.
4. Determine whether it is related to a specific file, folder, monitor, or scaling value.
5. Review existing reports in [GitHub Issues](https://github.com/AdamAnomatik/Simpltask-Releases/issues).

### How to report a bug

Include:

- Simpltask version;
- Windows version;
- Windows scaling;
- number and arrangement of monitors;
- exact reproduction steps;
- expected and actual results;
- whether the issue remains after restarting;
- a safe screenshot or short recording.

### Windows Event Viewer

After a crash:

1. Press `Win + R`.
2. Enter `eventvwr.msc`.
3. Open **Windows Logs → Application**.
4. Find the Simpltask error.
5. Copy the error details.

Remove usernames, private paths, and other sensitive information before publishing.

### Feature requests

Describe the problem, your current workaround, the expected result, and how often you need the feature.

Do not publish passwords, tokens, private documents, confidential business information, or vulnerability details. Follow [SECURITY.md](SECURITY.md) for vulnerabilities.
