# Polski Dvorak programisty

Układ klawiatury Dvoraka programisty z polskimi znakami, dla systemu macOS.

![schemat klawiatury](https://raw.githubusercontent.com/maxadamski/polski-dvp/master/polski_dvp-apple_wired.png)

### Instalacja

```
cp -R "polski-dvp.bundle" "/Library/Keyboard Layouts/com.maxadamski.polski-dvp.bundle"
```

### Edycja

Pliki `keylayout` i `bundle` można edytować w programie Ukelele (`brew cask install ukelele`)

### Schematy

Schematy zostały utworzone na stronie www.keyboard-layout-editor.com.

Schematy można edytować importując plik `json`.

### Ikony

Aby pozyskać ikony klawiatur należy użyć następujących komend:

```
mkdir icons
curl https://raw.githubusercontent.com/phible/scripts/master/apple-kbd-dat-icon-extract.py -o extract.py
extract.py -o icons
```

### Licencja

MIT
