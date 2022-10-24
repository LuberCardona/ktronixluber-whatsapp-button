# whatsapp-button

Whatsapp-button es una aplicacion personalizada que permitirá al cliente contactar personal de la tienda a través de un boton de whatsapp.

![whatsappButton](https://user-images.githubusercontent.com/66228518/197572265-263101d0-458b-4ea4-93a8-3f68405cf141.JPG)
![screencapture-api-whatsapp-send-2022-10-24-10_36_34](https://user-images.githubusercontent.com/66228518/197572410-a3ed93a0-b188-4cfa-b669-31a13ad455b8.png)

## Configuración

### Paso 1 - Configuración Básica
Ingresar al siguiente repositorio en GitHub [react-app-template](https://github.com/vtex-apps/react-app-template) y crear un nuevo repositorio usando este template

### Paso 2 - Clonación del repositorio
Abrir la terminal e ingresar el comando git clone mas la URL del repositorio en gitHub asi: git clone [url](), posteriormente acceda a la carpeta del proyecto en su repositorio local.

### Paso 3 - Editar el Manifest.json
Modificar en el archivo manifest.json el valor del vendor con el nombre correspondiente a su vendor y el valor del name con el nombre con el que va a usar su componente. Opcionalmente puede modificar la versión y el título.

Ejemplo:  
{  
"vendor": "itgloberspartnercl",  
"name": "whatsapp-button",  
"version": "0.0.1",  
"title": "WhatsApp Button Component"  
}

Adicionalmente debe asegurarse de tener en los builders el store en su version 0.x asi:

"builders":{   
"store": "0.x"   
} 

### Paso 4 - Editar el Package.json
Modificar en los archivos package.json ubicado de manera global asi como el que esta ubicado en la carpeta de react, el nombre y la versión de igual forma como fueron modificados en el archivo manifest.json

Ejemplo:  
{  
"name": "whatsapp-button",  
"version": "0.0.1",  
}

### Paso 5 - Instalar apps necesarias
En la terminal ubicarse en la carpeta react con el comando cd react y luego de estar alli digitar en la terminal la palabra yarn, con esto se hara la instalacion de los modulos de node necesarios para su aplicacion. Cierre su editor y abra nuevamente su proyecto y verifique que  dentro de la carpeta de react haya quedado instalada la carpeta de node modules.

### Paso 6 - Ejecute un preview de la tienda
En su terminal digite el comando vtex link, si su aplicacion es lanzada sin ningun error, en su ternimal aparecera la siguiente informacion:   
(info: App linked successfully). 

Para usar la aplicación en su tienda debe adicionar en el archivo manifest.json la dependencia correspondiente al componente.

Ejemplo:  
"dependencies": {  
"itgloberspartnercl.whatsapp-button": "0.x"  
}

## Dependencies  
Ninguna

## Store Component Apps  
Ninguna

## Custom Apps  
Ninguna

## Contributors
1. Luber María Cardona Vargas

