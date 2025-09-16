# Product Microservice


## Dev

1. Clonar el Repositorio
2. Instalar las dependencias
3. Crear un archivo `.env` basado en el `env.template`
4. Ejecutar migracion de prisma `npx prisma migrate dev`
5. Levantar el Servidor de NATS
```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```
```
Arrancar el Servidor: docker start nats-server
```
6. Ejecutar `npm run start:dev`
