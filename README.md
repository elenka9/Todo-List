# [Todo List](https://elenka9.github.io/Todo-List/)
*☝️ клик, чтобы посмотреть. можно добавить свои заметки*
## Frontend Project
**Skills:** Java Script, React, Redux, Vite

**About project:** Приложение, где можно добавлять, редактировать и удалять заметки. При перезагрузке список сохраняется. 

![image](https://github.com/user-attachments/assets/1fde11f8-ef89-4941-b49a-6c5d691aceee)


***
Для опубликования проекта на GitHub Pages потребовалось внести изменения в файлы: 
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
