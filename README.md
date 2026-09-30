# UIC Wagon Number Calculator 🚆 (UIC-Wagennummer Rechner)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PWA Ready](https://img.shields.io/badge/PWA-Ready-success?style=for-the-badge)

*Bilingual Web Application (German / English) to calculate the Check Digit of a UIC wagon number using the Luhn Algorithm.*

---

## 🇺🇸 English Info

This repository contains a simple, perfectly responsive, single-file Web Application that calculates the **12th digit (Self-check digit)** of a UIC (International Union of Railways) wagon number.

### ✨ Features
* **Zero Dependencies:** The entire application logic, styling (Tailwind via CDN), and Progressive Web App (PWA) configuration is housed in one single `index.html` file.
* **Bilingual:** Instantly switch between English and German.
* **Visual Breakdown:** Shows exactly how the Luhn algorithm calculates the final number step-by-step.
* **PWA / Installable:** Contains a dynamic manifest and service worker. You can "Add to Home Screen" on iOS and Android devices, allowing it to function completely offline.
* **Auto-formatting & Copy:** Easily copy the beautifully formatted result to your clipboard.

### 🚀 Usage
There is no build process required. 
1. Simply clone the repository or download `index.html`.
2. Open `index.html` in any modern web browser.
3. *Alternatively:* Host it directly via GitHub Pages!

### 🧮 The Math (Luhn Algorithm)
1. Multiply the 11 digits alternately by `2` and `1` starting from the left.
2. If the product of a multiplication is greater than or equal to 10, calculate the sum of its digits (e.g., `14` becomes `1 + 4 = 5`).
3. Sum all the resulting numbers together.
4. The difference between this sum and the **next higher multiple of 10** is the check digit.

---

## 🇩🇪 Deutsche Info

Dieses Repository enthält eine einfache, vollständig responsive Single-File Web-App, die die **12. Stelle (Selbstkontrollziffer)** einer UIC-Wagennummer berechnet.

### ✨ Funktionen
* **Keine Abhängigkeiten:** Die gesamte App-Logik, das Styling (Tailwind via CDN) und die Progressive Web App (PWA) Konfiguration befinden sich in einer einzigen `index.html` Datei.
* **Zweisprachig:** Direkter Wechsel zwischen Deutsch und Englisch.
* **Transparenter Rechenweg:** Zeigt detailliert, wie der Luhn-Algorithmus das Endergebnis berechnet.
* **PWA / Installierbar:** Dank dynamischem Manifest und Service Worker kann die Seite über "Zum Home-Bildschirm hinzufügen" (iOS/Android) als eigenständige App installiert und komplett offline genutzt werden.
* **Auto-Formatierung & Kopieren:** Das fertig formatierte Ergebnis kann mit einem Klick kopiert werden.

### 🚀 Nutzung
Es ist kein Build-Prozess notwendig.
1. Repository klonen oder die `index.html` herunterladen.
2. Die `index.html` in einem beliebigen modernen Browser öffnen.
3. *Alternativ:* Einfach kostenlos über GitHub Pages hosten!

### 🧮 Die Mathematik (Luhn-Algorithmus)
1. Die 11 Ziffern werden von links nach rechts abwechselnd mit `2` und `1` multipliziert.
2. Ist das Produkt einer Multiplikation `10` oder größer, wird die Quersumme gebildet (z.B. aus `14` wird `1 + 4 = 5`).
3. Alle daraus resultierenden Zahlen werden addiert.
4. Die Differenz dieser Summe zum **nächsthöheren Vielfachen von 10** ist die gesuchte Prüfziffer.

---
### License
MIT License - feel free to use and modify!
