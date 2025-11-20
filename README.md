# Humidor Controller  
**Intelligenter Klima-Controller für Zigarrenhumidore**

Der **Humidor Controller** ist ein moderner, vollständig automatisierter Regler für Zigarrenhumidore.  
Er misst und steuert zuverlässig Temperatur und Luftfeuchtigkeit und bietet ein intuitives Farbdisplay sowie eine einfache WLAN- und Home-Assistant-Integration.

---

## 🚀 Funktionen

### 🌡 Präzise Klimaüberwachung
- Echtzeitmessung von **Temperatur** und **Luftfeuchtigkeit**
- Hochwertige Sensoren für maximale Genauigkeit
- Übersichtliche Anzeige auf einem 160×128-Farbdisplay (Querformat)

### 💧 Automatische Befeuchtungssteuerung
- Reguliert die Luftfeuchtigkeit selbstständig
- Schutz vor Überfeuchtung und Austrocknung
- Unterstützt aktive und passive Befeuchtersysteme
- Optional: Erweiterung über PCF8574-Portexpander

### 📶 WLAN & Netzwerkfunktionen
- Einfaches Setup über QR-Code am Display
- Netzwerkwechsel ohne Neuinstallation möglich
- Automatischer Fallback-Modus bei Verbindungsproblemen

### 🔄 OTA Firmware Updates
- Einfache Updates direkt über das Gerät  
- Automatische Prüfung auf neue Releases  
- Anzeige von Changelog & Versionsdetails  
- Auswahl: **Update jetzt** oder **später**

### 🏠 Home Assistant Integration
- Direkte Einbindung in Home Assistant
- Sensorwerte und Steuerfunktionen als Entitäten sichtbar
- Keine Neukompilierung erforderlich

### 🧩 Benutzerfreundliches Display-Menü
- Übersichtliche LVGL-Oberfläche  
- Seiten für Status, Klima, Befeuchtung, WLAN, Einstellungen und Updates  
- Verständlich auch für Endkunden ohne technisches Wissen  

---

## 📦 Firmware

Die aktuelle Firmware steht hier auf GitHub als **fertige .bin Datei** zur Verfügung.  
Sie kann per OTA direkt aktualisiert werden, ohne dass ein Computer notwendig ist.

---

## 🧱 Unterstützte Hardware

- **ESP32 Controller**
- **160×128 TFT Farbdisplay** (SPI)
- Temperatur-/Feuchtigkeitssensor (z. B. SHT, AHT, BME-Serie)
- Optional:  
  - PCF8574 Portexpander  
  - Lüftersteuerung  
  - LED/Relais-Module  
  - Zusätzliche interne/externe Sensoren  

Gehäusevarianten (Holz / 3D-Druck) sind kompatibel.

---

## 🔧 Nutzung

1. Gerät anschließen und einschalten  
2. Ersteinrichtung starten  
   - Am Display erscheint ein QR-Code zur WLAN-Verbindung  
3. Humidor Controller mit deinem Netzwerk verbinden  
4. Optional: Home Assistant erkennt das Gerät automatisch  
5. Firmware-Updates bequem direkt am Gerät durchführen  

Keine Programmierung, kein Kompilieren, keine Zusatzsoftware notwendig.

---

## 🧪 Entwicklungsstand

Der Humidor Controller wird laufend verbessert.  
Geplante Erweiterungen:
- Mehrsprachige Benutzeroberfläche  
- Erweiterte Lüfterprofile  
- Zusätzliche Sensormodule  
- Verbesserte Update-Ansichten  

---

## 📜 Lizenz

Die Firmware steht Endkunden als fertig kompilierte `.bin` Datei zur Verfügung.  
Nutzung des Geräts ist ohne technische Kenntnisse möglich.

---

## ❤️ Dankeschön

Vielen Dank an alle Tester, Unterstützer und Zigarrenliebhaber, die zur Weiterentwicklung des Projekts beitragen.


