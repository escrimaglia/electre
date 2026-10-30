# ELECTRE

Aplicación de decisión multicriterio con **ELECTRE I y II** — Universidad Tecnológica Nacional, FRC.  
Cátedra *Decisiones en Escenarios Complejos*.  
Autor: Edgardo Scrimaglia.  

## Descargar

Entrá a **[la última versión](https://github.com/escrimaglia/electre/releases/latest)** y bajá el archivo de tu sistema:

| Sistema | Archivo |
|---|---|
| Windows 10 u 11 | `ELECTRE-<versión>-Windows-Setup.exe` |
| Mac con Apple Silicon (M1, M2, M3…), macOS 14 o posterior | `ELECTRE-<versión>-Mac-AppleSilicon.dmg` |
| Mac con Intel (en general, modelos de 2018 en adelante), macOS 14 o posterior | `ELECTRE-<versión>-Mac-Intel.dmg` |
| Linux (64 bits), Ubuntu 22.04 o posterior o equivalente | `ELECTRE-<versión>-Linux-x86_64.AppImage` |

**¿Mac con Apple Silicon o con Intel?:** Menú de la manzana → *Acerca de esta Mac*: si dice **Chip Apple M…** es Apple Silicon; si dice
**Procesador Intel…**, Intel.  

No hace falta instalar nada más (ni Python, ni Docker, ni internet para usarla).  

## Instalar

**Windows.** Ejecutá el instalador. Como el programa no tiene firma digital, Windows puede mostrar **"Windows protegió su
PC":** tocá **Más información → Ejecutar de todas formas**. No pide permisos de administrador. Queda en el menú Inicio.  

**Mac.** Abrí el `.dmg` y arrastrá **ELECTRE** a **Aplicaciones**. La primera vez, macOS avisa que no puede verificar
al desarrollador (o que la app no es segura), porque no tiene firma digital:  
1. Intentá abrir ELECTRE y cerrá el aviso con **Listo** (no la mandes a la papelera).  
2. Abrí *Ajustes del Sistema → Privacidad y seguridad* y bajá hasta *Seguridad*. El botón **Abrir igualmente** aparece
   recién después de haber intentado abrirla.  
3. Tocá **Abrir igualmente** y confirmá con tu contraseña o Touch ID.  

Después abre normalmente. Puede volver a pedirlo con cada versión nueva.  

**Linux.** Dale permiso de ejecución y abrilo: `chmod +x ELECTRE-*.AppImage && ./ELECTRE-*.AppImage`. Si no arranca,
instalá FUSE 2 (Ubuntu 22.04: `sudo apt install libfuse2`; Ubuntu 24.04 o posterior: `sudo apt install libfuse2t64`).  

## Usar

ELECTRE se abre en su propia ventana, como cualquier programa (no usa tu navegador). Funciona sólo en tu computadora.
Para cerrarla, cerrá la ventana. Tus casos quedan guardados para la próxima vez. El **Manual de uso** está en el menú de la aplicación y también se puede bajar: [ELECTRE_Manual_de_uso.pdf](https://github.com/escrimaglia/electre/releases/latest/download/ELECTRE_Manual_de_uso.pdf).  

Para **actualizar**, cerrá ELECTRE e instalá la versión nueva encima (tus casos se conservan; el aviso de seguridad puede volver a aparecer). Para **desinstalar**: en Windows, desde
*Configuración → Aplicaciones*; en Mac, desde Finder, arrastrá ELECTRE de Aplicaciones a la papelera (no desde Launchpad); en Linux, borrá el archivo. Los casos quedan en
`%APPDATA%\ELECTRE` (Windows), `~/Library/Application Support/ELECTRE` (Mac) o `~/.local/share/electre` (Linux).  

---

## English

Multi-criteria decision application with **ELECTRE I and II** — Universidad Tecnológica Nacional, FRC.  
Autor: Edgardo Scrimaglia.  

**Download** the file for your system from **[the latest release](https://github.com/escrimaglia/electre/releases/latest)**:
`…-Windows-Setup.exe` (Windows 10/11), `…-Mac-AppleSilicon.dmg` (Mac with an Apple M chip), `…-Mac-Intel.dmg` (Mac with an
Intel processor, generally 2018 models or later; both need macOS 14 or later) or `…-Linux-x86_64.AppImage` (64-bit Linux, Ubuntu 22.04 or later). Nothing else is needed (no Python, Docker or internet).  

**Install.** *Windows:* run the installer; if *"Windows protected your PC"* appears, choose **More info → Run anyway** (the
program is not digitally signed). *Mac:* open the `.dmg`, drag **ELECTRE** to **Applications**; the first time,
try to open ELECTRE and close the warning with **Done**, then go to *System Settings → Privacy & Security*, scroll to
*Security* and click **Open Anyway** (the button only appears after that first attempt). *Linux:*
`chmod +x ELECTRE-*.AppImage && ./ELECTRE-*.AppImage` (needs FUSE 2: `sudo apt install libfuse2`, or `libfuse2t64` on Ubuntu 24.04 or later).  

**Use.** ELECTRE opens in its own window, like any program (it does not use your browser); it runs only on your computer.
To close it, close the window. Your cases stay saved.
The **User manual** is in the app's menu and can also be downloaded: [ELECTRE_User_Manual.pdf](https://github.com/escrimaglia/electre/releases/latest/download/ELECTRE_User_Manual.pdf).  
