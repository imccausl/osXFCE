osXFCE Theme
---

Yet another(?) macOS-like theme for Linux, osXFCE uses [arc-flatabulous](https://github.com/andreisergiu98/arc-flatabulous-theme) as its base, 
but is deeply customized for use with [vala-panel-appmenu](https://github.com/rilian-la-te/vala-panel-appmenu) and XFCE.

Features include: 
- Boldface Application dropdown menu
- Window controls that are closer to one-another
- A subtle gradient on gtk title and headerbars
- Rounded corners on bottom of menu (requires a capable window manager for optimal display)
- A corresponding Plank theme that more closely resembles the macOS Sierra dock

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

To install the plank theme, copy `plank/flatabOSX-Theme` to your `.local/share/plank/themes` directory.

---
Things that I could use help with:
---

- Is it possible to round the top corners of submenus in the global menu while leaving the parent menus without rounded top corners?
- Is it possible to round the top corners of dropdown menus outside of the global menu without affecting the global menus?
- I can't seem to get opacity to work on menus -- am I doing something wrong or is this WM-specific?
- Rounded corner masking is a little more artifacty than I'd like: works fine on the top corners of windows, but the bottom corners of menus against lighter backgrounds looks a bit weird.

---

Development is most likely somewhat slow since I am learning GTK theme development as I go, 
with a lot of trial and error. If you want to help, please submit a pull request!