---
title: "6 Entwicklung des VS-Scrum Frameworks 3.0"
description: ""
icon: "article"
date: "2023-08-29T17:03:55+02:00"
lastmod: "2023-08-29T17:03:55+02:00"
draft: false
toc: true
weight: 106
---
Im Anschluss an die detaillierte Evaluierung des VS-Scrum Framework 2.0

richtet sich der Fokus dieses Kapitels auf die erneute Weiterentwicklung
und Optimierung des Frameworks. Das Ziel ist es, aus den
Verbesserungsvorschlägen, die im zweiten Fokusgruppeninterview genannt
wurden, im Rahmen eines weiteren Relevanz-Zyklus neue Anforderungen und
Akzeptanzkriterien zu formulieren. Dadurch soll eine Grundlage für die
Weiterentwicklung des Frameworks geschaffen werden.

## Der Relevanz-Zyklus

Der folgende Relevanz-Zyklus bildet den Ausgangspunkt für die
Entwicklung des VS-Scrum Framework 3.0. Durch diesen Zyklus wird
sichergestellt, dass die wesentlichen und bedeutsamsten
Verbesserungsvorschläge in die nächste Version des Frameworks
einfließen.

Deshalb werden nachfolgend die Anforderungen und Akzeptanzkriterien
beschrieben. Um diese Informationen zu sammeln, wurde im
Fokusgruppeninterview erneut die folgende Frage gestellt: „Welche
Verbesserungen oder Änderungen würden Sie am VS-Scrum Framework 2.0
vorschlagen?" (Folie 12, \[47\]).

**Organisations- und Projektumfeld**

Die Darstellung des VS-Scrum Frameworks sollte überarbeitet werden, um
das Organisationsumfeld und das Projektumfeld klarer voneinander
abzugrenzen. Anstatt sie als Subset zu präsentieren, sollte das
Organisationsumfeld links und das Projektumfeld rechts platziert werden,
da sie sich gegenseitig beeinflussen (vgl. ID1, Tabelle 7 im Anhang).

**User Story:**

Als Experten möchten wir eine klare Trennung zwischen Organisations- und
Projektumfeld im VS-Scrum Framework, um die Abhängigkeiten zwischen den
beiden Bereichen besser zu verstehen.

**Akzeptanzkriterien:**

- Das Organisationsumfeld ist links und das Projektumfeld rechts
  dargestellt.
- Das Projektumfeld wird nicht als Subset des Organisationsumfeld
  dargestellt.

**Änderungen an der Darstellung**

Um die neuen Rollen und Elemente des VS-Scrum Frameworks, die nicht Teil
des Standard Scrum-Prozesses sind, besser erkennen zu können, sollen sie
farblich hervorgehoben werden (vgl. ID2, Tabelle 7 im Anhang). Zudem
wurde durch die Interviewpartner angemerkt, dass die Darstellung mit
vielen gleichfarbigen Pfeilen verwirrend ist und eine klarere, farblich
differenzierte Darstellung zum leichteren Verständnis beitragen würde
(vgl. ID3, Tabelle 7 im Anhang). Des Weiteren sollte der Pfeil vom
Security Master mit der Beschriftung ‚bringt bei Bedarf ein' direkt vom
Security Backlog zum Product Backlog laufen, um zu verdeutlichen, dass
alle Anforderungen ins Product Backlog einfließen und anschließend wie
üblich priorisiert werden (vgl. ID7, Tabelle 7 im Anhang). Außerdem
wurde der Stern beim Scrum Team als irritierend wahrgenommen, weshalb er
entfernt werden sollte (vgl. ID10, Tabelle 7 im Anhang).

**User Story 1:**

Als Experten möchten wir eine farblich differenzierte Darstellung
zwischen den Standard Scrum-Elementen und den neuen Elementen des
VS-Scrum Frameworks, um die neuen Rollen und Elemente schnell
identifizieren zu können.

**Akzeptanzkriterium 1:**

Es gibt eine farbliche Unterscheidung zwischen dem Standard
Scrum-Prozess (vgl. Kapitel 2.1) und den neuen Elementen des VS-Scrum
Frameworks.

**User Story 2:**

Als Experten möchten wir, dass der Pfeil mit der Beschriftung ‚bringt
bei Bedarf ein' direkt vom Security Backlog auf den Product Backlog
zeigt, damit ersichtlich wird, dass alle Anforderungen ins Product
Backlog einfließen.

**Akzeptanzkriterium 2:**

Alle projektspezifischen Anforderungen laufen im Product Backlog
zusammen.

**User Story 3:**

Als Experten möchten wir, dass der Stern beim Symbol des Scrum Teams
entfernt wird, um Verständnisprobleme zu vermeiden.

**Akzeptanzkriterium 3:**

Der Stern beim Scrum Team ist entfernt.

**Einheitliches Backlog und S-Tags**

Des Weiteren wurde von den Experten vorgeschlagen, statt einem
zusätzlich Backlog nur ein einheitliches Product Backlog im
Projektumfeld einzuführen. In dieses Product Backlog sollen alle
Anforderungen, einschließlich der Security Anforderungen, einfließen
(vgl. ID6, Tabelle 7 im Anhang). Ergänzend dazu könnte das Refinement
bei einem einzelnen Backlog als Kreislauf um den Product Backlog
dargestellt werden, um die Kontinuität des Refinements zu betonen (vgl.
ID11, ID12, Tabelle 7 im Anhang). Zudem wurde der Wunsch geäußert, eine
Legende mit einer Erklärung des Begriffs S-Tags hinzuzufügen (vgl. ID13,
Tabelle 7 im Anhang).

**User Story 1:**

Als Experten möchten wir, dass lediglich ein Product Backlog im
Projektumfeld existiert, um eine bessere Übersichtlichkeit im Modell zu
schaffen und die Komplexität aus dem Prozess zu nehmen.

**Akzeptanzkriterium 1:**

Es gibt im Projektumfeld lediglich ein Product Backlog.

**User Story 2:**

Als Experten möchten wir eine Legende im VS-Scrum Framework, die S-Tags
erklärt, damit diese besser verständlich sind.

**Akzeptanzkriterium 2:**

Es gibt eine Legende mit einer Erklärung von S-Tags im VS-Scrum
Framework.

**User Story 3:**

Als Experten möchten wir, dass das Refinement als Kreislauf um den
Product Backlog dargestellt wird, um die Kontinuität des Prozesses zu
verdeutlichen.

**Akzeptanzkriterium 3:**

Um den Product Backlog ist ein Kreis mit Pfeil, welcher veranschaulicht,
dass es sich um einen Kreislauf handelt.

**IT-Sicherheitsanforderungen**

Darüber hinaus hat das Interview ergeben, dass die ‚allgemeinen
Anforderungen' als ‚organisationsweite IT-Sicherheitsanforderungen'
bezeichnet werden sollten. Auf diese Weise ist der IT-Sicherheitsbezug
sofort ersichtlich (vgl. ID25, ID26, Tabelle 7 im Anhang).

**User Story:**

Als Experten möchten wir, dass die allgemeinen Anforderungen im VS-Scrum
Framework als ‚organisationsweite IT-Sicherheitsanforderungen'
gekennzeichnet sind, damit unmissverständlich klar ist, dass diese
Anforderungen die IT-Sicherheit betreffen.

**Akzeptanzkriterium:**

Die Bezeichnung ‚allgemeine Anforderungen' ist durch ‚organisationsweite
IT-Sicherheitsanforderungen' ersetzt.

Nach der detaillierten Bewertung und den vorgebrachten
Verbesserungsideen zum VS-Scrum Framework 2.0 lässt sich die dritte
Forschungsfrage ‚Wie beurteilen Experten das weiterentwickelte VS-Scrum
Framework?' beantwortet. Die Analyse des Modells in Kapitel 5.3, ergänzt
durch die Optimierungsempfehlungen, liefert Einblicke in die
Expertenperspektive zum VS-Scrum Framework. Zusammenfassend kann
festgehalten werden, dass die Experten die hohe Anwendbarkeit und
Effizienz des Frameworks anerkennen.

Zudem äußerten die Experten im Interview, dass sie nach der Umsetzung
der vorgeschlagenen Optimierungen keine weiteren Verbesserungsvorschläge
für das Framework sehen \[46, S. 30\]. Daher wird das Framework im
nächsten Kapitel final entworfen.

## Der Design-Zyklus

Für die Weiterentwicklung des VS-Scrum Frameworks werden aus den im
vorherigen Kapitel definierten Anforderungen und Akzeptanzkriterien
erneut konkrete Design Entscheidungen formuliert. Diese werden in der
untenstehenden Tabelle 3 zusammengefasst.

[]{#_Ref144159736 .anchor}Tabelle 3: Design-Entscheidungen für die
Entwicklung des VS-Scrum Framework 3.0

+---------------+---+---------------------------------------------------+
| Thema         |   | Design-Entscheidung                               |
+===============+===+===================================================+
| O             |   | 1.  Das Projektumfeld wird aus dem                |
| rganisations- |   |     > Organisationumfeld geschoben.               |
| und           |   |                                                   |
| Projektumfeld |   | 2.  Das Projektumfeld wird rechts neben dem       |
|               |   |     > Organisationsumfeld positioniert.           |
+---------------+---+---------------------------------------------------+
| Änderungen an |   | 1.  Die Pfeile des Standard Scrum-Prozesses       |
| der           |   |     > werden blau eingefärbt.                     |
| Darstellung   |   |                                                   |
|               |   | 2.  Die neuen Elemente des VS-Scrum Frameworks    |
|               |   |     > werden braun eingefärbt.                    |
|               |   |                                                   |
|               |   | 3.  Der Stern beim Scrum Team wird entfernt.      |
+---------------+---+---------------------------------------------------+
| Backlog,      |   | 1.  Der Backlog mit dem Namen ‚User Storys,       |
| S-Tag und     |   |     > Features und Epics' wird entfernt.          |
| Refinement    |   |                                                   |
|               |   | 2.  Es wird eine Legende mit ‚Standard Scrum' und |
|               |   |     > ‚Neuerungen VS-Scrum' angelegt.             |
|               |   |                                                   |
|               |   | 3.  Die Felder der Legende werden mit der         |
|               |   |     > passenden korrespondierenden Farbe aus dem  |
|               |   |     > Framework eingefärbt.                       |
|               |   |                                                   |
|               |   | 4.  Es wird eine zweite kleine Tabelle neben der  |
|               |   |     > Legende mit der Überschrift ‚Erklärungen'   |
|               |   |     > angelegt.                                   |
|               |   |                                                   |
|               |   | 5.  In der zweiten Tabelle wird die Abkürzung     |
|               |   |     > ‚CISO' mit ‚Chief Information Security      |
|               |   |     > Officer' und ‚S-Tag' mit ‚Kennzeichen für   |
|               |   |     > IT-Sicherheitsanforderungen' erklärt.       |
|               |   |                                                   |
|               |   | 6.  Der Pfeil mit dem Text ‚Refinement' wird      |
|               |   |     > entfernt.                                   |
|               |   |                                                   |
|               |   | 7.  Um den Product Backlog wird ein runder Pfeil, |
|               |   |     > welcher einen Kreislauf andeutet, mit der   |
|               |   |     > Beschriftung ‚Refinement' eingefügt.        |
+---------------+---+---------------------------------------------------+
| I             |   | Die Bezeichnung ‚allgemeine Anforderungen' wird   |
| T-Sicherheits |   | durch ‚organisationsweite                         |
| anforderungen |   | IT-Sicherheitsanforderungen' ersetzt.             |
+---------------+---+---------------------------------------------------+

Die nachfolgende Abbildung 7 zeigt das VS-Scrum Framework 3.0 und somit
die für diese Arbeit finale Version des Modells.

![](media/image8.png){width="9.315972222222221in"
height="4.158333333333333in"}

[]{#_Ref144159759 .anchor}Abbildung 7: Das VS-Scrum Framework 3.0 [^5]

Nach der detaillierten Darstellung der Evaluierung und Weiterentwicklung
des VS-Scrum Frameworks folgt im nachfolgenden Kapitel eine
konsolidierende Reflexion. Es wird das gesamte Vorgehen kritisch
beleuchtet, der Mehrwert für die Praxis und Wissenschaft herausgestellt
und ein Ausblick auf zukünftige Forschungsansätze gegeben.
