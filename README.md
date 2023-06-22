# tarea2-ids
Galeria de carros conectada a una base de datos en Mongodb

1. Descarga e instala el lenguaje de programacion go para tu sistema operativo: https://go.dev/doc/install

2. De no tener instalado vscode, descargalo del siguiente link: https://code.visualstudio.com/download

3. Instala la extension de go para vscode(si te sale alguna notificacion de vscode dale click a install all)

Necesitaremos una base de datos a la cual conectarnos, para lo cual:
Crearse una cuenta en mongodb:
•	Puedes Registrarte con una cuenta de Google, GitHub o con un correo electronico y una contraseña
•	Registrate usando el siguiente link link
•	Deberas responder 3 preguntas
•	Si ya tienes una cuenta haz click donde dice "Log in now" e inicia sesion
•	Tambien puedes iniciar sesion mediante el siguiente link link

Crear un cluster de base de datos:
•	Despues de registrarte se mostraran 3 plantillas para desplegar tu base de datos, elige la que dice M0 Free
•	Haz click en el boton verde que dice "create"
•	Te preguntara como te gustaria autenticar la conexion, seleccionar la opcion que dice "Username and password"
•	Se te dara un usuario y contraseña autogenerada, darle click al boton "copy" para copiar la contraseña y guarda estos datos
•	Haz click en el boton verde que dice "Create User"
•	Te preguntara desde donde te gustaria conectarte, seleccionar la opcion que dice "My Local Environment"
•	Deslizate hacia abajo y haz click en el boton verde que dice "Finish and Close"
•	Se abrira un cuadro que confirma que se han establecido las reglas de acceso, haz click en el boton verde que dice "Go to Databases"
•	Ahora que ya se posee un cluster de Atlas, se puede crear una base datos



5. Abre el terminal e introduce el comando 
	go mod init main.go
Esto creará un archivo go.mod

6. Abre tu base de datos en atlas, Cluster 0 es el nombre predeterminado, y dale al boton Conectar, selecciona Drivers y 
- Selecciona driver para go
-Descarga el controlador de go para mongdb escribiendo 
go get go.mongodb.org/mongo-driver/mongo
en el terminal de tu carpeta de trabajo en vs code

7. Reemplaza tu "cadena de conexion" en la linea 12 del archivo main.go, donde dice <reemplaza>
PD: Asegurate de guardar los cambios en el archivo con ctrl+s

8. Finalmente introduce el comando
go run main.go 
para correr el programa

Deberá aparecerte un mensaje de conexión satisfactoria, y así conectas un programa en go a tu base de datos en mongodb
