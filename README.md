# ELECTRE

Aplicación de decisión multicriterio con **ELECTRE I y II** — Universidad Tecnológica Nacional, FRC.  
Cátedra *Decisiones en Escenarios Complejos*.  
Autor: Edgardo Scrimaglia.  

## Descargar

Entrá a **[la última versión](https://github.com/escrimaglia/electre/releases/latest)** y bajá el archivo de tu sistema:

| Sistema | Archivo |
|---|---|
| Windows 10 u 11 | `ELECTRE-<versión>-Windows-Setup.exe` |
| Mac con Apple Silicon (M1, M2, M3…) | `ELECTRE-<versión>-Mac-AppleSilicon.dmg` |
| Mac con Intel | `ELECTRE-<versión>-Mac-Intel.dmg` |
| Linux (64 bits) | `ELECTRE-<versión>-Linux-x86_64.AppImage` |

**¿Mac con Apple Silicon o con Intel?:** Menú de la manzana → *Acerca de esta Mac*: si dice **Chip Apple M…** es Apple Silicon; si dice
**Procesador Intel…**, Intel.  

No hace falta instalar nada más (ni Python, ni Docker, ni internet para usarla).  

## Instalar

**Windows.** Ejecutá el instalador. Como el programa no tiene firma digital, Windows puede mostrar **"Windows protegió su
PC":** tocá **Más información → Ejecutar de todas formas**. No pide permisos de administrador. Queda en el menú Inicio.  

**Mac.** Abrí el `.dmg` y arrastrá **ELECTRE** a **Aplicaciones**. La primera vez, macOS avisa que no puede verificar
al desarrollador: abrí *Ajustes del Sistema → Privacidad y seguridad* y tocá **Abrir igualmente** (o clic derecho sobre
ELECTRE → **Abrir**). Después abre normalmente.  

**Linux.** Dale permiso de ejecución y abrilo: `chmod +x ELECTRE-*.AppImage && ./ELECTRE-*.AppImage`. Si no arranca,
instalá FUSE 2 (en Ubuntu: `sudo apt install libfuse2`).  

## Usar

Al abrir ELECTRE aparece una ventanita *"ELECTRE está funcionando"* y la aplicación se abre en tu navegador. Funciona sólo
en tu computadora. Para cerrarla, tocá **Cerrar ELECTRE** en la ventanita; si cerrás el navegador, se cierra sola a los
pocos minutos. Tus casos quedan guardados para la próxima vez. El **Manual de uso** está en el menú de la aplicación.  

Para **actualizar**, instalá la versión nueva encima (tus casos se conservan). Para **desinstalar**: en Windows, desde
*Configuración → Aplicaciones*; en Mac, desde Finder, arrastrá ELECTRE de Aplicaciones a la papelera (no desde Launchpad); en Linux, borrá el archivo. Los casos quedan en
`%APPDATA%\ELECTRE` (Windows), `~/Library/Application Support/ELECTRE` (Mac) o `~/.local/share/electre` (Linux).  

---

## English

Multi-criteria decision application with **ELECTRE I and II** — Universidad Tecnológica Nacional, FRC.  
Autor: Edgardo Scrimaglia.  

**Download** the file for your system from **[the latest release](https://github.com/escrimaglia/electre/releases/latest)**:
`…-Windows-Setup.exe` (Windows 10/11), `…-Mac-AppleSilicon.dmg` (Mac with an Apple M chip), `…-Mac-Intel.dmg` (Mac with an
Intel processor) or `…-Linux-x86_64.AppImage` (64-bit Linux). Nothing else is needed (no Python, Docker or internet).  

**Install.** *Windows:* run the installer; if *"Windows protected your PC"* appears, choose **More info → Run anyway** (the
program is not digitally signed). *Mac:* open the `.dmg`, drag **ELECTRE** to **Applications**; the first time, go to
*System Settings → Privacy & Security* and click **Open Anyway** (or right-click ELECTRE → **Open**). *Linux:*
`chmod +x ELECTRE-*.AppImage && ./ELECTRE-*.AppImage` (needs FUSE 2: `sudo apt install libfuse2`).  

**Use.** A small *"ELECTRE is running"* window appears and the app opens in your browser; it runs only on your computer.
Close it with **Close ELECTRE**, or just close the browser and it shuts down after a few minutes. Your cases stay saved.
The **User manual** is in the app's menu.  
