Se trata de un proyecto de elaboración de una interfaz gráfica que conecta a una base de datos creada en PgAdmin.

En el archivo comprimido tenemos una carpeta la cual es el proyecto ( los archivos de Python ) los cuales están divididos para tener un mejor control
por supuesto cada uno de ellos cumplen una función diferente.

El segundo archivo que está dentro del comprimido es un archivo .sql, esta es la base de datos ya creada que se utiliza en este proyecto, para ello debemos de instalar postgres y utilizar de postgres PgAdmin

El archivo documentacion2.0.pdf explica paso a paso como hacer la base de datos en la interfaz de PgAdmin y la prueba que se le realizó a la interfaz gráfica 
de igual manera si no se quiere crear la base de datos manualmente importa el archivo BIBLIOTECA.sql y tendrá la base de datos que se usó en este caso

para correr el programa es necesario un entorno de compilación por ejemplo Visual Stdio Code que se utilizó en esta ocasión, para que pueda correr se ocupan instalar unas librerías mediante un pip install

pip install psycopg2

pip install reportlab

pip install letter

abriremos el entorno de compilación y la carpeta del proyecto, para poder entrar en la interfaz nos dirigiremos al archivo llamado login y correremos el programa, nos abrirá la interfaz de inicio de sesión como se muestra en el documento .pdf después de esto podremos ingresar de 2 maneras como ADMIN o como EMPLEADO ( esto se explica en el archivo documentacion2.0.pdf )

para entrar como administrador

User: ADMIN

Password: ADMIN

para entrar como empleado

User: EMPLEADO

Password: EMPLEADO

ESPERO QUE LES RESULTE DE MUCHA AYUDA, GRACIAS
