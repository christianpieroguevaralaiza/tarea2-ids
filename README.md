# tarea2-ids
Galeria de carros conectada a una base de datos en Mongodb

1. Descarga e instala el lenguaje de programacion go para tu sistema operativo: https://go.dev/doc/install

2. De no tener instalado vscode, descargalo del siguiente link: https://code.visualstudio.com/download
3. Instala la extension de go para vscode(si te sale alguna notificacion de vscode dale click a install all)

Crea la base de datos: 
...
Añade documentos
...	

4. Abre tu base de datos en atlas, Cluster 0 es el nombre predeterminado, y dale al boton Conectar, selecciona Drivers y 
- Selecciona driver para go
-Descarga el controlador de go para mongdb escribiendo 
go get go.mongodb.org/mongo-driver/mongo
en el terminal de tu carpeta de trabajo en vs code
- Reemplaza tu "cadena de conexion" en la linea 12 del archivo main.go, donde dice reemplaza


5. Abre el terminal y escribe 
	go run main.go

Debería aparecerte un mensaje de conexión satisfactoria, y así conectas un programa en go a tu base de datos en mongodb
