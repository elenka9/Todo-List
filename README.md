# [Todo List](https://elenka9.github.io/Todo-List/)
*☝️ клик, чтобы посмотреть. можно добавить свои todo-шки*
## Frontend Project
**Skills:** Java Script, React, Rudux, Vite

**About proejct:** Приложение, где можно добавлять и удалять заметки. При перезагрузке список сохраняется. 


***
Для опубликования проекта на GitHub Pages на потребовалось внести изменения в файлы: 
1. Установка зависимости в проект - npm i gh-pages 
2. В package.json добавлены 2 скрипта -
  ```
    "predeploy": "npm run build",
    "deploy": "gh-pages -d dist"
  ```

3. В vite.config.js добавлена строка:
```
base: '/Название репозитория'
```

4. После `git push origin` дополнительно делаем - `npm run deploy`
