# Work-KI – Webseite v02

Statische deutsche Produktwebseite für Work-KI von Marko Reber.

`index.html` direkt öffnen oder über GitHub Pages mit Branch `main` und Ordner `/ (root)` veröffentlichen. HTML, CSS und JavaScript benötigen keinen Build-Schritt. Alle verwendeten lokalen Pfade funktionieren auch unter `/Work-KI/`.

Die Anwendung Work-KI wird unter proprietären Lizenzbedingungen bereitgestellt; die Veröffentlichung dieser Webseite erteilt keine Open-Source-Lizenz am Programm. Siehe `lizenz.txt`. Alle Rechte an eigenen Webseiteninhalten bleiben, soweit nicht anders angegeben, bei Marko Reber.

Die Vorschau auf der Startseite ist eine Illustration mit Beispieldaten. Die Webseite enthält keinen öffentlichen Work-KI-Downloadlink. Ein Verkauf über den Microsoft Store oder eine vergleichbare Plattform ist geplant. Ein verbindlicher Termin, Preis und Store-Link werden noch ergänzt.

## Systemanforderungen für Work-KI

| Bestandteil | Mindestplanung für kleine lokale Modelle | Empfohlen für den Alltag |
| --- | --- | --- |
| Betriebssystem | Windows 10 22H2, 64 Bit (x64) | Windows 11, 64 Bit (x64) |
| Prozessor | Moderner x64-Prozessor mit 4 Kernen | 6 bis 8 Kerne oder mehr |
| Arbeitsspeicher | 16 GB RAM | 32 GB RAM oder mehr, etwa für Qwen 3.5 9B und längere Arbeiten |
| Freier SSD-Speicher | Rund 25 GB mit Ollama und Basismodellen | 50 GB frei, zusätzlich Platz für Projekte und Sicherungen |
| Grafikkarte | Chat kann auf dem Prozessor laufen und ist dann langsamer | Unterstützte GPU mit 8 bis 12 GB VRAM oder mehr, je nach Modell und Kontext |

Für Chat, Dokumente und Python-Aufträge mit Qwen 3.5 9B sind **32 GB RAM und 12 GB VRAM** ein Richtwert mit mehr Reserve. Für isolierte Python-Projektprüfungen muss Windows AppContainer verfügbar sein. Ollama und die lokalen Modelle werden separat eingerichtet.

Für lokale FLUX-Bilder sind eine **NVIDIA-GPU mit mindestens 12 GB VRAM**, **32 GB RAM** und **30 bis 60 GB zusätzlicher SSD-Speicher** für Modelle und ComfyUI einzuplanen. Der tatsächliche Bedarf hängt von Modell, Kontextlänge und Aufgaben ab.
