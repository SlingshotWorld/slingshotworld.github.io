# Asztali (Windows .exe) változat

Attila csomagolása: a HTML-t egy kis Python-program (pywebview) saját ablakban nyitja meg,
böngésző nélkül. Az adatok a `%APPDATA%\SlingshotWorld` mappába mentődnek, és megmaradnak.

## Építés Windowson
1. Python 3.9+ telepítve ("Add to PATH" bepipálva).
2. Másold ide a gyökérben lévő `index.html`-t **`SlingshotWorld.html`** néven (a build ezt a nevet várja).
3. Tedd mellé az ikonfájlokat (`icon.ico` – a build ezt használja; `icon_prastie.ico`, `icon_tinta.ico` alternatívák).
4. Futtasd a `build_exe.bat`-ot. Eredmény: `dist\SlingshotWorld.exe`.

Az .exe-t és az ikonokat nem tároljuk a repóban (bináris, nagy); a kész .exe a GitHub **Releases** oldalra kerül.
