---
description: "Guia exhaustiva de la configuracion del emulador para speedruns de Super Mario 64" 
---

# Configurando los plugins

Por defecto, Project64 1.6 viene con plugins de Jabo. Si bien generalmente funcionan, estos tienen varios defectos, como sombras faltantes en graficas de intel o audio distorcionados. Esta sección proporciona información sobre los plugins recomendados, así como sobre cómo configurarlos.

!!! Respecto a configurar manualmente
Todos los plugins necesarios son provistos por el paquete presentado en esta guia, pero si has hecho la instalación manual, deberas instalar los plugins manualmente tambien. Esto es simplemente copiar los archivos .dll de los plugins dentro de una carpeta llamada Plugin dentro de la carpeta de instalacion de Project64.
!!!

## Selección de plugins
Los Plugins pueden ser cambiados al abrir el menu  de **Options -> Settings**. Luego de seleccionarlos, los plugins pueden ser configurados en **Options -> Configure Graphics/Audio/Controller plugin**. Sigue los links para información detallada de como configurar plugins individualmente.

### Plugins graficos
- **Recomendado:** [**LINK's GLideN64**](gliden64_link.md)
- Alternativa: [GLideN64 rev.8004dc2](gliden64_old.md) or [glN64](gln64.md)

### Plugins de audio
- **Recomendado:** [**Azimer's HLE v0.70 WIP 10**](azi.md)

### Plugins de mando
Lamentablemente hay un par de diferentes opciones para plugins de mando, con diferentes caracteristicas cada uno, por lo que el mejor plugin depende de que mando quieras usar.

- Para usuarios del adaptador **Raphnet N64 to USB v3**: [**raphnetraw**](raphnetraw.md)
- Para mandos **Xbox**, **Dualshock 4/5**, **Switch Pro Controller** o **XInput**: [**Octomino's SDL Input**](octomino.md)
- Para  **Teclado**: [**Luna's DirectInput**](luna.md) (recommended) or [**LINK's DirectInput**](keyboardinput.md)
- Para otros mandos con DirectInput o genericos: [**N-Rage's Input**](nrage.md)
- Para adaptadores de **Gamecube para Wii U/Switch**, [**mira esta pagina**](wiiu_gc.md) para instrucciones especiales.

### RSP plugin

- **Recomendado:** [**PJ64 Fixups**](fixups.md)
