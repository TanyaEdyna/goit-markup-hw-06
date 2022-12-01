# goit-markup-hw-06

<!-- Відкриття/закриття модального вікна -->

Модальне вікно з формою заявки відкривається по натисканню на кнопку "Замовити послугу". Для того щоб скрипт спрацював, необхідно додати до розмітки спеціальні атрибути, за якими скрипт шукає елементи:

data-modal-open - на кнопку відкриття модального вікна.
data-modal-close - на кнопку закриття модального вікна.
data-modal - на бекдроп модального вікна.

<!-- -------- Код для settings.json --------- -->

{
"liveSassCompile.settings.formats": [
{
"format": "expanded",
"extensionName": ".css",
"savePath": "/css"
},
{
"format": "compressed",
"extensionName": ".min.css",
"savePath": "/css"
}
],
"liveSassCompile.settings.excludeList": ["/**/node_modules/**", "/.vscode/**"],
"liveSassCompile.settings.generateMap": true,
"liveSassCompile.settings.autoprefix": ["> 1%", "last 2 versions"]
}
