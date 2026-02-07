# Audit-Modul: Geschäftskontinuitätsmanagement (MaRisk AT 7.3)

## 1. Zielsetzung (Objective)
Überprüfung der Widerstandsfähigkeit (Resilience) und Wiederherstellbarkeit (Recoverability) kritischer Geschäftsaktivitäten und unterstützender IKT-Systeme, um den Geschäftsbetrieb auch in Krisensituationen aufrechtzuerhalten.



## 2. Zentrale Risiken (Key Risks)
* **Fehlende Geschäftsauswirkungsanalyse (Missing BIA):** Kritische Prozesse sind nicht identifiziert oder die Auswirkungen eines Ausfalls wurden unterschätzt.
* **Unzureichende Notfalltests (Inadequate DR Testing):** Disaster Recovery Tests sind veraltet, decken nicht alle Szenarien ab (z.B. kein RZ-Wechsel) oder die Ergebnisse wurden nicht analysiert.
* **Unklare Wiederherstellungsprioritäten (Unclear Recovery Priorities):** Im Notfall ist unklar, welche Systeme zuerst wiederhergestellt werden müssen (**RTO** - Recovery Time Objective), was zu Datenverlusten oder Betriebsausfällen führt.



## 3. Prüfungshandlungen (Audit Procedures)

### A. Überprüfung von BIA und BCM-Richtlinien (Review BIA and BCM Policies)
* **BIA-Vollständigkeit:** Prüfung, ob alle Geschäftsprozesse in der Business Impact Analysis abgedeckt sind.
* **Zielwerte:** Bewertung der Angemessenheit der Wiederherstellungsziele (RTO und **RPO** - Recovery Point Objective).
* **Policy-Aktualität:** Review der BCM-Richtlinien auf Übereinstimmung mit aktuellen regulatorischen Anforderungen.



### B. Bewertung von Notfall- und Krisentests (Assess DR and Crisis Tests)
* **Testdurchführung:** Analyse der Protokolle vergangener Tests auf erfolgreiche Durchführung und Erreichung der Zielwerte.
* **Szenarien:** Bewertung, ob realistische Katastrophenszenarien (z.B. Ransomware, Brand im Rechenzentrum) getestet wurden.
* **Lückenanalyse (Gap Analysis):** Überprüfung, ob identifizierte Mängel aus Tests behoben wurden.



### C. Bewertung des Management-Reportings (Evaluate Management Reporting on BCM)
* **Berichterstattung:** Prüfung, ob die Geschäftsleitung regelmäßig über den BCM-Status und Testergebnisse informiert wird.
* **Entscheidungsfindung:** Nachweis, dass der Vorstand Maßnahmen zur Verbesserung der Resilienz freigibt.
