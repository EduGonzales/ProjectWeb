# ProjectWeb

#Instalación de mi proyecto.

#Primero debemos instalar anaconda(https://www.anaconda.com/) en Linux.
#Ejecutamos el sh y después creamos un entorno virtual: conda install -n nombre_del_entorno -c anaconda python.
#Nota: Si quisiera una versión de python en específico : python=3.9.
#Para acceder al entorno creado: conda activate nombre_del_entorno.
#Para salir del entorno: conda deactivate nombre_del_entorno.
#Ahora, una vez en el entorno, instalaremos:
#instalar pip en anaconda: https://anaconda.org/anaconda/pip: conda install -c anaconda pip.
#instalar django :pip install Django==4.0.4
#instalar DB Browser for SQLITE: para poder ver bien las bases de datos : https://sqlitebrowser.org/dl/
#la carpeta /bin : copiarla en el Home/bin o sino ahi.
#la carpeta dbblast ponerla en el mismo directorio home, pero no dentro de bin
#instalar visual studio code : descargaremos visual studio code(https://code.visualstudio.com/).
#dentro de visual studio code : agregar la carpeta ProjectWeb : y en la terminal de visual studio : 
#1. python manage.py makemigrations
#2. python manage.py migrate
#3. python manage.py runserver

#NOTA: EN EL CASO DE QUE AL HACER EL BLAST NO FUNCIONE:
#HABRA QUE CREAR EL BLAST LOCAL DESDE 0, PERO ES MUY SENCILLO
#SIGUE ESTOS COMANDOS: CREAS UNA NUEVA CARPETA EN HOME : EJEMPLODB 
#2. CREAS UN ARCHIVO INPUTS.FASTA O COPIAS LA QUE TE VENIA EN EL PROYECTO : DBBLAST
#3. EJECUTAS EL SIGUIENTE COMANDO :
