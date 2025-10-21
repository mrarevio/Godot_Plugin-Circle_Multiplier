# 🌀 Circle Multiplier (Godot Plugin)

Ein vielseitiges Godot-Editor-Plugin zur automatischen Erstellung von **kreisförmigen und elliptischen Objekt-Arrays**.
Ideal für Level-Designer:innen, die schnell strukturierte oder natürliche Anordnungen von 3D-Objekten generieren möchten – direkt im Editor, mit **Live-Vorschau**, **Zufallsvariationen** und **Preset-System**.

---

## 🚀 Hauptfunktionen

### 🔹 Kreis- und Ellipsen-Generator

* Erzeugt Objekte entlang eines Kreises oder einer Ellipse
* Frei einstellbarer **Radius (X/Z)**, **Start- und Endwinkel**, **Dichte** und **Offset**
* Wahlweise **geschlossener Kreis** oder **offener Bogen**
* Unterstützt **vertikale Rotation (Y)** und **Neigung (Tilt)** für komplexe Formen

### 🔹 Live-Vorschau

* Echtzeit-Vorschau direkt im Editor
* Umschaltbare Anzeigearten: Transparent, Wireframe, Solid, Outline
* Anpassbare Vorschaufarbe, Transparenz und Linienbreite
* Option zur Anzeige von Hilfskreisen und Achsen

---

## 🎨 Erweiterte Features

* ✅ **Zufällige Rotation** (z. B. ±30°) für natürliche Anordnung
* ✅ **Zufällige Skalierung** (z. B. ±20 %) für Variation
* ✅ **Progressive Skalierung** (von Start- bis Endwert)
* ✅ **Positionsvariation** entlang des Kreises
* ✅ **Preset-System**:

  * Einstellungen speichern, laden und löschen
  * Schneller Zugriff über GUI mit Such- und Verwaltungstools
  * Speichert Presets in `res://circle_generator_presets.cfg`

---

## ⚙️ Bedienung

1. Aktiviere das Plugin unter **Project > Project Settings > Plugins**
2. Wähle ein 3D-Objekt im Editor (z. B. ein `MeshInstance3D`)
3. Öffne das Tool über das Menü **“Circle Multiplier”**
4. Konfiguriere Radius, Verteilung, Skalierung usw.
5. Nutze die **Live-Vorschau**, um das Ergebnis direkt zu sehen
6. Klicke **Erstellen**, um das Array dauerhaft in der Szene zu generieren

---

## 🧠 Technische Details

* Erstellt Kopien des ausgewählten `Node3D`-Objekts entlang eines Kreisbogens
* Automatische **Undo/Redo-Unterstützung** über den Godot-Editor
* Speicherung der Plugin-Parameter im Projektverzeichnis
* Geschrieben in **GDScript**, vollständig kompatibel mit **Godot 4.x**

---

## 💡 Einsatzmöglichkeiten

* Platzierung von Objekten in **Arena-Layouts**, **Ringen** oder **Türmen**
* Erzeugung von **Deko-Strukturen**, **Zaunanordnungen** oder **Park-Layouts**
* Kombination mit dem *Rectangle Multiplier* für modulare Szenenerstellung

---

## 📁 Installation

1. Kopiere den Plugin-Ordner nach:
   `res://addons/circle_multiplier/`
2. Aktiviere es über:
   `Projekt > Projekt Einstellungen > Plugins`

---

## 🧰 Kompatibilität

* ✅ Godot 4.2+
* 🧱 Unterstützt alle `Node3D`-basierten Objekte
* 💾 Kompatibel mit Windows, Linux und macOS

---

## 📸 Vorschau (optional)

<img width="2557" height="1388" alt="image" src="https://github.com/user-attachments/assets/a93db5b4-37fb-4a43-82bf-6e3819e8eaee" />

---

## ⚙️ Lizenz

Dieses Plugin steht unter der **MIT-Lizenz** – freie Nutzung, Änderung und Weitergabe erlaubt.

---

## ✨ Autor

**Entwickelt von: iMrArevio




