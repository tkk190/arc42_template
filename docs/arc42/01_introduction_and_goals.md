# 1. Einführung und Ziele

<!---
Beschreibt die wesentlichen Anforderungen und treibenden Kräfte, die bei
der Umsetzung der Softwarearchitektur und Entwicklung des Systems
berücksichtigt werden müssen.

Dazu gehören:

-   zugrunde liegende Geschäftsziele,

-   wesentliche Aufgabenstellungen,

-   wesentliche funktionale Anforderungen,

-   Qualitätsziele für die Architektur und

-   relevante Stakeholder und deren Erwartungshaltung.
-->

## Aufgabenstellung


### **Inhalt**

<!---
Kurzbeschreibung der fachlichen Aufgabenstellung, treibenden Kräfte,
Extrakt (oder AbstraKt) der Anforderungen. Verweis auf (hoffentlich
vorliegende) Anforderungsdokumente (mit Versionsbezeichnungen und
Ablageorten).
-->

### **Motivation**

<!---
Aus Sicht der späteren Nutzung ist die Unterstützung einer fachlichen
Aufgabe oder Verbesserung der Qualität der eigentliche Beweggrund, ein
neues System zu schaffen oder ein bestehendes zu modifizieren.
-->

### **Form**

<!---
Referenzierbarkeit durch Ids ("M_x" muss | "O_x" optional)
Kurze textuelle Beschreibung, eventuell in tabellarischer Use-Case Form.
Sofern vorhanden, sollte die Aufgabenstellung Verweise auf die
entsprechenden Anforderungsdokumente enthalten.

Halten Sie diese Auszüge so knapp wie möglich und wägen Sie Lesbarkeit
und Redundanzfreiheit gegeneinander ab.

Siehe [Anforderungen und Ziele](https://docs.arc42.org/section-1/) in
der online-Dokumentation (auf Englisch!).
-->

## Qualitätsziele


### **Inhalt**

<!---
Die Top-3 bis Top-5 der Qualitätsanforderungen für die Architektur,
deren Erfüllung oder Einhaltung den maßgeblichen Stakeholdern besonders
wichtig sind. Gemeint sind hier wirklich Qualitätsziele, die nicht
unbedingt mit den Zielen des Projekts übereinstimmen. Beachten Sie den
Unterschied.

Hier ein Überblick möglicher Themen (basierend auf dem ISO 25010
Standard):

![Kategorien von
Qualitätsanforderungen](images/01_2_iso-25010-topics-DE.drawio.png)

Qualitätsmerkmale:
- Verfügbarkeit (availability)
- Änderbarkeit (modifiability) oder Wartbarkeit (maintainablity)
- Performanz (performance)
- Sicherheit (security, safety)
- Bedienbarkeit (usability)
- Testbarkeit (testability)

-->

### **Motivation**

<!---
Weil Qualitätsziele grundlegende Architekturentscheidungen oft
maßgeblich beeinflussen, sollten Sie die für Ihre Stakeholder relevanten
Qualitätsziele kennen, möglichst konkret und operationalisierbar.
-->

### **Form**

<!---
Referenzierbarkeit durch Ids ("Q_x")
Tabellarische Darstellung der Qualitätsziele mit möglichst konkreten
Szenarien, geordnet nach Prioritäten.
-->

## Stakeholder


### **Inhalt**

<!---
Expliziter Überblick über die Stakeholder des Systems -- über alle
Personen, Rollen oder Organisationen, die
-   die Architektur kennen sollten oder
-   von der Architektur überzeugt werden müssen,
-   mit der Architektur oder dem Code arbeiten (z.B. Schnittstellen
    nutzen),
-   die Dokumentation der Architektur für ihre eigene Arbeit benötigen,
-   Entscheidungen über das System und dessen Entwicklung treffen.

Der Personenkreis kann sehr großzügig gefasst werden. Wirklich alle betroffenen
Personen, z.B. auch DB-Admin, Server-Admin, Management, Jurist, Netzwerkadmin

-->

### **Motivation**

<!---
Sie sollten die Projektbeteiligten und -betroffenen kennen, sonst
erleben Sie später im Entwicklungsprozess Überraschungen. Diese
Stakeholder bestimmen unter anderem Umfang und Detaillierungsgrad der
von Ihnen zu leistenden Arbeit und Ergebnisse.
-->

### **Form**

<!---
Tabelle mit Rollen- oder Personennamen, sowie deren Erwartungshaltung
bezüglich der Architektur und deren Dokumentation.

| Rolle     | Kontakt     | Abnahmerelevanz | Erwartungshaltung           |
|-----------|-------------|-----------------|-----------------------------|
| *Rolle-1* | *Kontakt-1* | hoch            | *Erwartung-1*               |
| *Rolle-2* | *Kontakt-2* | keine           | *Erwartung-2*               |
-->
