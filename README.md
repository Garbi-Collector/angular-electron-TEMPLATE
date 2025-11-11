esta es una explicacion de como usar este repositorio para tus propios proyectos de angular que ademas incluyen electron, para que de manera mas rapida puedas ahorrarte el proceso (corto) pero tedioso de hacerlo en cada proyecto que quieres usar estas tecnologias.

---
1) lo primero es que tienes que bajar este repositorio o usarlo como template en tu cuenta de git.
2) una vez lo tengas en local deberas ir a (poner la direccion) [package.json](/package.json) y mirar dentro de las primeras variables, veras algo como esto, modificalo a tu gusto

´´´ json
"name": "ejemplo",
"main": "main.js",
"version": "1.0",
"author": "garbi.dev",
"description": "ejemplo de descripcion",
´´´

3) luego deberas fijarte en el apartado de "scripts" que encontraras una variable como esta
´´´ json
   "serve:ssr:angular-electron-template": "node dist/angular-electron-template/server/server.mjs",
´´´

aca deberas hacer una modificacion de esta variable para que coincida con el nombre de tu proyecto. por ejemplo si tu proyecto se llama "pepito" deberas modificar donde dice "angular-electron-template" y remplazarlo con "pepito", de esta manera:

´´´ json
"serve:ssr:pepito": "node dist/pepito/server/server.mjs",
´´´
