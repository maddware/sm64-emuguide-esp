---
description: "Guia exhaustiva de la configuracion del emulador para speedruns de Super Mario 64" 
---

# Adquiriendo el emulador

La unica version de Project64 permitida para speedruns en leaderboards es la 1.6. **Todas las otras versiones (tales como 1.7 o 2.x) estan prohibidas.** Las leaderboards tambien permiten el uso de Mupen64Plus y OpenEmu, permitiendo opciones de emulacion nativa para usuarios de Linux y Mac respectivamente. Esta guia se enfoca en configurar Project64 1.6 especificamente.

## Descarga

Para acelerar el proceso de configura3cion, existe un paquete preconstruido disponible con el emulador y los mejores plugins. Extrae el archivo en cualquier carpeta que quieras, luego sigue las instrucciones de esta guia

Ultima actualización en 2022-10-16.

[!file Enlace 1 (Dropbox)](https://www.dropbox.com/s/cgkbhsarjthgnz8/Project64%201.6%20%28wermi%27s%20build%20v7%29.exe?dl=1)
[!ref target="blank" text="Enlace 2 (GDrive)"](https://drive.google.com/file/d/1GlvT7-TBjLz5ii0UsswDnqZZF4VVx3US)

!!!
Si tienes errores cargando cualquiera de los plugins, vas a necesitar instalar la version apropiada de Visual C++ runtimes. Por conveniencia, un paquete all-in-on puede ser encontrado aca: https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/
!!!

## Configuracion manual

!!!Advertencia

Esta guia esta escrita con asumiendo que usas la version provista en esta pagina para hacer el proceso más espedito y sin problemas. Una instalacion manual es posible pero no recomendada. No soy tu mama de todos modos :shrug:

!!!

Si quieres configurar el emulador manualmente, puedes tambien [descargar Project64 1.6 directamente desde Jabosoft](http://www.jabosoft.com/articles/114), junto con un parche para actualizar los Jabo plugins para mejor compatibilidad. Corre el instalador de la version 1.6 primero, luego aplica el parche 1.6.1 tanto corriendo el instalador o copiando los plugins a la carpeta Plugins en el caso de la version .zip.

!!!

Es sugerido que el emulador instalado **cualquier parte que no sea Program Files**, por ejemplo `C:\Project64 1.6`. Esto es debido a que los permisos de escritura estan restringidos para ese directorio en nuevas versiones de windows y cualquier escritura realizada por aplicaciones de legado seran derigidas a la carpeta VirtualStore, causando preguntarte por ejemplo donde estan tus archivos de guardado exactamente.

!!!
