# Инструкции по загрузке на GitHub

## После создания репозитория на GitHub выполните эти команды:

```bash
# Добавить удаленный репозиторий (замените YOUR_USERNAME на ваш GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/first-snow-festival.git

# Переименовать ветку в main (современный стандарт)
git branch -M main

# Отправить код на GitHub
git push -u origin main
```

## Альтернативно, если GitHub уже показывает другие команды:

Скопируйте и выполните команды, которые покажет GitHub после создания репозитория. Обычно они выглядят так:

```bash
git remote add origin https://github.com/YOUR_USERNAME/first-snow-festival.git
git branch -M main
git push -u origin main
```

## После успешной загрузки:

1. **Проверьте репозиторий** на github.com/YOUR_USERNAME/first-snow-festival
2. **Включите GitHub Pages** в Settings → Pages:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
3. **Сайт будет доступен** по адресу: https://YOUR_USERNAME.github.io/first-snow-festival/
