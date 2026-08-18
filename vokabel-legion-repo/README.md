# Vokabel-Legion

Lateinvokabeltrainer für Cursus (Neu) – als Webseite über GitHub Pages erreichbar.

## Einrichtung (einmalig)

1. Dieses gesamte Verzeichnis in ein neues, öffentliches GitHub-Repository hochladen
   (z. B. per Drag & Drop auf github.com unter „Add file → Upload files“,
   oder per `git push`, falls du lieber die Kommandozeile nutzt).
2. Im Repository zu **Settings → Pages** gehen.
3. Unter „Build and deployment“ → „Source“ die Option **„GitHub Actions“** auswählen
   (nicht „Deploy from a branch“ – der mitgelieferte Workflow übernimmt das automatisch).
4. Einmal auf den Reiter **Actions** gehen und den Workflow „Deploy to GitHub Pages“
   manuell starten (oder einfach eine Kleinigkeit committen) – danach läuft er bei
   jedem Push auf `main` automatisch.
5. Nach ein bis zwei Minuten erscheint unter Settings → Pages die fertige Adresse,
   z. B. `https://DEINNAME.github.io/vokabel-legion/`.

## Updates einspielen

Einfach die neue Version der App als `index.html` ins Repository hochladen
(alte Datei überschreiben) und pushen/committen – der Workflow deployt automatisch
neu. Der Lernfortschritt selbst liegt im Browser des jeweiligen Geräts
(localStorage) und bleibt davon unberührt; bei größeren Sprüngen lohnt sich vorher
trotzdem eine Sicherung über „✍️ Eigene Vokabeln → ⬇️ Sicherung herunterladen“.
