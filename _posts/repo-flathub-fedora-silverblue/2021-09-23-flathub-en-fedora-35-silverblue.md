---
layout: post
title:  "Instalación de repositorio Flathub en Fedora SilverBlue 35"
date:   2021-09-23 18:00:00 +0700
tags: [fedora, flatpak, flathub, silverblue]
---

<center>
<img src="https://raw.githubusercontent.com/mxhectorvega/mxhectorvega.github.io/master/_posts/repo-flathub-fedora-silverblue/flathub.png" style="max-width:100%;width:auto;height:auto;">
</center>

En relación al uso regular del sistema inmutable de Fedora SilverBlue, donde la intención es que el usuario no toque el SO principal, separando el software instalado instalado por el usuario, tomando en cuenta que los paquetes flathub son mas seguros por ejecutarse de modo contenerizado, así hará que la experiencia del usuario final sea más al estilo iOS by Apple.

**Instrucciones:**
1. Abra una terminal.
2. Copiar y pegar: ``` flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo ```
3. Escribir nuestra contraseña

Ahora podrás instalar software disponible de Fathub estable ya sea desde GnomeSoftware o desde la terminal con el comando ``` flatpak install nombre_del_paquete ```

**Comunidad:**
- [Canal YouTube](https://youtube.com/mxhectorvega)
- [Grupo Telegram de Fedora](https://t.me/fedoralinuxes)
