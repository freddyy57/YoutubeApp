# YoutubeApp

Esta App carga una determinada cuenta de youtube y muestra una lista con los videos de esa cuenta. Al pulsar el video se abririrá en una ventana nueva.

Para que funcione esta app navegue a esta dirección y obtenga una API key de youtube(https://developers.google.com/youtube/v3/docs/)

Una vez obtenga su apikey copie y pegue en: src/app/services/youtube.service.ts linea 9:

```

private apikey:string = "Aqui su API KEY";

```

En la linea 10 puede cambiar el playlist para que se muestre la cuenta de youtube que desee.

Navegue en su consola a la carpeta de este proyecto e instale las dependencias

```
npm install

```

Cuando termine de instalar las dependencias escriba el comando

```
ng serve

```

Abra en su navegador web la dirección: localhost:4200



This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.5.
