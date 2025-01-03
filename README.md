# API Tester

Ein einfacher API-Tester, mit dem du HTTP-Anfragen (GET, POST, PUT, DELETE, PATCH) an beliebige Endpunkte senden und die Antwort in Echtzeit anzeigen kannst. Das Tool bietet zudem Funktionen zur Authentifizierung, Dateiupload und Header- sowie Body-Verwaltung.

## Features

- **HTTP-Methoden auswählen**: Sende GET, POST, PUT, DELETE oder PATCH-Anfragen.
- **Benutzerdefinierte Header**: Füge benutzerdefinierte Header im JSON-Format hinzu.
- **Request Body**: Definiere den Body für POST/PUT/PATCH-Anfragen.
- **Dateiupload für Authentifizierung**: Lade eine Datei hoch, um eine Authentifizierung zu ermöglichen.
- **Benutzername und API-Key**: Optionales Textfeld für Benutzername und API-Key zur Authentifizierung.
- **Responsiv**: Funktioniert auf Desktop und mobilen Geräten.

## Verwendung

1. **HTTP-Methode auswählen**: Wähle eine der verfügbaren HTTP-Methoden (GET, POST, PUT, DELETE, PATCH) aus der Dropdown-Liste aus.
2. **API-URL angeben**: Gib die URL des gewünschten API-Endpunkts in das Textfeld ein.
3. **Header hinzufügen**: Gib benutzerdefinierte Header im JSON-Format ein. Beispiel:
   ```json
   {
     "Content-Type": "application/json"
   }
   ```
4. **Request Body(Optional)**: Gib den Body deiner Anfrage (z. B. JSON) für POST/PUT/PATCH-Anfragen ein.
5. **Dateiupload für Authentifizierung**: Wähle eine Datei aus, um sie zu senden (optional, je nach API-Anforderung).
6. **Benutzername und API-Key**: Gib optional einen Benutzernamen und API-Key für die Authentifizierung ein.

Drücke den **"Send Request"-Button**, um die Anfrage abzusenden. Die Antwort wird im unteren Bereich angezeigt, einschließlich:

- **Statuscode** (grün oder rot, je nach Erfolg oder Fehler)
- **Response-Headers**: Die Header der Antwort im JSON-Format
- **Response-Body**: Der Inhalt der Antwort im JSON-Format (bei erfolgreichem Abruf)

