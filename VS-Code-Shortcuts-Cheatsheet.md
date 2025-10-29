# VS Code Shortcuts Cheatsheet - Linux 🚀
*Der Produktivitäts-Booster 9000 für Web Development*

---

## 🧭 Navigation (ohne Maus/Pfeiltasten)

### Zeilen & Wörter
```
Ctrl + G                → Gehe zu Zeile (Nummer eingeben)
Ctrl + ←/→             → Wort für Wort springen
Home/End               → Zeilenanfang/ende
Ctrl + Home/End        → Dateianfang/ende
Alt + ↑/↓              → Zeile nach oben/unten verschieben
```

### Suchen & Springen
```
Ctrl + F               → Suchen in Datei
Ctrl + Shift + F       → Suchen in allen Dateien
Ctrl + P               → Datei öffnen (fuzzy search)
Ctrl + Shift + P       → Command Palette
F12                    → Zu Definition springen
Alt + ←/→             → Zurück/Vorwärts navigieren
Ctrl + Click           → Zu Definition (bei Funktionen/Variablen)
```

---

## ✂️ Markieren (Selection)

### Text markieren
```
Shift + ←/→            → Zeichen für Zeichen
Ctrl + Shift + ←/→     → Wort für Wort markieren
Shift + Home/End       → Bis Zeilenanfang/ende
Ctrl + Shift + Home/End → Bis Dateianfang/ende
Ctrl + L               → Ganze Zeile markieren
Ctrl + A               → Alles markieren
Ctrl + Shift + L       → Alle Zeilen in Selection markieren
```

### Multi-Cursor Magic 🪄
```
Ctrl + D               → Nächstes gleiches Wort markieren
Ctrl + Shift + L       → Alle gleichen Wörter markieren
Alt + Click            → Zusätzlichen Cursor setzen
Ctrl + Alt + ↑/↓       → Cursor oberhalb/unterhalb
Ctrl + U               → Letzte Cursor-Operation rückgängig
Escape                 → Alle Cursor bis auf einen entfernen
```

---

## ✏️ Bearbeiten

### Zeilen manipulieren
```
Ctrl + Shift + K       → Zeile löschen
Ctrl + Shift + Enter   → Zeile oberhalb einfügen
Ctrl + Enter           → Zeile unterhalb einfügen
Ctrl + Shift + D       → Zeile duplizieren
Ctrl + /               → Zeile kommentieren/entkommentieren
Ctrl + Shift + A       → Block kommentieren
Alt + ↑/↓              → Zeile verschieben
```

### Code-Blöcke & Einrückung
```
Ctrl + Shift + [       → Bereich einklappen
Ctrl + Shift + ]       → Bereich ausklappen
Ctrl + K, Ctrl + 0     → Alle Bereiche einklappen
Ctrl + K, Ctrl + J     → Alle Bereiche ausklappen
Tab                    → Einrücken
Shift + Tab            → Ausrücken
Ctrl + ]               → Zeile einrücken
Ctrl + [               → Zeile ausrücken
```

### Copy & Paste & Undo
```
Ctrl + C               → Kopieren
Ctrl + V               → Einfügen
Ctrl + X               → Ausschneiden
Ctrl + Z               → Rückgängig
Ctrl + Shift + Z       → Wiederholen
Ctrl + Shift + V       → Einfügen ohne Formatierung
```

---

## 🎨 HTML/CSS/JS Emmet Shortcuts

### HTML Emmet (Type + Tab)
```
ul>li*5                → <ul><li></li><li></li>...</ul>
div.container          → <div class="container"></div>
input#name             → <input id="name">
div{Hello World}       → <div>Hello World</div>
a[href="#"]            → <a href="#"></a>
img[src alt]           → <img src="" alt="">
table>tr*3>td*4        → Tabelle mit 3 Zeilen, 4 Spalten
```

### CSS Emmet
```
m10                    → margin: 10px;
p20                    → padding: 20px;
w100                   → width: 100px;
h50                    → height: 50px;
bgc                    → background-color: ;
c                      → color: ;
```

### Tag-Navigation
```
Ctrl + Shift + .       → Zu schließendem Tag
Alt + .                → Auto-close Tag
F2                     → Tag/Variable umbenennen
```

---

## 📁 File Explorer & Tabs

### Dateien
```
Ctrl + N               → Neue Datei
Ctrl + S               → Speichern
Ctrl + Shift + S       → Speichern unter
Ctrl + W               → Tab schließen
Ctrl + Shift + T       → Letzten Tab wieder öffnen
Ctrl + Tab             → Zwischen Tabs wechseln
Ctrl + PageUp/PageDown → Tab wechseln
Ctrl + 1/2/3...        → Zu Tab 1/2/3...
```

### Explorer & Panels
```
Ctrl + Shift + E       → File Explorer fokussieren
Ctrl + Shift + `       → Terminal öffnen/fokussieren
Ctrl + J               → Panel (Terminal/Problems) ein/aus
Ctrl + B               → Sidebar ein/ausblenden
Ctrl + Shift + Y       → Debug Console
```

---

## 🔍 Suchen & Ersetzen

### Erweiterte Suche
```
Ctrl + F               → Suchen
Ctrl + H               → Suchen & Ersetzen
F3 / Enter             → Nächstes Ergebnis
Shift + F3             → Vorheriges Ergebnis
Alt + Enter            → Alle Vorkommen auswählen
Ctrl + Shift + F       → In allen Dateien suchen
Ctrl + Shift + H       → In allen Dateien ersetzen
```

### Regex in Suche
```
.*                     → Beliebiger Text
\d+                    → Zahlen
\w+                    → Wörter
^                      → Zeilenanfang
$                      → Zeilenende
```

---

## 🔧 Development Shortcuts

### JavaScript/jQuery spezifisch
```
Ctrl + Space           → IntelliSense (Autocomplete)
Ctrl + Shift + Space   → Parameter hints
F12                    → Zu Funktionsdefinition
Shift + F12            → Alle Referenzen anzeigen
F2                     → Variable/Funktion umbenennen
Ctrl + K, Ctrl + I     → Hover Info anzeigen
```

### Debugging
```
F9                     → Breakpoint setzen/entfernen
F5                     → Debugging starten
F10                    → Step Over
F11                    → Step Into
Shift + F11            → Step Out
Shift + F5             → Debugging stoppen
```

---

## ⚡ Produktivitäts-Hacks

### Schnelle Arbeitsflows
```
Ctrl + K, Ctrl + S     → Keyboard Shortcuts öffnen
Ctrl + K, Ctrl + T     → Theme wechseln
Ctrl + Shift + P       → Command Palette (alles möglich!)
Ctrl + ,               → Settings öffnen
Ctrl + K, Ctrl + O     → Ordner öffnen
```

### Multi-Cursor Workflows
1. **Wort markieren** → `Ctrl + D` (mehrmals) → Alle gleichen markieren
2. **Alt + Click** → Mehrere Cursor setzen
3. **Ctrl + Shift + L** → Alle Zeilen in Selection
4. **Gleichzeitig tippen** → Alle Cursor parallel

### jQuery Development Workflow
1. `Ctrl + P` → HTML-Datei öffnen
2. `Ctrl + G` → Zu `<script>` Section (z.B. Zeile 20)
3. Tippe: `$("` → `Ctrl + Space` für Autocomplete
4. `Ctrl + D` für Multi-Selection bei wiederholenden Selektoren

---

## 💡 Pro-Tipps

### Eigene Snippets erstellen
1. `Ctrl + Shift + P` → "Configure User Snippets"
2. "javascript.json" auswählen
3. jQuery-Snippets hinzufügen:

```json
{
    "jQuery Click": {
        "prefix": "jqclick",
        "body": [
            "$(\"#$1\").click(function(e) {",
            "\te.preventDefault();",
            "\t$2",
            "});"
        ]
    },
    "jQuery Ready": {
        "prefix": "jqready",
        "body": [
            "$(document).ready(function() {",
            "\t$1",
            "});"
        ]
    }
}
```

### Terminal Shortcuts (Fish Shell)
```
Ctrl + Shift + `       → Neues Terminal
Ctrl + C               → Prozess beenden
Ctrl + L               → Terminal leeren
Tab                    → Autocomplete
Ctrl + R               → History durchsuchen
```

---

## 🎯 Meine Top 10 Must-Know Shortcuts

```
1. Ctrl + P           → Datei schnell öffnen
2. Ctrl + G           → Zu Zeile springen  
3. Ctrl + D           → Gleiches Wort markieren (Multi-Cursor)
4. Ctrl + L           → Ganze Zeile markieren
5. Alt + ↑/↓          → Zeile verschieben
6. Ctrl + /           → Kommentieren/entkommentieren
7. Ctrl + Shift + K   → Zeile löschen
8. Ctrl + ←/→         → Wort-weise springen
9. Home/End           → Zeilenanfang/ende
10. Ctrl + Shift + P  → Command Palette (Supermacht!)
```

---

## 🚀 Challenge: Probiere diese Workflows

### Workflow 1: jQuery Selektor erstellen
1. `Ctrl + G` → Gehe zu Script-Bereich
2. Tippe: `$("li")` 
3. `Ctrl + D` → Markiere alle gleichen
4. Erweitere zu: `$("li:eq(0)")`

### Workflow 2: HTML schnell erstellen
1. Tippe: `ul>li*5{Item $}` + Tab
2. `Ctrl + D` auf "Item" → Alle markieren
3. Ändere zu deinem Text

### Workflow 3: Multi-File-Suche
1. `Ctrl + Shift + F`
2. Suche: `getElementById`
3. `Ctrl + Shift + H` → Ersetze mit `querySelector`

---

*Erstellt für dein Web-Development Learning Journey* 💪  
*SAP UI5 Skills incoming!* 🎯