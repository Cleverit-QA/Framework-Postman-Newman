# Tabla de contenidos
1- Descripcion general
2- Tecnologias
3-Installacion
4-Recomendaciones
5-Anexos

## Descripcion general
Este proyecto esta hecho con postman+newman+gitAction, se crea una colletion de una api, la cual tenga a su vez un arhicvo json que es donde estaran los testcase perteneciente al api, Postman correrla los casos de prueba automatizado, considerando los testcase del archivo json, luego mediante el action correrar de manera automatica y creara un archivo tipo reporte.xml que nos servira de evidencias en las pruebas.

## Tecnologias(Requerimientos)
1-Postman
2-newman
3-GitActions
4-nodejs

## Installacions(Comandos)
1.Installar postman
2.install nodejs
3.Ejecutar los siguientes comando para instalar newman:
  $npm install newman
  $npm install -g newman-reporter-slackreporter
  $npm install -g newman-reporter-htmlextra

## Recomendacion(Comandos)
-En caso de que quiera correr newman de manera local para generar un reporte en su pc, ejecute el siguiente comando en cmd asegurandose que la colletion y el json esten en la misma carpeta: newman run Micollection.json -d Mitest_case.json -r htmlextra

## Anexos: 
![image](https://user-images.githubusercontent.com/122124442/218802190-4456eb4f-d969-4c7a-8f69-2f4e80b594de.png)
![image](https://user-images.githubusercontent.com/122124442/218802607-e6ef6980-d2cd-4719-82bf-0c547c8e5551.png)
