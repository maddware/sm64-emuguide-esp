---
description: "Guia exhaustiva de la configuracion del emulador para speedruns de Super Mario 64" 
---

# Configuración basica
Al abrir el emulador por primera vez, se te dara la bienvenida con una ventana con un menu desplegable de seleccion de lenguaje. Se sugiere mantenerlo en **Ingles**, debido a que te sera mas facil seguir la guía.

![](img/pj64_welcome.png)

Luego de eso, la aplicacion principal aparecera, la cual contiene el navegador de ROM y una barra de menú. Si tienes una carpeta con tus juegos de N64, puedes seleccionarla yendo a **File -> Choose Rom Directory**. Despues debes hacer clic en **Options -> Settings**, luego haz clic en la pestaña **Options** y desmarca la casilla **Hide Advanced Settings**. No es estrictamente necesario, pero se sugiere desmarcar **Pause emulation when window is not active** y marcar **Remember selected cheats**, si planeas usar codigos para practicar u otras razones varias.

![](img/pj64_options.png)

Luego, presiona OK y selecciona la ventana de **Settings** nuevamente. Nuevas pestañas deberian aparecer ahora. Primero, anda a la pestaña de **Advanced**. Las configuraciones aqui van a aplicar a todos las ROMs. Cambia **Default Memory Size** a **8 MB** como se muestra. Muchas romhacks, incluyendo Usamune (ROM de practica) y algunos codigos de practica de Gameshark requieren memoria adicional para funcionar correctamente.


![](img/pj64_advanced.png)

#### Arreglando "Bad ROM?" 

Si planeas usar el navegador ROM integrado de Project 64, se sugiere encarecidamente cambiar algunas de las opciones para hacerlo más usable. Haz clic en la pestaña de **Rom Selection**. Aqui tu cambiaras las columnas visibles entre otras cosas. Por defecto, Project64 solo muestra un "Good Name" de un rom, el cual es sacado de la base de datos del emulador. Esto resulta en muchos romhacks y similares resultando en **Bad ROM**, los cuales no son muy utiles, especialmente si tienes muchos ROMs de este estilo. Para arreglar esto, añade otro campo, como **File Name**.

![](img/pj64_browser.gif)

#### ROM settings
Los contenidos de esta pestaña van a estar totalmente en gris si accedes sin abrir un ROM. Para editar los contenidos, abre un rom y accede a **Settings** nuevamente, o **haz clic derecho a un ROM** en el navegador y haz clic en **Edit Game Settings** en el menu contextual, como se ve abajo.

![](img/pj64_gamesettings.png)

Asegurate que **Memory Size** este en **8 MB** (esto no deberia ser necesario si has seguido los pasos previos) y **Counter Factor** este en **1**, lo cual removera el lag presente en el juego, el cual es mas visible cerca del submarino en DDD.
Ten en consideracion que las versiones estandar del ROM de practica de Usamune (Japones o USA) tambien requeriran **CPU core style** en **Interpreter**. Lamentablemente esta opcion es mucho mas exigente en CPU, por lo que si tu computador es un poco lento, se sugiere mantenerlo en **Recompiler** y usar la **version VC de Usamune**.

!!!
Dado que las configuraciones son aplicadas a cada ROM por separado, necesitaras cambiar las configuraciones de cada ROM que quieras correr.
!!!

![](img/pj64_romconfig.png)
