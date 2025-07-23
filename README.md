# Open-Pen## 🧠 Projekt: Open-Pen  
### Ein modularer Eingabe-Proxy für Maus-gestützte Stylus-Interaktion

**Open-Pen** ist ein freies, experimentelles Eingabe-Framework für Linux, das die Maus als grundlegende Positionsquelle nutzt und über ein **virtuelles Eingabegerät** ins System weitergibt. Ziel ist es, eine universell kompatible und preisgünstige Alternative zu klassischen Grafiktabletts zu schaffen – unabhängig von proprietärer Hardware.

---

## 🎯 Projektziel

- 🖱️ **Zwischenstück bauen**: Ein Programm, das Mausbewegungen exklusiv abfängt und via `uinput` als virtuelles Eingabegerät zurückgibt.
- ⚡ **Niedrige Latenz, hohe Kompatibilität**: Das System funktioniert transparent – für das OS sieht es aus wie ein ganz normales Eingabegerät.
- 🧩 **Modularer Aufbau**: Die Quelle der Bewegungen (Touchpad, Maus, Digitizer) ist austauschbar – ebenso wie die dynamischen Zusatzdaten (z. B. Druck, Neigung via BLE).
- 🛠️ **Erweiterbar zum Smart Stylus-System**: Die Basis bildet ein Maus-Proxy – später kann es zu einem vollständigen Stylus-Eingabesystem ausgebaut werden.

---

## 💡 Warum Open-Pen?

- Keine Abhängigkeit von teuren EMR-Technologien
- Günstige Hardware wie ESP32 nutzbar
- Freie Software, kein SDK-Zwang
- Ideal für Maker, Künstler:innen, Bildung, Forschung und Open-Hardware-Fans

---

## 🔧 Aktueller Status

- [x] C-Code für Maus-Proxy entwickelt  
- [x] Virtuelles Eingabegerät via `uinput` erzeugt  
- [ ] BLE-Stiftintegration geplant  
- [ ] Event-Mapping und Druckmodulation in Vorbereitung  
- [ ] README und Visualisierung folgen
