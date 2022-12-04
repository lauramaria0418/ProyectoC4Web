Aplicación de Servidor

## Dependencias:

Esta aplicación web (de lado del servidor), se encuentra desarrollada con las siguientes tecnologías:

- [express](https://www.npmjs.com/package/express), nos permite generar y ejecutar nuestro servidor
- [cookie-parser](https://www.npmjs.com/package/cookie-parser), para poder interactuar con las cookies en los encabezados de nuestras solicitudes y respuestas http
- [cors](https://www.npmjs.com/package/cors), para definir la lista de hosts o clientes web permitidos
- [helmet](https://www.npmjs.com/package/helmet), para generar encabezados con respecto a nuestras solicitudes y respuestas
- [morgan](https://www.npmjs.com/package/morgan), para mostrar en consola de forma automatizada los logs de nuestro servidor asi mismo como poder escribirlos en un archivo
- [mongoose](https://www.npmjs.com/package/mongoose), para conectarnos a un cluster [MongoDB](https://www.mongodb.com/)
- [mongoose-sequence](https://www.npmjs.com/package/mongoose-sequence), para generar de una forma sencilla un indice de con auto-incremento en MongoDB
- [argon2](https://www.npmjs.com/package/argon2), para poder hashear las contraseñas de nuestros usuarios
- [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken), para poder autenticar a nuestros usuarios, en este proyecto manejaremos la autenticación por medio de 2 tokens uno de refresco con larga duración (7 días), y uno de acceso con corta duración (15 minutos)
- [zod](https://www.npmjs.com/package/zod), para validar objetos json de una forma rápida y sencilla

Y también cuenta con otras tecnologías para facilitar la experiencia como desarrollador:

- [babel](https://www.npmjs.com/package/babel), el cual nos permite tener sintaxis de ECMAScript moderno, como por ejemplo usar `import export` en nuestros archivos sin la necesidad de incluir archivos innecesarios en las rutas o sus extensiones
- [eslint](https://www.npmjs.com/package/eslint), para validar estándares y reglas de formato en nuestro código
- [prettier](https://www.npmjs.com/package/prettier), para darle formato a nuestro código de forma automática
- [husky](https://www.npmjs.com/package/husky), para ejecutar comandos antes de hacer commit con nuestros cambios
- [lint-staged](https://www.npmjs.com/package/lint-staged), para ejecutar comandos tomando en cuenta solo los archivos en el área de stage
- [nodemon](https://www.npmjs.com/package/nodemon), el cual nos permite reiniciar nuestro servidor con cada cambio que realicemos en algún archivo

