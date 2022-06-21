# Pasapalabra_POO
Pasapalabra en Java con interfaz gráfica desarrollado para la asignatura Programación Orientada a Objetos del grado de Ingeniería de Computadores de la Universidad Rey Juan Carlos

Desarrollado por: Alejandro Panizo Jerez y Aitor García Camargo


****MANUAL DE USO****
![Captura de pantalla 2022-06-21 231245](https://user-images.githubusercontent.com/98469786/174898434-18fdc63a-bde4-4c3e-b0b7-0a1a9260ea30.png)

![Captura de pantalla 2022-06-21 232934](https://user-images.githubusercontent.com/98469786/174900537-9e361982-b3ee-432c-89dc-f6c893a3aeb6.png)

**LOGIN Y DATOS**

Para iniciar sesión o registrarse hay que utilizar el menú de Jugador Principal situado en la parte superior derecha. 
Pulsando en Actualizar se muestran las estadísticas del jugador que se encuentra logueado.
En Mostrar Clasificación se muestra un listado de todos los jugadores en el sistema, ordenador por partidas ganadas o por puntos
En Historial de Partidas podemos ver todas las partidas disputadas por el jugador logueado con los resultados suyos y de su contrincante.

**MODOS DE JUEGO**

-Entrenamiento: Se puede jugar con un único usuario logueado, es necesario cargar un fichero binario de palabras (Hemos adjuntado un fichero binario llamado Palabras1) y seleccionar el número de letras que queremos para el rosco, con un máximo de 26. Una vez finalizado el entrenamiento el botón reiniciar partida reinicia la interfaz y actualiza los puntos en caso de ser necesario.
-Modo VS: Tenemos que introducir las credenciales de un jugador ya registrado en el apartado de Segundo Jugador, además de añadir los correspondientes ficheros de palabras (se adjuntan los ficheros binarios Palabras1 y Palabras2). Una vez terminada la partida hay que pulsar reiniciar partida para reiniciar la interfaz y el reparto de puntos, ya estaría disponible el mostrar historial de partidas.


**FUNCIONES DE ADMINISTRADOR**

Modificar Jugador: Un administrador puede modificar, crear o eliminar a otros usuarios, para ello es necesario iniciar sesión como administrador (usuario: admin , contraseña: admin), e introducir en el menú de administrador los datos de algún usuario ya registrado o nuevos datos para crearlo, el botón mostrar estadísticas, muestra los datos del usuario seleccionado en el menú de estadísticas.

**FICHEROS BINARIOS**
Tenemos un sistema para poder crear ficheros binarios a partir de los datos que hay introducidos en el sistema en el momento de la acción de cargar y para poder extraerlos de ficheros binarios. Dentro del .rar del programa completo y en la carpeta del ejecutable de la aplicación hemos añadido los ficheros necesarios para cargar palabras en el rosco o cargar jugadores.

