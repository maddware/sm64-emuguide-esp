---
description: "Guia exhaustiva de la configuracion del emulador para speedruns de Super Mario 64" 
---

# Configuración de adaptador de mando de Gamecube para Wii U/Switch

Para este adaptador, hay dos opciones para usarlo. Puedes usar un plugin que de soporte al adaptador nativamente (Parecido a Yuzu o Dolphin) o puedes usar el driver de Massive en conjunto con N-Rage.

!!!Precaución antes de que sigas
Si tienes un adaptador generico, podrias querer **evitar esta parte de la guia completamente**, y en vez usar el modo PC de tu adaptador con el [**N-Rage's Input**](nrage.md). Esto seria mas facil de configurar y utilizar, tambien funciona relativamente igual.

Adicionalmente, [algunos adaptadores (tienen un boton en vez de un switch) aparentemente **no pueden ser cambiado a modo Wii U**](https://forums.dolphin-emu.org/Thread-cannot-switch-compatible-gamecube-adapter-to-wiiu-switch-mode), lo cual es estrictamente necesario para que funcione.
!!!
## Plugin de input nativa

Para instrucciones detalladas, revisa la pagina dedicada al plugin.

[!ref pj64-wiiu-gcn](pj64-wiiu-gcn.md)
## Driver de Massive

Si quieres usar el adaptador con otros plugins, es necesario instalar los drivers los cuales haran que el mando funcione como DirectInput.
!!!Precaución
Hay reportes de drivers con problemas para algunos adaptadores genericos. Si no tienes el adaptador oficial de Nintendo o el de Mayflash, entonces 
There have been reports of the drivers having problems with some third party adapters. If you don't have the official Nintendo adapter or the Mayflash adapter, ten cuidado :scream:.
!!!

!!!Precaución
Si usas **Windows 11**, es posible que no seas capaz de instalar vJoy. Revisa https://github.com/shauleiz/vJoy/issues/57 para revisar detalles.
!!!

### Instalando los drivers de Massive 
Instrucciones detalladas del proceso de instalacion se pueden encontrar abajo.

[!ref target="blank" text="Pagina de Massive"](http://m4sv.com/page/wii-u-gcn-usb-driver)

### Configuraciones de drivers adicionales

After installing the drivers, it's a good idea to change a couple of settings. In the adapter application, click on the **Configure** button. By default, all four ports are enabled - you might want to **disable** the unused ones to avoid cluttering your device list. Set the **analog stick deadzones** to **0** (you'll be able to adjust the deadzone in Project64 later on). Check **Disable ports on exit** to disable vJoy devices after you're done using the drivers. After you're done, click on **Save and Close**.

![Example configuration](./img/m4sv_conf.png)

### Calibración de mando
Some Gamecube controllers come with analog stick offset out of the factory. Unfortunately, Massive's drivers don't calibrate the stick centers, like a real console would do. To compensate for this, you can callibrate the controller in Windows. In the adapter window, click on **Windows Gamepad Info**, then double click on **vJoy Device**. Go to the **Settings** tab and click on the **Calibrate** button. Follow the instructions in the calibration wizard. After finishing, your stick should be properly centered.

Additional information on how to use N-Rage can be found on its own page, linked below.

[!ref N-Rage's Input plugin](nrage.md)
