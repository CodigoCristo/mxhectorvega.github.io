---
layout: post
title:  "Aplicar temas e iconos en Fedora SilverBlue"
date:   2021-03-15 07:00:00 +0700
tags: [fedora, silverblue, themes, icons]
---

<center>
<img src="https://raw.githubusercontent.com/mxhectorvega/mxhectorvega.github.io/master/_posts/temas-para-silverblue/theme.jpg" style="max-width:90%;width:auto;height:auto;">
</center>

Aplica temas para que tu software de usuario Flatpak para estar bien integrado con los temas GTK del sistema.

**Instrucciones:**
```bash
mkdir ~/.themes
mkdir ~/.icons
sudo cp -R /usr/share/themes/* ~/.themes
sudo cp -R /usr/share/icons/* ~/.icons
sudo flatpak override --filesystem=~/.themes
sudo flatpak override --filesystem=~/.icons
```

**Comunidad:**
- [Canal YouTube](https://youtube.com/mxhectorvega)
- [Grupo Telegram de Fedora](https://t.me/fedoralinuxes)
