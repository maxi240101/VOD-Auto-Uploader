# VOD-Auto-Uploader


# 🎥 VOD Auto Uploader

*[🇩🇪 Deutsch (German) below | 🇬🇧 English below]*

---

## 🇩🇪 Deutsch

### 📝 Beschreibung
Der **VOD Auto Uploader** ist ein automatisiertes Desktop-Tool für Streamer, das den kompletten Archivierungs-Prozess von Twitch zu YouTube übernimmt. Das Programm lädt das neueste Twitch-VOD herunter, generiert automatisch eine Videobeschreibung mit deinen Social-Media-Links und lädt das Video direkt auf YouTube hoch (Öffentlich & COPPA-konform). Ausgestattet mit einer modernen, dunklen Benutzeroberfläche und einem integrierten Auto-Updater.

### ✨ Features
* **1-Klick Archivierung:** Sucht, lädt und publiziert das neueste Twitch-VOD automatisch.
* **Dynamische Beschreibung:** Integrierter Link-Manager (Tab-System) für TikTok, Discord, Instagram & Co., der die YouTube-Beschreibung automatisch zusammenbaut.
* **YouTube API Integration:** Lädt Videos ohne Browser im Hintergrund hoch, setzt den Status direkt auf "Öffentlich" und nicht speziell für Kinder.
* **Traffic-Kontrolle:** Einstellbare Download- und Upload-Limits.
* **Auto-Updater:** Prüft beim Start über GitHub auf neue Versionen und aktualisiert sich im Hintergrund selbst.
* **Clean-Up:** Löscht riesige lokale Videodateien nach erfolgreichem Upload sofort wieder.

### 🚀 Schritt-für-Schritt Anleitung (Installation & Nutzung)

**Vorbereitung:**
Du benötigst Zugangsdaten für die Twitch API (Client ID & Secret) sowie eine `client_secret.json` aus der Google Cloud Console für die YouTube Data API v3.

1. **Download:** Gehe rechts auf dieser GitHub-Seite zu **"Releases"** und lade die neueste `.zip`-Datei (z. B. `VOD.Auto.Uploader.Beta.0.3.0.zip`) herunter.
2. **Entpacken:** Entpacke den kompletten Ordner auf deinen PC. Belasse den `_internal`-Ordner immer exakt neben der `.exe`.
3. **API-Schlüssel hinzufügen:** Kopiere deine `client_secret.json` (für YouTube) in denselben Ordner neben die `.exe`.
4. **Starten:** Führe die `VOD_Auto_Uploader.exe` aus.
5. **Links einrichten:** Wechsle oben in den Tab **"Links"** und füge alle deine Social-Media-Links ein (diese werden später in die Videobeschreibung gepackt).
6. **YouTube verbinden:** Gehe zurück auf **"Start"** und klicke auf den roten Button "Mit YouTube verbinden". Melde dich im Browser an.
7. **Twitch Daten eintragen:** Gib deine Twitch API-Daten ein und klicke auf "Alle Daten speichern".
8. **Upload:** Klicke auf "Neuestes VOD suchen". Sobald es gefunden wurde, klicke auf den grünen Button **"Download & Upload starten"**. Zurücklehnen und das Programm arbeiten lassen!

---
---

## 🇬🇧 English

### 📝 Description
The **VOD Auto Uploader** is an automated desktop tool for streamers that handles the entire archiving process from Twitch to YouTube. The program downloads the latest Twitch VOD, automatically generates a video description using your custom social media links, and directly uploads the video to YouTube (Public & COPPA compliant). It features a modern dark-mode GUI and a built-in auto-updater.

### ✨ Features
* **1-Click Archiving:** Automatically finds, downloads, and publishes the latest Twitch VOD.
* **Dynamic Description:** Built-in link manager (tab system) for TikTok, Discord, Instagram, etc., which auto-generates the YouTube description.
* **YouTube API Integration:** Uploads videos in the background without a browser, setting the status to "Public" and "Not made for kids".
* **Traffic Control:** Adjustable download and upload speed limits.
* **Auto-Updater:** Checks for new versions via GitHub on startup and silently updates itself in the background.
* **Clean-Up:** Automatically deletes the massive local video files immediately after a successful upload.

### 🚀 Step-by-Step Guide (Installation & Usage)

**Prerequisites:**
You will need Twitch API credentials (Client ID & Secret) and a `client_secret.json` from the Google Cloud Console for the YouTube Data API v3.

1. **Download:** Go to **"Releases"** on the right side of this GitHub page and download the latest `.zip` file (e.g. `VOD.Auto.Uploader.Beta.0.3.0.zip`).
2. **Extract:** Extract the complete folder to your PC. Always keep the `_internal` folder exactly next to the `.exe`.
3. **Add API Key:** Copy your `client_secret.json` (for YouTube) into the same folder, right next to the `.exe`.
4. **Launch:** Run the `VOD_Auto_Uploader.exe`.
5. **Set up Links:** Switch to the **"Links"** tab at the top and add your social media links (these will be injected into your video descriptions).
6. **Connect YouTube:** Go back to the **"Start"** tab and click the red "Connect to YouTube" button. Log in via your browser.
7. **Enter Twitch Data:** Enter your Twitch API credentials and click "Save all data".
8. **Upload:** Click "Search latest VOD". Once found, click the green **"Start Download & Upload"** button. Lean back and let the tool do the work!
