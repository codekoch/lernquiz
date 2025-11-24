# <a href=https://codekoch.github.io/lernquiz/>lernquiz</a>

🎓 H5P-Style Quiz Builder (Offline Edition)

Ein leichtgewichtiges, browserbasiertes Tool zum Erstellen von interaktiven Multiple-Choice-Quizzes, die denen auf LEIFIphysik oder H5P ähneln.

Das Besondere: Der Editor läuft komplett im Browser (als einzelne HTML-Datei) und generiert eigenständige HTML-Quizze, die ohne Server oder Plugins in Moodle oder auf Websites laufen.

🚀 Schnellstart

Lade die Datei index.html lherunter oder klcike einach hier <a href=https://codekoch.github.io/lernquiz/>lernquiz</a>.

Öffne sie mit einem modernen Browser (Chrome, Edge, Firefox).

Erstelle deine Fragen oder lass dir ein json TEmplate mit Hilfe einer KI erstellen (optionale kann der Editor auch direkt einen Quiz per KI erstellen, wenn du einen validen API-Key eingibst.)

Klicke auf "HTML Export", um dein fertiges Quiz zu erhalten (Hier ein Beispiel: <a href=https://codekoch.github.io/lernquiz/lernquiz_-ganzrationale-funktionen.html>lernquiz_-ganzrationale-funktionen.html</a>.

🛠 Bedienungsanleitung

1. Fragen erstellen

Nutze den Button "+ Frage hinzufügen".

Gib Fragetext und Antwortmöglichkeiten ein.

Markiere die richtige(n) Antwort(en).

Wichtig: Schreibe individuelles Feedback in die Felder unter den Antworten ("Richtig, weil..." oder "Falsch, denke an..."). Das erhöht den Lerneffekt enorm.

2. KI-Generator nutzen (Optional)

Klicke oben auf "KI-Generator & Einstellungen".

Gib deinen Google Gemini API Key ein (der Key wird nur lokal im Browser genutzt und nicht gespeichert).

Gib eine Anweisung ein, z.B.: "Erstelle 5 Fragen zum Thema Ganzrationale Funktionen mit Fokus auf Symmetrie."

Der Generator erstellt Fragen inkl. Distraktoren und Feedback automatisch.

3. Speichern & Laden

Speichern: Klicke auf "Speichern", um den aktuellen Bearbeitungsstand als .json Datei zu sichern.

Laden: Ziehe eine .json Datei per "Laden" in den Editor oder nutze "JSON Text", um Code aus der Zwischenablage einzufügen.

🏫 Integration in Moodle

Da das Ergebnis eine reine HTML-Datei ist, brauchst du kein H5P-Plugin.

Erstelle im Quiz-Editor dein Quiz und klicke auf "HTML Export".

Gehe in deinen Moodle-Kurs.

Wähle "Material oder Aktivität anlegen" -> "Datei".

Lade die exportierte HTML-Datei hoch.

Optional: Stelle in den Moodle-Einstellungen der Datei bei "Darstellung" auf "In Pop-up öffnen" oder "Einbetten", für die beste User Experience.

💻 Tech Stack

Dieses Tool wurde als Single-File-Application per Google Gemini entwickelt, um maximale Portabilität zu gewährleisten.

Core: React 18 (via CDN)

Styling: Tailwind CSS (via CDN)

Transpiler: Babel Standalone (für JSX im Browser)

Math: MathJax (für LaTeX Rendering)

Icons: Lucide-React

📄 Lizenz

MIT License - Frei verwendbar für Bildungszwecke und private Projekte.
