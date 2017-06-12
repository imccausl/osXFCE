osXFCE Theme
---

Yet another(?) macOS-like theme for Linux, osXFCE uses [arc-flatabulous](https://github.com/andreisergiu98/arc-flatabulous-theme) as its base, 
but is deeply customized for use with [vala-panel-appmenu](https://github.com/rilian-la-te/vala-panel-appmenu) and XFCE.

Features include: 
- Boldface Application dropdown menu
- Window controls that are closer to one-another
- A subtle gradient on gtk title and headerbars
- Rounded corners on bottom of menu (requires a capable window manager for optimal display)
- A corresponding Plank theme that more closely resembled the macOS Sierra dock

---
Screenshot
---
![osXFCE](http://i.imgur.com/uZb9wpO.png)

---
Installation Instructions
---
```
git clone https://github.com/imccausl/osXFCE.git ~/
cp -r ~/osXFCE ~/.themes/osXFCE
```

To install the plank theme, copy `plank/flataOSX-Theme` to your `.local/share/plank/themes` directory.

---

Development is most likely somewhat slow since I am learning GTK theme development as I go, 
with a lot of trial and error. If you want to help, please submit a pull request!