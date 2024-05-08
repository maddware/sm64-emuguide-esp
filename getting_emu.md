---
description: "Guía exhaustiva de la configuración del emulador para speedruns de Super Mario 64" 
---

# Adquiriendo el emulador

La única versión de Project64 permitida para speedruns en leaderboards es la 1.6. **Todas las otras versiones (tales como 1.7 o 2.x) estan prohibidas.** Las leaderboards también permiten el uso de Mupen64Plus y OpenEmu, permitiendo opciones de emulación nativa para usuarios de Linux y Mac respectivamente. Esta guia se enfoca en configurar Project64 1.6 especificamente.

## Descarga

Para acelerar el proceso de configuración, existe un paquete preconstruido disponible con el emulador y los mejores plugins. Extrae el archivo en cualquier carpeta que quieras, luego sigue las instrucciones de esta guía

Ultima actualización en 2022-10-16.

[!file Enlace 1 (Dropbox)](https://www.dropbox.com/s/cgkbhsarjthgnz8/Project64%201.6%20%28wermi%27s%20build%20v7%29.exe?dl=1)
[!ref target="blank" text="Enlace 2 (GDrive)"](https://drive.google.com/file/d/1GlvT7-TBjLz5ii0UsswDnqZZF4VVx3US)

!!!
Si tienes errores cargando cualquiera de los plugins, vas a necesitar instalar la versión apropiada de Visual C++ runtimes. Por conveniencia, un paquete all-in-on puede ser encontrado acá: https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/
!!!

## Configuración manual

!!!warning

Esta guía esta escrita asumiendo que usas la versión provista en esta página para hacer el proceso más expedito y sin problemas. Una instalación manual es posible pero no recomendada. No soy tu mama de todos modos :shrug:

!!!

Si quieres configurar el emulador manualmente, puedes también [descargar Project64 1.6 directamente desde Jabosoft](http://www.jabosoft.com/articles/114), junto con un parche para actualizar los Jabo plugins para mejor compatibilidad. Corre el instalador de la versión 1.6 primero, luego aplica el parche 1.6.1 tanto corriendo el instalador o copiando los plugins a la carpeta Plugins en el caso de la versión .zip.

!!!

Es sugerido que el emulador esté instalado en **cualquier directorio que no sea Program Files o Archivos de programa**, por ejemplo `C:\Project64 1.6`. Esto es debido a que los permisos de escritura están restringidos para ese directorio en nuevas versiones de windows y cualquier escritura realizada por aplicaciones de legado serán dirigidas a la carpeta VirtualStore, causando preguntarte por ejemplo donde están tus archivos de guardado exactamente.

!!!
