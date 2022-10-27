<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1. Clonar el repositorio
2. Ejecutar

```
npm install
```
3. Tener Nest CLI instalado
```
npm i -g @nestjs/cli
```
4. Levantar la base de datos

```
docker-compose up -d
```


5. Clonar archivo __.env.template__ y renombrar la carpeta a __.env__
```
http://localhost:3000/api/v2/seed
```

6. Llenar las variables de entorno definidas en ```.env```
   

7. Ejecutar la aplicación en dev:

```npm run start:dev```


8. Poblar base de datos con el seed
```
http://localhost:3000/api/v2/seed
```

## Stack
 * mongoDB
 * NestJs
