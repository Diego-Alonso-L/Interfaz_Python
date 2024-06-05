Este es un proyecto de creacion de una interfaz grafica la cual se conecta a una base de datos creada en PgAdmin.

en el archivo comprimido tenemos una carpeta la cual es el proyecto ( los archivos de python ) los cuales estan divididos para tener un mejor control
por supuesto cada uno de ellos cumplen una funcion diferente.

el segundo archivo que esta dentro del comprimido es un archivo .sql, esta es la base de datos ya creada que se utiliza en este proyecto para ello debemos de instalar postgres y utilizar de postgres PgAdmin

el archivo documentacion2.0.pdf explica paso a paso como hacer la base de datos en la interfaz de PgAdmin y la prueba que se le realizo a la interfaz grafica 
de igual manera si no se quiere crear la base de datos manualmente importa el archivo BIBLIOTECA.sql y tendra la base de datos que se uso en este caso

para correr el programa es necesario un entorno de compilacion por ejemplo visual stdio code que se utilizo en este ocacion, para que pueda correr se ocupan instalar unas librerias mediante un pip install

pip install psycopg2

pip install reportlab

pip install letter

abriremos el entorno de compilacion y la carpeta del proyecto, para poder entrar en la interfaz nos dirigiremos al archivo llamado login y correremos el programa, nos abrira la interfaz de inicio de sesion como se muestra en el documento .pdf despues de esto podremos ingresar de 2 maneras como ADMIN o como EMPLEADO ( esto se explica en el archivo documentacion2.0.pdf )

para entrar como administrador

User: ADMIN

Password: ADMIN

para entrar como empleado

User: EMPLEADO

Password: EMPLEADO

ESPERO QUE LES RESULTE DE MUCHA AYUDA, GRACIAS
