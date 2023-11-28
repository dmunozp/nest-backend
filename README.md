# Backend en Nest


## Pasos:
1. Instalar nestjs ```npm i -g @nestjs/cli```
2. Crear nuevo proyecto ```nest new project-name```
3. Levantar backend ```npm run start:dev```
4. Levantar la base de datos: lee y monta la imagen de MongoDB ```docker compose up -d```
5. Conectar backend con MongoDB con ayuda de Mongoose ```npm i @nestjs/mongoose mongoose``` 
6. Variables de entorno ```npm i @nestjs/config```
7. Instalar validadores dto ```npm install class-validator class-transformer```
8. Encriptar contraseña ```npm i bcryptjs```
    Instalar los tipos definición de datos ```npm i --save-dev @types/bcryptjs```
9. Trabajar con JWT ```npm install --save @nestjs/jwt```
10. Crear Guard ```nest g gu auth/guards```


## Variables de entorno
Copiar el .env.template y renombrarlo a .env
