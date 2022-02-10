# WebFont Open Sans

Пакет для установки веб-шрифта: Open Sans.

## Установка

Чтобы установить пакет, Вы можете воспользоваться командой в CLI:

```bash 
npm install --save https://github.com/getscope/npm-webfont-open-sans
```

или в файле `package.json` создать свойство `dependencies` и добавить ссылку на github-репозиторий:

```json 
{
    "dependencies": {
        "@getscope/npm-webfont-open-sans": "github:getscope/npm-webfont-open-sans"
    }
}
```

и выполнить команду в CLI для обновления установленных зависимостей:

```bash 
npm update
```

## Примеры использования и подключения

```css 
body {
    font-family: 'Open Sans', sans-serif;
}
```

Для импорта веб-шрифта в SCSS, Вы можете воспользоваться следующими путями:

```scss 
@import "node_modules/@getscope/npm-webfont-open-sans/src/scss/_300-normal.scss";
@import "node_modules/@getscope/npm-webfont-open-sans/src/scss/_400-normal.scss";
@import "node_modules/@getscope/npm-webfont-open-sans/src/scss/_600-normal.scss";
@import "node_modules/@getscope/npm-webfont-open-sans/src/scss/_700-normal.scss";
@import "node_modules/@getscope/npm-webfont-open-sans/src/scss/_800-normal.scss";
@import "node_modules/@getscope/npm-webfont-open-sans/src/scss/_all-normal.scss";
```
