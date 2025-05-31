# Intelligent Tasks Manager (VS Code Extension)

Этот плагин для Visual Studio Code помогает вам управлять комментариями типа TODO, FIXME, BUG, NOTE, визуализируя их в удобной панели.

## 📦 Установка

1. Склонируйте репозиторий:
```
git clone <repo-url>
```

2. Установите зависимости:
```
npm install
```

3. Сборка плагина:
```
npm run compile
```

4. Упакуйте в `.vsix` файл:
```
npx vsce package
```

5. Установите плагин в VS Code:
```
code --install-extension <путь к vsix>
```

## 🚀 Использование

- Откройте панель **Intelligent Tasks** в дереве проводника.
- Сканируйте рабочее пространство с помощью команды `Сканировать рабочее пространство`.
- Отмечайте задачи как выполненные.

## 🔧 Настройки

В `settings.json` вы можете указать теги для отслеживания:
```json
"intelligentTasks.todoPatterns": ["TODO", "FIXME", "BUG", "NOTE"]
```
