# HL7 Parser

Ein browserbasierter Parser für HL7 v2.x Nachrichten – ohne Abhängigkeiten, als einzelne HTML-Datei.

## Features

- **Vollständiger HL7 v2.x Parser** – erkennt Feldtrennzeichen und Kodierungszeichen automatisch aus dem MSH-Segment
- **MLLP-Framing** wird automatisch erkannt und entfernt
- **Deutsche Feldbezeichnungen** für alle Standardsegmente
- **Komponenten-Analyse** – zusammengesetzte Felder (Name, Adresse, CWE-Codes) werden mit einzelnen Komponentenbezeichnungen dargestellt
- **Wiederholungsfelder** – `~`-getrennte Werte werden einzeln angezeigt
- **Feldsuche** – Live-Filterung über alle Segmente und Feldwerte
- **Kopieren** – Feldwerte per Klick in die Zwischenablage kopieren
- **Rohdaten-Ansicht** – jedes Segment kann als Rohzeile eingeblendet werden
- **Segment-Index** – Schnellnavigation per Klick, mit Segmentzähler
- **Alle auf-/zuklappen** – Segmentdarstellung auf Knopfdruck ein- oder ausblenden
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
| NK1 | Next of Kin / Associated Parties |
| MRG | Merge Patient Information |
| GT1 | Guarantor |
| ROL | Role |
| ACC | Accident |
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
