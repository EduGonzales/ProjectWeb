# ProjectWeb

#Instalación de mi proyecto.

1. Primero debemos instalar anaconda(https://www.anaconda.com/) en Linux.
2. Ejecutamos el sh y después creamos un entorno virtual: conda install -n nombre_del_entorno -c anaconda python.
3. Nota: Si quisiera una versión de python en específico : python=3.9.
4. Para acceder al entorno creado: conda activate nombre_del_entorno.
5. Para salir del entorno: conda deactivate nombre_del_entorno.
6. Ahora, una vez en el entorno, instalaremos:
7. instalar pip en anaconda: https://anaconda.org/anaconda/pip: conda install -c anaconda pip.
8. instalar django :pip install Django==4.0.4
9. instalar DB Browser for SQLITE: para poder ver bien las bases de datos : https://sqlitebrowser.org/dl/
10. la carpeta /bin : copiarla en el Home/bin o sino ahi.
11. la carpeta dbblast ponerla en el mismo directorio home, pero no dentro de bin
12. instalar visual studio code : descargaremos visual studio code(https://code.visualstudio.com/).
13. dentro de visual studio code : agregar la carpeta ProjectWeb : y en la terminal de visual studio : 
14. python manage.py makemigrations
15. python manage.py migrate
15. python manage.py runserver

#NOTA: EN EL CASO DE QUE AL HACER EL BLAST NO FUNCIONE:
#HABRA QUE CREAR EL BLAST LOCAL DESDE 0, PERO ES MUY SENCILLO
#SIGUE ESTOS COMANDOS: CREAS UNA NUEVA CARPETA EN HOME : EJEMPLODB 
#2. CREAS UN ARCHIVO INPUTS.FASTA O COPIAS LA QUE TE VENIA EN EL PROYECTO : DBBLAST
#3. EJECUTAS EL SIGUIENTE COMANDO :
