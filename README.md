# Autenticación de autorización - Teslo REST Server

Se ve la forma en que se da autorización por autenticación dentro de nuestro REST Server, los temas que se acabarcan son: 

- Autenticación. 
- Autorización por `Bearer Tokens`.
- Uso de `Json Web Tokens`.
- Realización de `Hash` de contraseñas.
- Uso de `Nest Passport`.
- Módulos asíncronos.
- Protección de rutas.
- Uso de `Custom Method Decorators`.
- Uso de `Custom Class Decorators`.
- Uso de `Custom Property Decorators`.
- Enlazar usuarios con productos.

## Teslo API
1. Instalar las dependencias de `node_modules` con el comando:
```
npm install
```
2. Renombrar el archivo `.env.template` a `.env`.
3. Definir las variables de entorno.
4. Levantar la base de datos con `Docker`:
```
docker-compose up -d
``` 
5. Ejecutar el SEED para reestablecer la Base de datos de tipo `GET`: 
```
http://localhost:300'/api/seed
```
6. Levantar el proyecto en entorno de desarrollo: 
```
npm run start:dev
``` 