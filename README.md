# Servicio REST Node

URL:

https://enigmatic-stream-28842.herokuapp.com/usuario

## Instalaciones

```
npm i express --save
npm i body-parser --save
```

## Despliegue en Heroku

En package.json:
```
"scripts": {
    "start": "node server/server.js"
}
```

Comandos:
```
heroku create
git remote
git remote -v
git push heroku master
heroku open
```

## Versiones

- v0.0.1
    * Se crean esqueletos de metodos GET, PUT, POST y DELETE
    
