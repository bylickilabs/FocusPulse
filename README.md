|[► FocusPulse Pro ◄](https://github.com/bylickilabs/FocusPulse-Pro)
|---|

### 🧠 FocusPulse – Der minimalistische Konzentrationstracker im Browser

![HTML5](https://img.shields.io/badge/HTML5-Active-%23E34F26?style=for-the-badge&logo=html5&logoColor=white) | ![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow?style=for-the-badge&logo=javascript) | ![Chart.js](https://img.shields.io/badge/Chart.js-integrated-%2300fff7?style=for-the-badge) | ![LocalStorage](https://img.shields.io/badge/Storage-local-orange?style=for-the-badge) | ![Responsive](https://img.shields.io/badge/Responsive-Ready-green?style=for-the-badge) | ![MIT License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
|---|---|---|---|---|---|

|![FocusPulse1](https://github.com/user-attachments/assets/3ef3bc3b-4380-4b4b-bd80-5bb61e2a42f9)|
|---|

<br>

---

<br>

> 🔍 Projektübersicht

> **FocusPulse** ist ein leichtgewichtiges Tool zur Konzentrationsverfolgung.  
  - Es erkennt deine Maus- und Tastatureingaben in Echtzeit und speichert Fokusphasen – lokal, anonym, datensicher.

Ideal für:
- Selbstbeobachtung im Alltag
- Fokus-Training & Pomodoro
- Schüler, Studenten, Entwickler

<br>

---

<br>


## ✨ Hauptfunktionen

| Funktion               | Beschreibung                                         |
|-------------------------|-----------------------------------------------------|
| 🕹️ Live-Tracking       | Erfassung von Maus- & Tastaturaktivität             |
| 🕐 Zeitintervall       | Messung alle 30 s / 1 min / 2 min                   |
| 📊 Chart-Auswertung    | Fokusanzeige als Liniendiagramm mit Chart.js        |
| 📦 Lokale Speicherung  | Speicherung im Browser (`localStorage`)             |
| 🔄 Zurücksetzen        | Zurücksetzen der aktuellen Session                  |
| 📤 CSV-Export          | Sessiondaten exportieren                            |
| 🎯 Fortschrittsanzeige | Visualisierung des Fokusziels                       |

<br>

---

<br>


> 🚀 Nutzung (lokal)

1. Projektordner entpacken
2. Öffne `index.html` im Browser  
   → ⚠️ **Nicht als `file:///` öffnen**, sondern über lokalen Server starten:

### ▶ mit Python (empfohlen)
```bash
cd FocusPulse
python -m http.server
```

> Aufrufen unter:
```yarn
http://localhost:8000/
```

▶ mit Node.js (z. B. http-server)

```yarn
npx http-server
```

<br>

---

<br>

> 🧩 Projektstruktur

```yarn
FocusPulse/
├── index.html
├── css/
│   └── style.css
├── js/
│   ├── tracker.js
│   ├── chart.js
│   ├── utils.js
│   └── storage.js
```

<br>

---

<br>

> 📤 CSV-Export
  - Mit einem Klick erhältst du eine .csv mit:

```yarn
Zeitpunkt,Aktiv
12:00:30,1
12:01:30,1
12:02:30,0
```

<br>

---

<br>

>🔖 Tags (GitHub Topics)

```yarn
focuspulse
focus-tracker
productivity
chartjs
localstorage
vanillajs
self-monitoring
offline-webapp
minimal-ui
```

<br>

---

<br>

📄 Lizenz
MIT License [LICENSE](LICENSE)

<br>
