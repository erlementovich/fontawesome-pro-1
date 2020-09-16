# Fontawesome-pro
1. Добавляем в `dependencies` файла package.json
  ```json
"dependencies": {
     "@fortawesome/fontawesome-free": "^5.14.0",
     "@fortawesome/fontawesome-pro": "git+ssh://git@github.com:erlementovich/fontawesome-pro.git#master"
   }
```
2. В `main.scss` своего проекта добавляем: 
```css 
@import "~@fortawesome/fontawesome-pro/css/all.css";
@import "~@fortawesome/fontawesome-pro/css/brands.css";
```
3. Далее используем официальный сайт [fontawesome.com](https://fontawesome.com)
