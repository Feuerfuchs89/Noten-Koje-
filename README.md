<p align="center"><img src="icon-512.png" width="128" alt="Icon"></p>

# ❄️ Noten-Editor

Browser-Editor für kleine Ensemble-Stücke, ursprünglich für *O Snowflakes how Gently / Schneeflöckchen* (Violine I/II, Viola, Cello). Eine einzige HTML-Datei, keine Installation, kein Server. Läuft auch offline (Service Worker) und lässt sich auf dem Handy als App installieren.

![Screenshot](docs/screenshot.png)

## Funktionen
- **Bearbeiten:** Tonhöhe (Stufe, ♯/♭/♮, Oktave), Notenwert (32stel bis Ganze, punktiert), Pausen aller Werte, Bögen, Noten einfügen/löschen, Liedtext (2 Strophen)
- **Eingabemodus:** Notenwert wählen, Ton tippen (C–H, auch per Tastatur), Cursor springt weiter, Takt wird automatisch aufgefüllt und am Ende automatisch angehängt
- **Control-Panel** mit Tabs (Note, Takt, Stimme, Wiedergabe, Ansicht, Datei): Taktart, Tonart, Tempo, Schlüssel, Name, Instrument, Lautstärke, Stimmen hinzufügen/entfernen, Metronom, Zoom
- **Hell/Dunkel/Automatisch**
- **Rückgängig/Wiederholen** (Strg+Z / Strg+Y)
- **Takte** am Ende anhängen (beliebig viele), einfügen, duplizieren, löschen, Stimme um Oktave oder Halbton transponieren
- **Import** und **Export** von MusicXML (alle Stimmen, Einzelstimme oder Klavier-Auszug)
- **Instrument pro Stimme** (Violine, Bratsche, Cello, Klavier, Flöte, Oboe, Blockflöte, Fagott, Gitarre, Harfe, Orgel), wird als MIDI-Programm exportiert
- **Abspielen** mit Web Audio (Tempo, Stimmen an/aus, ab gewählter Note, Hall); Antippen einer Note spielt sie an
- **Spuren ein-/ausblenden:** Nur die gewählten Stimmen werden angezeigt und gespielt; ein Cursor folgt der Auswahl bzw. der Wiedergabe, die Ansicht scrollt mit
- Zeilenumbruch nach wählbarer Taktzahl, automatische Taktprüfung, Autosave im Browser

## Online stellen (GitHub Pages)
*Settings → Pages → Branch `main`, Ordner `/ (root)`*. Danach ist die App unter `https://<name>.github.io/<repo>/` erreichbar.

## Grenzen
- Import: nur unkomprimiertes `.xml`/`.musicxml` (kein `.mxl`), je System nur die erste Stimme, keine Triolen
- Klang ist ein einfacher Synthesizer, keine echten Instrumentenaufnahmen

## Lizenz
MIT
