# Proyecto de Lista de Tareas

Este proyecto es una aplicación de lista de tareas construida con React, TypeScript, Redux y XState. También se implementa la autenticación de usuario a través de Passport.js, permitiendo el inicio de sesión con correo electrónico y contraseña, así como con Google y Facebook.

## Características

- Gestión de usuarios: registro, inicio de sesión, actualización de perfil y recuperación de contraseña.
- Gestión de tareas: añadir, completar, borrar y mover tareas entre colecciones.
- Gestión de colecciones de tareas: añadir, renombrar, borrar y ordenar colecciones.

## Inicio rápido

Para empezar a trabajar con el proyecto, sigue estos pasos:

1. Clona el repositorio:

   ```bash
   git clone https://github.com/<tu-usuario>/proyecto-lista-de-tareas.git
   ```

2. Instala las dependencias:

   ```bash
   cd proyecto-lista-de-tareas
   npm install
   ```

3. Inicia el servidor de desarrollo:

   ```bash
   npm start
   ```

Visita `http://localhost:3000` en tu navegador para ver la aplicación.

## Pruebas

Para ejecutar las pruebas, utiliza el siguiente comando:

```bash
npm test
```

## Construir el proyecto

Para construir el proyecto para producción, utiliza el siguiente comando:

```bash
npm run build
```

Los archivos de construcción se guardarán en el directorio `build`.

## Despliegue

Este proyecto puede desplegarse en cualquier servidor que pueda servir archivos estáticos. Asegúrate de servir el archivo `index.html` para cualquier ruta que no sea encontrada para soportar el enrutamiento del lado del cliente.

## Contribuir

Este proyecto está abierto a contribuciones. Por favor, abre un issue o crea un pull request si deseas contribuir.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT.
