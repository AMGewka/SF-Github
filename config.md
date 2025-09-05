# Первичная настройка Git

Укажем имя и email (будут отображаться в коммитах):

```bash
git config --global user.name "Ваше Имя"
git config --global user.email "you@example.com"
```

Полезные параметры:
```bash
git config --global core.editor "code --wait"
git config --global color.ui auto
```

Проверка настроек:
```bash
git config --list
```

---

👉 Далее: [Создание репозитория](init.md)
