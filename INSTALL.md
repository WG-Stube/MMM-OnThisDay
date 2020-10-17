
# Installation Wikipedia an diesem Tag

## Manuelle Installation

1. In den Modul Ordner wechseln
`cd ~/MagicMirror/modules`

2. Erweiterung herunterladen und installieren
- `git clone https://github.com/nkl-kst/MMM-OnThisDay`
- `cd MMM-OnThisDay/`
- `npm install --only=prod`

3. Modul einrichten
 `nano ~/MagicMirror/config/config.js`
 In der Datei ganz am Ende der Liste (nach dem letzten `},` ) einfügen
```js
{
    module: 'MMM-OnThisDay',
    position: "top_right", // All available positions
    config: {
    }
},
```

4. Nano schliessen mit `CTRL+O` und `CTRL+X`

5. Mirror starten zum testen 
- `cd ~/MagicMirror`
- `npm run start`

