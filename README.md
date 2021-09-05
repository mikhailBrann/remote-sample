# Twitter bootstrap
![Bootstrap logo](https://www.ruhidesain.com/wp-content/uploads/2018/04/getbootstrap-card.png)

**Twitter Bootstrap** - это CSS фреймворк, постороенный на слудующих технологиях:
* HTML
* CSS
* JavaScript
## start to work
Перед началом работ определитесь, ~~оно Вам надо?~~ каким способом подключения воспользоваться.

Есть *2 основных способа*:
1. через CDN
    1. Так же можно сохранить нужные файлы в проект и все) 
2. через NPM

### Install for CDN
создаем в проекте несколько тегов для подключения:
1. [CSS](https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css)
2. [JS](https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/js/bootstrap.min.js)

```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>News</title>

        <link rel="stylesheet" 
        href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" 
        crossorigin="anonymous">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/js/bootstrap.min.js" integrity="sha384-cn7l7gDp0eyniUwwAZgrzD06kc/tftFf19TOAs2zVinnD/C7E91j9yyk5//jjpt/" crossorigin="anonymous"></script>

    </head>
    <body>
        
    </body>
    </html>
```
### Instal for NPM
вводим несколько команд:
* npm install bootstrap --save
* npm install jquery --save
### use

```javascript
    var $ = require("expose-loader?$!jquery"); 
    require('bootstrap');
    require('jquery.easing');
```