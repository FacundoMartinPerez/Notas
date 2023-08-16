# NotasApp

## Se necesita:
- Base de Datos (MongoDB)
- Google Console Account para crear la clave de autenticación 

## Crear archivo .env 
Crea un archivo .env para guardar las credenciales. Abajo dejo un ejemplo:

```
MONGODB_URI = mongodb+srv://<username>:<password>@mongodburlhere
GOOGLE_CLIENT_ID= TU_GOOGLE_ID_ACÁ
GOOGLE_CLIENT_SECRET= TU_GOOGLE_CLIENT_SECRET_ACÁ
GOOGLE_CALLBACK_URL=http://localhost:5000/google/callback
Aún así yo dejo mis credenciales para que sea más fácil, las credenciales ya están en el archivo .env
```

## Instalación
Para instalar y usar este proyecto es necesario instalar las dependencias usando npm y recién después de eso se corre el server:

```
$ npm install
$ npm start
```