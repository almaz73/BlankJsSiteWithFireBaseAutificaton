# BlankJsSiteWithFireBaseAutificaton

[ДЕМО](https://almaz73.github.io/fireBase/helloWorld/login.html) 
======

> JS project . Стартовый шаблон для создания js сайтов c базой данных на FireBase

> Требуется настройка firebase (зарегистрироваться -> создать html проект -> оттуда забрать ключи и вложить в firebase.js -> создать базу банных -> настроить правила)

правила для database:
```
{
  "rules": {
   ".read": "auth != null",
   ".write":"auth != null",
   "guest":{
     ".read": true,
     ".write": true,
   }
  }
}
```

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```
---