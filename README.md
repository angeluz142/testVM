# testVM

Test1 - .NET

Proyecto de prueba realizado con Web API en C# con Framework 4.5.2

El desarrollo en .NET se encuentra en la carpeta "testVirtualMind".

Preparacion del entorno:

1- Es necesario que cuentes con la version de SQLSERVER >= 2012 y visual studio 2015 como mínimo.
2- Usar para pruebas del API puedes utilizaar Postman (https://www.getpostman.com/) o similares.
3- Ejecutar script "VMscript.sql" en sqlserver para crear la BD junto con su data.
4- Una vez ejecutado el script (ubicado en la carpeta BD Scripts) asegurate de hacer una consulta a la tabla Tbl_User.
5- Abre el proyecto de VS y coloca como proyecto de arranque "RestApp".
6- Ejecuta el proyecto.


Empieza a probar:

Url: http://localhost:12611/api/Cotizacion/Real  ----> Respuesta esperada: Http 401
Url: http://localhost:12611/api/Cotizacion/Peso  ----> Respuesta esperada: Http 401
Url: http://localhost:12611/api/Cotizacion/Dolar ----> Respuesta esperada: 17.250 (por ejemplo).

--Para listar los usuarios:

Url: http://localhost:12611/api/Usuario  ----> Respuesta esperada: data en json.



Test2 --  JavaScript

1- Descarga los archivos ubicados en el directorio de "testJS".
2- Abre en el navegador el index.html.
3- Apertura la consola del navegador (suele ser con f12) y ejecuta las instrucciones
   comentadas en el archivo "jstes.js".
   
 
