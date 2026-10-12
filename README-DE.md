# Kniffelmeister Android

Diese Android-App zeigt https://kniffelmeister.de/ in einer WebView.

## APK erstellen
Das GitHub-Actions-Workflow unter `.github/workflows/build-apk.yml` startet automatisch nach einem Push auf `main`. Du kannst ihn auch manuell unter **Actions → Build Android APK → Run workflow** starten.

Nach erfolgreichem Build findest du die Datei als Artefakt `kniffelmeister-debug-apk` im jeweiligen Workflow-Lauf. Lade das Artefakt herunter und entpacke es, um `app-debug.apk` zu erhalten.

Hinweis: Dies ist eine einfache WebView-App. Sie lädt die bestehende Website und verändert keine Inhalte auf der Website.
