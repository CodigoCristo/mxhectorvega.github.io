---
layout: post
title:  "Actualización del Script amigable automatizado que instala ArchLinux"
date:   2021-09-21 07:00:00 +0700
tags: [archlinux, brtfs, paru, pipewire, gnome, minimal]
---

<center>
<img src="https://raw.githubusercontent.com/mxhectorvega/mxhectorvega.github.io/master/_posts/instalador-de-arch-minimal/logo-arch.png" style="max-width:60%;width:auto;height:auto;">
</center>

Este instalador con bashismos es un Fork de Crisparch by [@CodigoCristo](https://github.com/codigocristo), que tiene tiene como finalidad, eficientar, mejorar y optimizar el proceso de instalación de ArchLinux, incluyendo las tecnologias recientes como particionado Brtfs, servidor de audio y video PipeWire, gestor de paquetes en Rust Paru y el entorno de escritorio Gnome 40., <mark>en la inteligencia de poder llegar a más usuarios a probar ArchLinux sin tantas complicaciones.</mark>

**Instrucciones:**
1. Iniciar en modo uefi o bios con el LiveUSB de ArchLinux
2. ``` loadkeys es``` (o segun la distribucion del teclado ``` la-latin1, es, en, us ```)
3. ``` bash <(curl https://mxhectorvega.github.io/gnomelite) ```
4. Seleccionar la unidad conectada donde se instalara ejemplo: ``` /dev/sdx ```:
5. Ingrese una contraseña root:
6. Ingrese un nombre de usuario estándar:
7. Ingrese una contraseńa para el usuario estándar :
8. Ingrese un nombre para el equipo:
9. Ingrese localizacion del idioma ejemplo ``` es_MX.UTF-8 ``` o ``` es_AR.UTF-8 ```

**Nota:**
Despues de la instalacion para cargar las configuraciones de Kitty, Ranger, Neovim, ZSH y un gestor de extenciones para gnome debe de hacer ``` bash <(curl https://mxhectorvega.github.io/scripts/dots1) ```

**Captura de pantalla:**
<center>
<img src="https://raw.githubusercontent.com/mxhectorvega/mxhectorvega.github.io/master/_posts/instalador-de-arch-minimal/gnome.png" style="max-width:100%;width:auto;height:auto;">
</center>

**Comunidad:**
- [Canal YouTube](https://youtube.com/mxhectorvega)
- [Grupo Telegram de ArchLinux](https://t.me/archLinuxes)
