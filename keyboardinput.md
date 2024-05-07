---
title: "LINK's DirectInput"
description: "Guia exhaustiva de la configuracion del emulador para speedruns de Super Mario 64" 
---

# LINK's DirectInput7 1.6.1

![](./img/keyboardinput.png)

[!file Descarga](https://www.mediafire.com/file/vtr2wup8d9l664l/KeyboardInput.zip/file)

Este plugin es una modificacion de Jabo's DirectInput hecho para jugadores de **teclado**, el cual añade soporte para modificadores analogos (para que por ejemplo puedas caminar en vez de correr). Los modificadores son configurados a traves de el archivo de texto **KeyboardInputConfig.txt**, el cual especifica la **cantidad por la cual el valor analogico es dividido** junto a **virtual-key codes**, los cuales especifican que botones activan estos modificadores.

!!!
Una lista completa de las **virtual-key codes** pueden ser encontradas aca: [https://docs.microsoft.com/en-gb/windows/win32/inputdev/virtual-key-codes](https://docs.microsoft.com/en-gb/windows/win32/inputdev/virtual-key-codes)
!!!

Por ejemplo, la primera linea del archivo pretederminado es `2 4C`, el cual significa que el valor del analogo sera dividido por **2** cuando la tecla L sea presionada. El plugin leera **solo 5 lineas** de la configuracion, por lo que es probable que tengas que reemplazar configuraciones existentes dependiendo de tus necesidades.

Un video explicativo complementario en ingles puede ser encontrado aqui:

[!embed](https://www.youtube.com/embed/pwsz8ak65N0?start=142)

[!ref Regresar a la selección de plugins](plugin_setup.md#selección-de-plugins)
