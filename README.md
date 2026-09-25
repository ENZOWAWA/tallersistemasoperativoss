# tallersistemasoperativoss
 Clase 1: 20 de Agosto de 2026

Tema: Navegación en el Sistema de Archivos y Control de Versiones

Estructura de Directorios en Linux: / (Raíz), /etc (Configuración), /home (Usuarios), /root (Superusuario), /var, /sys, /bin, /usr, /share (Sistema).

Rutas:

Absoluta: Inicia desde la raíz / (ej. cd /etc/apt/services).

Relativa: Inicia desde el directorio actual (ej. cd ../user1).

Comandos: cd (cambiar dir; cd ~, cd $HOME para ir a inicio), find (buscar archivos), printenv (variables de entorno), history (historial).

Clase 2: 27 de Agosto de 2026

Tema: Banderas de ls, Operadores Lógicos y Redirección

Banderas ls: -a (ocultos), -lh (tamaño legible: KB, MB), -r (orden inverso).

Operadores:

Relacionales: >=, ==, >, <=, <, !=

Lógicos: AND (&&), OR (||), NOT (!) (Ej: 5 > 3 AND 2 == 2 → Verdadero / 2 > 1 OR 1 > 2 → Verdadero).

Clase 3: 29 de Agosto de 2026

Tema: Introducción a la Interfaz de Usuario y Comandos Básicos

Conceptos Clave: GUI (Interfaz Gráfica), Comando e Instrucción, Sintaxis (Estructura).

Comandos Básicos: help (muestra comandos), touch (crea archivos vacíos, ej. touch uno.txt), ls (visualiza directorio).

Nota: Linux es case-sensitive (distingue mayúsculas y minúsculas).

 Clase 4: 15 de Septiembre de 2026

Tema: Permisos de Archivos en Linux

Estructura Octal: 4 (Lectura/r), 2 (Escritura/w), 1 (Ejecución/x) en niveles Usuario / Grupo / Otros.

Ejemplos chmod:

chmod 400 file.txt (Solo propietario lee)

chmod 444 file.txt (Todos leen)

chmod 700 file.txt (Acceso total solo propietario)

chmod +x file.txt (Agrega ejecución)

chmod -wx file.txt (Quita escritura y ejecución)

Propietario: chown (cambia propietario/grupo).

Clase 5: 17 de Septiembre de 2026

Tema: Caracteres Comodín (Wildcards) y Tuberías (|)

Comodines: * (cero o infinitos caracteres, ej. *.txt, s*) y ? (exactamente un carácter).

Comandos y Redirección: grep (filtra/busca texto), | Pipe (redirige salida a entrada, ej. ls -1 | grep *.txt), > (redirige salida a archivo, ej. echo "Hola" > file.txt), date (fecha), mkdir /tmp/taller (directorio temporal).

Práctica de Laboratorio (Secuencia de Comandos)

cd / — Ir a la raíz.

cd $HOME — Ir al directorio personal.

ls — Listar archivos.

touch test.txt — Crear archivo.

cp test.txt test2.txt — Copiar archivo.

mv test2.txt test3.txt — Renombrar/mover archivo.

rm test2.txt — Eliminar archivo.

mkdir prueba — Crear carpeta.

mv test3.txt prueba/ — Mover archivo a carpeta.

cp -r /home/prueba /home/prueba2/ — Copiar carpeta recursivamente.

rm -rf prueba — Eliminar carpeta de forma forzada.

vi test3.txt / vi test4.txt — Editar archivos con Vi.

cat test3.txt test4.txt > test5.txt — Concatenar archivos.

clear — Limpiar pantalla.

whoami — Mostrar usuario actual.

history — Ver historial de comandos.
