# HL7 Parser

Ein browserbasierter Parser für HL7 v2.x Nachrichten – ohne Abhängigkeiten, als einzelne HTML-Datei.

## Features

- **Vollständiger HL7 v2.x Parser** – erkennt Feldtrennzeichen und Kodierungszeichen automatisch aus dem MSH-Segment
- **Deutsche Feldbezeichnungen** für alle Standardsegmente
- **Komponenten-Analyse** – zusammengesetzte Felder (Name, Adresse, CWE-Codes) werden mit einzelnen Komponentenbezeichnungen dargestellt
- **Wiederholungsfelder** – `~`-getrennte Werte werden einzeln angezeigt
- **Segment-Index** – Schnellnavigation per Klick
- **Beispielnachrichten** – ADT A01 (Aufnahme), ORU R01 (Laborbefund), ACK

## Unterstützte Segmente

| Segment | Beschreibung |
|---------|-------------|
| MSH | Message Header |
| MSA | Message Acknowledgment |
| ERR | Error |
| EVN | Event Type |
| PID | Patient Identification |
| PV1 / PV2 | Patient Visit |
| ORC | Common Order |
| OBR | Observation Request |
| OBX | Observation/Result |
| NTE | Notes and Comments |
| IN1 | Insurance |
| AL1 | Allergy Information |
| DG1 | Diagnosis |
| PR1 | Procedures |
| SCH | Scheduling Activity |
| QRD | Query Definition |
| Z-Segmente | Benutzerdefinierte Segmente |

## Verwendung

Datei `index.html` direkt im Browser öffnen – kein Server, keine Installation erforderlich.

```
Strg + Enter   → Nachricht parsen
```

## Lizenz

MIT
