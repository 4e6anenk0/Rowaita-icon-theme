# Rowaita icons

<p align="center">
    <img width=200 height=200 src="logo.png" alt="Logo">
</p>

Rowaita is a Linux icon pack that combines simplicity and convenience. Informative mimtype icons will help you find the right file, even without having to look at the file extensions. And rounded shapes will give your environment a harmonious look. If you like standard Gnome icons and Papirus, Marwaita icons, then Rowaita icons are definitely worth your attention. 

## Installation instruction:

Move the folders (Rowaita, Rowaita-Dark, Rowaita-Light) of icons to: **/home/.local/share/icons** or **/home/.icons** (in user mode) or **/usr/share/icons** (in root mode).

\* If the desired target folder does not exist, you can create it

## Key differences:

This fork includes some modifications and changes. Below you can see some key differences:

1) Changed the design of some icons to better match the overall style.

2) Changed the shape and design of folders. They are now rounded and have bold symbols on the folder icon. As for me, now they are perfectly combined with the Gnome UI. Look at this:

<p align="center">
    <img width=500 src="img/screenshot2.png" alt="Screenshot of folders icons">
</p>

<p align="center">
    <img src="img/screenshot1.png" alt="Screenshot of folders icons on desktop">
</p>

<p align="center">
    <img src="img/screenshot3.png" alt="Screenshot of icons on desktop">
</p>

___

<p align="center"> 
If you like this icons pack, please consider buying me a coffee:
</p>

<p align="center"> <a href="https://www.buymeacoffee.com/yppppl" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-yellow.png" alt="Buy Me A Coffee ❤️" height="41"></a> </p>

___

3) The mimetypes for the following files have been added to this icon pack. This is really cool for developers as it allows you to quickly browse files by type. For example:

<p align="center">
    <img width=500 src="img/img1.png" alt="Office icons">
</p>
<p align="center">
    <img width=500 src="img/img2.png" alt="Dev icons">
</p>
<p align="center">
    <img width=500 src="img/img3.png" alt="Archives icons">
</p>
<p align="center">
    <img width=500 src="img/img4.png" alt="Other icons">
</p>

Added or changed:
epub, json, json-ld, doc, xls, ppt, xlsx, pptx, docx, colab, google doc, google pres, google spre, ipynb, djvu, csv, dockerfile, erlang, haskell, kotlin, objective c, scala, swift, dart, image, php, css, perl, 7zip, aab, acad, apk, illustrator, psd, less, sass, cobol, fortran, pascal, vala, flatpak, hex, lua, markdown, readme, certificatem yaml, tar, arduino, binary, sql, wasm, bzip, rar, tar, C#, C++, C, Swift, Obj C, erlang, go, haskell, hex, go, kotlin, lua, ruby, rust, sl ...

## Known problems and ways to solve them:
### Problem: Icons are missing or displayed incorrectly in Flatpack applications
If your Flatpack apps are missing icons or not showing up, here's what you can do:
1) Make sure that the icons are actually in the required directory. That is, they must not be placed via a symbolic link.
2) Grant permission to the directory of custom icons. This can be done globally or for the user. For example: 
```bash
# globally
flatpak override --filesystem=~/.icons
# or for user
flatpak --user override --filesystem=~/.icons
```
If it doesn't work, you can try this:
```bash
sudo flatpak override --system --filesystem=~/.icons
```
___

<p align="center"> 
If you like this icons pack, please consider buying me a coffee:
</p>

<p align="center"> <a href="https://www.buymeacoffee.com/yppppl" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-yellow.png" alt="Buy Me A Coffee ❤️" height="41"></a> </p>

This project has mixed projects:

- [Marwaita icons](https://github.com/darkomarko42/Marwaita-Icons): GNU General Public License v3.0
- [Papirus Icons](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme): GNU General Public License v3.0
- [Adwaita icons](https://gitlab.gnome.org/GNOME/adwaita-icon-theme): GNU Lesser General Public License v3.0

uses components:
[charm-icons](https://github.com/jaynewey/charm-icons), [typicons.font](https://github.com/stephenhutchings/typicons.font), [Font-Awesome](https://github.com/FortAwesome/Font-Awesome), [dripicons](https://github.com/amitjakhu/dripicons), [ficons](https://github.com/fiction-com/ficons), [collecticons-lib](https://github.com/developmentseed/collecticons-lib), [fluentui-system-icons](https://github.com/microsoft/fluentui-system-icons), [remixicon](https://github.com/Remix-Design/remixicon), [octicons](https://github.com/primer/octicons)
