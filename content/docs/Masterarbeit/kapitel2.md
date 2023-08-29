---
title: "2 Wissensbasis"
description: ""
icon: "article"
date: "2023-08-29T17:00:18+02:00"
lastmod: "2023-08-29T17:00:18+02:00"
draft: false
toc: true
weight: 102
---
Im Rahmen des DSR-Frameworks liefert die Wissensbasis die Rohdaten, mit
welchen die Forschung durchgeführt werden kann \[7, S. 80\]. „Prior
\[Information System\] research and results from reference disciplines
provide foundational theories, frameworks, instruments, constructs,
models, methods, and instantiations used in the develop/build phase of a
research study" \[7, S. 80\]. Das Kapitel 2 befasst sich aufgrund dessen
mit der bestehenden Literatur. In Anbetracht der Zielsetzung dieser
Arbeit handelt es sich dabei um die Themen Scrum als agile Methode,
IT-Sicherheit in der Softwareentwicklung und abschließend die
Vorstellung des VS-Scrum Frameworks.

## Scrum als agile Methode

Im Bereich der Softwareentwicklung haben sich verschiedene Methoden
etabliert (vgl. Abbildung 2). Mit der Veröffentlichung des agilen
Manifests im Jahr 2001 ist das Interesse an agilen
Softwareentwicklungsmethoden stark angestiegen \[15, S. 1215\].
Mittlerweile gehört Scrum zu den weltweit am meisten praktizierten
Softwareentwicklungsmethoden (vgl. Abbildung 2).

![Ein Bild, das Screenshot, Reihe, Design enthält. Automatisch
generierte Beschreibung](media/image3.png){width="5.880952537182852in"
height="2.1015912073490814in"}

[]{#_Ref131239965 .anchor}Abbildung 2: Weltweit praktizierte Methoden
der Softwareentwicklung 2022 \[16\]

Der Name Scrum leitet sich aus einer im Rugby verwendeten Strategie ab,
bei der es darum geht, das Spiel nach kleineren Regelverstößen neu zu
starten \[17, S. 1\]. Außerhalb dieser Sportart wurde die
Begrifflichkeit erstmals von Ikujiro Nonaka und Hirotaka Takeuchi im
Jahr 1987 verwendet \[17, S. 1\].

Die Grundprinzipien von Scrum basieren auf dem agilen Manifest, welches
die folgenden Werte definiert \[18\]:

- **Individuen und Interaktionen** mehr als Prozesse und Werkzeuge
- **Funktionierende Software** mehr als umfassende Dokumentation
- **Zusammenarbeit mit dem Kunden** mehr als Vertragsverhandlung
- **Reagieren auf Veränderung** mehr als das Befolgen eines Plans

Scrum beinhaltet zudem verschiedene Rollen und Events, die nachfolgend
erläutert werden \[17, S. 9 f.\].

### Bestandteile des Scrum-Prozesses

Im Scrum-Verfahren werden spezifische Rollen, Artefakte und Ereignisse
definiert. Abbildung 3 illustriert den charakteristischen Ablauf eines
Scrum-Prozesses.

![Ein Bild, das Screenshot, Grafiken, Grafikdesign, Design enthält.
Automatisch generierte
Beschreibung](media/image4.png){width="5.838073053368329in"
height="2.8208825459317586in"}

[]{#_Ref144157516 .anchor}Abbildung 3: Vereinfachtes Scrum Framework
nach Rubin \[19, S. 17\]

Nachfolgend werden im ersten Schritt die Rollen im Framework dargelegt.

**Product Owner**: Dieser ist verantwortlich für die Entwicklung des
Produktziels, die Priorisierung der Anforderungen und die Kommunikation
mit dem Auftraggeber. Zudem erstellt und pflegt er das Product Backlog
\[20, S. 6\].

**Scrum Master:** Er fungiert als Coach für das Team, hilft bei der
Beseitigung von Hindernissen und stellt sicher, dass die
Scrum-Prinzipien korrekt angewendet werden \[20, S. 7\].

**Developer:** Darunter wird ein Team von Fachleuten verstanden, das für
die Planung, Entwicklung und Lieferung des Produkts verantwortlich ist
\[20, S. 6\].

Scrum organisiert die Softwareentwicklung in Sprints \[20, S. 11\],
\[21, S. 258\]. Jeder Sprint ist ein festgelegter Zeitraum von bis zu
einem Monat, in dem vorher definierte Aufgaben abgearbeitet werden
sollen \[19, S. 20\].

**Sprint Planning:** Hier wird entschieden, welche Aufgaben im kommenden
Sprint bearbeitet werden. Dies basiert auf dem Product Backlog und dem
Input des Product Owners \[19, S. 247 f.\].

**Daily Scrum:** Ein tägliches bis maximal 15-minütiges Meeting, in dem
das Entwicklungsteam den Fortschritt bespricht und den Plan für den
nächsten Tag festlegt \[19, S. 24\]**.**

**Sprint Review:** Am Ende des Sprints werden die Ergebnisse den
Stakeholdern präsentiert sowie der Fortschritt in Richtung des
Produktziels diskutiert \[19, S. 26 f.\]**.**

**Sprint Retrospektive:** Das Team reflektiert zum Abschluss eines
Sprints, was gut lief und wo Verbesserungspotential besteht. Der Gedanke
dabei ist, die Arbeitsweise kontinuierlich zu optimieren \[19, S. 27
f.\]**.**

Alle diese Events zielen darauf ab, Transparenz zu schaffen, die
Kommunikation zu fördern und sicherzustellen, dass das Team auf das
Produktziel hinarbeitet \[19, S. 35\], \[22, S. 312 f.\]**.**

### Vorteile und Herausforderungen von Scrum

Scrum bietet eine Vielzahl von Vorteilen, die sowohl für die Kunden als
auch für die Projektmanager von Bedeutung sind. Scrum erhöht die
Kundenzufriedenheit, indem es ermöglicht, schnell auf Anfragen zu
reagieren und die Durchlaufzeit zu optimieren \[23, S. 195\]. Dies führt
zu einer höheren Produktqualität und einer höheren Akzeptanz von
Änderungen während des Entwicklungsprozesses \[23, S. 195\].

Ein weiterer Vorteil von Scrum ist die Fähigkeit, präzise Schätzungen
mit weniger Zeitaufwand zu erstellen \[21, S. 287\], \[23, S. 195\].
Dies gibt den Teams mehr Kontrolle über den Zeitplan des Projekts.
Besonders in Umgebungen mit sich ständig ändernden Anforderungen wird
die Stärke von Scrum deutlich. Es ermöglicht eine schnelle Anpassung an
Änderungen und hilft dabei den Zeitplan einzuhalten \[21, S. 287\],
\[23, S. 195\].

Jeder Sprint in Scrum hat eine feste Dauer (vgl. Kapitel 2.1.1). Anstatt
den gesamten Projektumfang auf einmal zu schätzen, wird beim agilen
Vorgehen Scrum das wichtigste Feature zuerst geschätzt. Während der
Zeitplan und der Sprint konstant bleiben, kann der Umfang angepasst
werden, um sicherzustellen, dass die Veröffentlichungstermine
eingehalten werden \[21, S. 286 f.\], \[23, S. 195\].

Allerdings bringt Scrum auch einige Herausforderungen mit sich. Ein
zentrales Merkmal von Scrum ist die reduzierte Dokumentation \[19, S.
225\], \[23, S. 195\]. Während dies in manchen Fällen als Vorteil
angesehen werden kann \[19, S. 57 f.\], kann es in anderen zu
Kommunikationslücken oder Missverständnissen führen \[24, S. 3\].

Eine zusätzliche Herausforderung entsteht, wenn Entwicklungen für
externe Partner durchgeführt werden. In solchen Fällen muss der externe
Partner sehr eng in das Projekt eingebunden sein und beispielsweise
monatlich für Testzwecke zur Verfügung stehen \[19, S. 440 f.\].

Dikert et al. \[25\] haben in ihrer Studie im Jahr 2016 weitere
Herausforderungen identifizieren können. Einige Teams stoßen bei einer
Implementierung von Scrum auf Widerstand gegen Veränderungen, sowohl aus
der Perspektive des Managements als auch aus derjenigen des Teams selbst
\[25, S. 92 ff.\], \[26, S. 115\].

Ein weiteres Problem ist die unzureichende Investition in wichtige
Ressourcen, wie zum Beispiel Coaching und Schulung hinsichtlich der
Scrum-Methode \[25, S. 96\], \[26, S. 115\]. Ohne die richtige Schulung
und Unterstützung können Teams Schwierigkeiten haben, die
Scrum-Prinzipien korrekt zu implementieren und zu befolgen \[25, S.
96\]. Dies kann schlussendlich zu Missverständnissen über das Konzept
und seine Anwendung führen.

Koordinationsprobleme sind ebenfalls eine häufige Herausforderung,
insbesondere für Teams, die global verteilt sind \[25, S. 59 ff.\]. Die
Distanz kann zu Kommunikationsverzögerungen und Inkonsistenzen in der
Arbeitsweise führen \[25, S. 97\]. Organisatorische Einschränkungen, wie
Bürokratie, können ebenfalls den reibungslosen Ablauf von
Scrum-Projekten behindern \[25, S. 98\].

Zusätzlich können technische Herausforderungen, wie zum Beispiel die
Schätzung des Arbeitsaufwands sowie die Abstimmung von kurz- und
langfristigen Planungen, auftreten. Hinzu kommt die Qualitätssicherung,
bei welcher fehlende automatisierte Tests zu Problemen führen können
\[25, S. 97 f.\].

Zusammenfassend lässt sich festhalten, dass Scrum trotz seiner
zahlreichen Vorteile auch mit Herausforderungen verbunden ist. Eine
kontinuierliche Schulung und Weiterbildung der Mitarbeitenden,
einschließlich des Managements, ist unerlässlich. Darüber hinaus ist ein
klares Bekenntnis des Managements zu Scrum entscheidend für dessen
Erfolg. Im nächsten Kapitel wird im Kontext der Wissensbasis dargelegt,
wie die IT-Sicherheit in der Softwareentwicklung gestaltet ist.

## IT-Sicherheit in der Softwareentwicklung

Die IT-Sicherheit in der Softwareentwicklung hat in den letzten Jahren
erheblich an Bedeutung gewonnen, insbesondere vor dem Hintergrund der
zunehmenden Digitalisierung und Vernetzung von Systemen. Die Abbildung 4
zeigt auf, dass die Ausgaben für die IT-Sicherheit in Deutschland
zwischen 2017 und 2021 stetig zugenommen haben. Darüber hinaus wird
prognostiziert, dass die Ausgaben kontinuierlich weiter steigen.

![Ein Bild, das Screenshot, Reihe enthält. Automatisch generierte
Beschreibung](media/image5.png){width="5.852317366579178in"
height="2.622735126859143in"}

[]{#_Ref144157554 .anchor}Abbildung 4: Ausgaben für IT-Sicherheit in
Deutschland in den Jahren 2017 bis 2021 und Prognose bis 2025 \[27\]

Eine wesentliche Hilfestellung für die sichere Softwareentwicklung
bietet in Deutschland das BSI. Mit der BSI-Grundschutz-Methodik bietet
das BSI Hilfestellungen, um Organisationen bei der Etablierung eines
angemessenen Informationssicherheitsniveaus zu unterstützen \[28, S.
8\]. Es wird ein systematischer Weg aufgezeigt, wie potenzielle
IT-Sicherheitsrisiken identifiziert und geeignete Sicherheitsmaßnahmen
implementiert werden können \[28, S. 11\].

Dabei werden sowohl organisatorische als auch technische Aspekte
berücksichtigt \[28, S. 31\]. Die Methodik basiert auf einem Katalog von
Standards und Empfehlungen, die in verschiedenen Vorgehensweisen
(Standard-, Basis- und Kernabsicherung) angewendet werden können \[28,
S. 7\]. Der Katalog selbst besteht aus verschiedenen Bausteinen. „Diese
\[\] sind entsprechend ihrem jeweiligen Fokus in prozess- und
systemorientierte Bausteine aufgeteilt und nach zusammengehörigen Themen
in ein Schichtenmodell einsortiert" \[28, S. 13\]. Besonders relevant
ist für die Softwareentwicklung der Baustein ‚CON.8:
Software-Entwicklung', der die Anforderungen an eine sichere
Softwareentwicklung beschreibt \[29, S. 2\].

Ein zentraler Aspekt stellt dabei die Qualitätssicherung dar, denn ohne
sie können Fehler in der Software übersehen werden, was wiederum zu
Sicherheitslücken führt \[29, S. 3\]. Des Weiteren kann eine
unzureichende Dokumentation die Wartung und Anpassung der Software
erschweren und zu Betriebsstörungen führen \[29, S. 3\]. Die
IT-Sicherheit der Entwicklungsumgebung ist ebenfalls entscheidend, denn
wenn diese nicht ausreichend geschützt ist, kann die Software
manipuliert werden, was wenn überhaupt, nur schwer nachzuvollziehen ist
\[29, S. 2 f.\].

Außerdem wird im Baustein beschrieben, dass Software-Konzeptionsfehler,
die oft historisch bedingt sind, erhebliche Sicherheitslücken
verursachen und die Wartung der Software erschweren können \[29, S. 3
f.\]. Bei unzureichendem Test- und Freigabeverfahren besteht das Risiko,
dass kritische Fehler in der Software übersehen werden \[29, S. 4\].

Zudem kann das Testen der Software mit echten Produktivdaten die
Vertraulichkeit und Integrität dieser Daten gefährden, weshalb während
des gesamten Testprozesses der Schutz und die Sicherheit dieser Daten an
erster Stelle stehen sollte \[29, S. 4\].

Eine Basis-Anforderung des BSI ist die ‚CON.8.A2 Auswahl eines
Vorgehensmodells' \[29, S. 5\]:

> „Ein geeignetes Vorgehensmodell zur Software-Entwicklung MUSS
> festgelegt werden. Anhand des gewählten Vorgehensmodells MUSS ein
> Ablaufplan für die Software-Entwicklung erstellt werden. Die
> Sicherheitsanforderungen des Auftraggebers an die Vorgehensweise
> MÜSSEN im Vorgehensmodell integriert werden." - \[29, S. 5\]

Dies verdeutlicht, welche Relevanz das BSI einem passendem
Vorgehensmodell für die Softwareentwicklung zuschreibt. Ein Modell,
welches sich insbesondere für die Integration von
IT-Sicherheitsanforderungen eignet, ist das VS-Scrum Framework, welches
im nächsten Kapitel detailliert vorgestellt wird.

## Das VS-Scrum Framework[^2]

In diesem Kapitel wird das VS-Scrum Framework vorgestellt. Dieses
basiert auf bereits existierenden Vorgehensmodellen, welche
Anforderungen der IT-Sicherheit in einen Scrum Prozess implementieren.
Das VS-Scrum Framework konsolidiert diese Anforderungen und wurde vom
Autor der vorliegenden Arbeit im Rahmen einer früheren Projektarbeit als
ein ganzheitliches Artefakt gestaltet \[6\].

Zunächst wird ein Überblick über bestehende Konzepte aus der Literatur
gegeben, die sich mit der Integration von IT-Sicherheitsanforderungen in
Scrum-Verfahren befassen. Es wird erläutert, welche dieser Konzepte in
das VS-Scrum Framework übernommen wurden. Anschließend werden die neu
zum Modell hinzugefügten Rollen und Ereignisse ausführlich beschrieben.

### Umsetzungskonzepte

Die bestehende Literatur zeigt verschiedene Möglichkeiten für eine
sichere Entwicklung in Scrum Projekten auf \[6, S. 11\]. In den
einzelnen Modellen werden diverse Umsetzungskonzepte genutzt, die im
nachfolgenden vorgestellt werden.

Neben dem herkömmlichen Backlog, wie in Kapitel 2.1.1 beschrieben,
schlagen einige Experten die Einführung eines speziellen ‚Security
Backlogs' vor. In diesem werden alle User-Storys gesammelt, die sich
hauptsächlich auf die Steigerung der IT-Sicherheit konzentrieren \[30,
S. 416 f.\]\[6, S. 11\]. Der Grund für die Einführung eines separaten
Backlogs liegt darin, dass Auftraggeber in der Regel nicht ausreichend
mit Sicherheitsrisiken vertraut sind. Azham et al. betonen, dass durch
die klare Trennung der Backlogs die agile Methodik nicht beeinträchtigt
wird, sondern vielmehr eine klarere Struktur und Priorisierung von
IT-Sicherheitsanforderungen ermöglicht \[30, S. 416\].

Um sicherzustellen, dass der spezielle Security Backlog effektiv
verwaltet und überwacht wird, wird die Rolle des ‚Security Masters'
eingeführt. Der Security Master hat eine zentrale Funktion innerhalb des
Scrum-Teams: Er ist nicht nur für die Identifizierung von User-Storys
zuständig, die potenzielle Sicherheitsrisiken bergen, sondern auch für
die umfassende Dokumentation dieser Risiken \[30, S. 416\]. Darüber
hinaus obliegt ihm die Aufgabe, Penetrationstests zu planen,
durchzuführen und deren Ergebnisse entsprechend zu dokumentieren sowie
mit dem Team zu teilen \[30, S. 416\]. Durch diese spezialisierte Rolle
wird gewährleistet, dass IT-Sicherheitsaspekte im Entwicklungsprozess
stets Priorität haben und systematisch angegangen werden.

Einige Modelle, wie Secure Scrum \[31\], US-Scrum \[32\] und weitere
Entwicklungen, die auf umfangreichen Literaturrecherchen basieren, wie
beispielsweise diejenigen von Ghani et al. \[4\], Tomanek und Klima
\[33\] sowie Wichers \[34\], verfolgen einen differenzierten Ansatz zur
Sicherheitsbewertung. In diesen Modellen wird besonderes Augenmerk auf
die Bewertung des potenziellen Schadens gelegt, welcher entstehen
könnte, wenn die in einer User Story verarbeiteten Daten kompromittiert
werden. Um diese kritischen User Storys hervorzuheben, werden sie mit
speziellen Kennzeichnungen, den sogenannten S-Marks, versehen. Diese
S-Marks verweisen auf ein detailliertes S-Tag. Das S-Tag charakterisiert
das spezifische IT-Sicherheitsrisiko und bietet zudem konkrete
Lösungsansätze. Dies kann beispielsweise die Empfehlung zur Anwendung
bestimmter etablierter IT-Sicherheitsverfahren oder bewährter Best
Practices beinhalten \[31, S. 15\], \[35, S. 2\]. Dieser Ansatz stellt
sicher, dass die IT-Sicherheitsrisiken nicht nur identifiziert, sondern
auch systematisch und nach bewährten Methoden angegangen werden.

Eine weitere entscheidende Rolle zur Verbesserung der IT-Sicherheit in
Scrum Projekten ist die Durchführung von Penetrationstests. Dabei werden
sowohl manuelle als auch automatische Tests im Rahmen des Continuous
Integration beziehungsweise Continuous Delivery genutzt \[4\], \[32\],
\[33\], \[36\]--\[38\]. Die Integration von Penetrationstests in diesen
Prozess ermöglicht es, IT-Sicherheitslücken kontinuierlich zu überwachen
und zeitnah zu beheben. Dieser proaktive Ansatz trägt deshalb dazu bei,
das Risiko von IT-Sicherheitsverletzungen zu minimieren und das
Vertrauen in die entwickelte Software zu stärken.

Die Idee von Security Sprints, wie sie von Wichers \[34\], Rafi et al.
\[32\] und Maier et al. \[36\] vorgeschlagen wird, stellt eine
spezialisierte Herangehensweise an die IT-Sicherheit dar. Während im
traditionellen Scrum-Ansatz IT-Sicherheitsanforderungen oft als Teil des
regulären Entwicklungszyklus behandelt werden, bieten Security Sprints
eine dedizierte Phase, in der sich das Team ausschließlich auf
IT-Sicherheitsaspekte konzentriert. Diese spezialisierten Sprints
ermöglichen es den Teams, sich intensiv mit den komplexen Aspekten der
IT-Sicherheit auseinanderzusetzen, ohne von anderen Projektanforderungen
abgelenkt zu werden. Es bietet darüber hinaus Raum für eine tiefere und
gründlichere Analyse von IT-Sicherheitsrisiken, die in einem regulären
Sprint möglicherweise übersehen werden könnten. Ein weiterer Vorteil von
Security Sprints ist die Möglichkeit, Experten für IT-Sicherheit in den
Entwicklungsprozess einzubeziehen. Diese Experten können wertvolle
Einblicke und Fachkenntnisse bieten, die über das allgemeine Wissen des
Entwicklungsteams hinausgehen. Durch die Einbindung dieser Expertise
können Sicherheitslücken effektiver identifiziert und behoben werden.

Nach der ausführlichen Darstellung der unterschiedlichen
Umsetzungskonzepte aus der Literatur folgt nun die Herausforderung,
diese sinnvoll zu kombinieren. Das Ziel dieses Ansatzes ist es, die
stärksten und effektivsten Konzepte aus der gesamten Bandbreite der
Literatur zu extrahieren und sie in einem Framework zu vereinen. Dieses
konsolidierte Framework soll die Vorteile der einzelnen Ansätze nutzen
und gleichzeitig potenzielle Schwächen oder Lücken adressieren, um eine
umfassende und robuste Lösung für die IT-Sicherheit in Scrum-Projekten
zu bieten.

### Vorstellung des VS-Scrum Frameworks

In diesem Abschnitt wird das VS-Scrum Framework (siehe Abbildung 5)
vorgestellt. Es werden die spezifischen Rollen und Ereignisse, die im
Zuge des VS-Scrum Frameworks neu eingeführt wurden, detailliert
vorgestellt und erläutert.

Im VS-Scrum Framework übernimmt der Security Master eine zentrale Rolle,
die durch spezifische Verantwortlichkeiten im Bereich der IT-Sicherheit
definiert wird. Basierend auf den Quellen \[6, S. 13\] und \[30\] hat er
die folgenden Hauptaufgaben:

1. **Verwaltung des Security Backlogs:** Er sorgt für die Erfassung,
   Priorisierung und Aktualisierung aller sicherheitsrelevanten
   User-Storys und Anforderungen.
2. **Zuweisung von S-Tags:** Er prüft User-Storys auf
   sicherheitsrelevante Aspekte und kennzeichnet diese bei Bedarf mit
   S-Tags.
3. **Organisation des** **Security Sprints:** Er plant und koordiniert
   spezielle Entwicklungszyklen, die sich ausschließlich auf
   sicherheitsrelevante Anforderungen konzentrieren.

Durch diese Aufgaben gewährleistet der Security Master, dass sowohl agil
als auch sicherheitsbewusst agiert wird.

Der Security Backlog dient als zentrale Stelle für alle dokumentierten
IT-Sicherheitsrisiken, die entweder im Verlauf der speziellen Security
Sprints oder durch umfassende Netzwerk-Penetrationstests identifiziert
wurden (vgl. Konzept A in \[6, S. 11\]). Eine zentrale Rolle bei der
Verwaltung dieses Backlogs spielt der Security Master. Er trifft
Entscheidungen darüber, welche User Storys aus dem Security Backlog in
das kommende Sprint Planning einfließen sollen. Darüber hinaus hat der
Security Master die Aufgabe, User Storys aus dem allgemeinen Product
Backlog zu überprüfen. Er muss beurteilen, ob diese sicherheitsrelevante
Aspekte beinhalten und dementsprechend mit einem S-Tag versehen werden
müssen (vgl. Konzept B in \[6, S. 11\]). Durch diese systematische
Überprüfung wird sichergestellt, dass alle sicherheitsrelevanten Aspekte
während des gesamten Entwicklungsprozesses angemessen berücksichtigt
werden.

Das Sprint Backlog, welches das Ergebnis der Sprint-Planung darstellt,
enthält alle User Storys, die im nächsten Sprint realisiert werden
sollen. Die Dauer eines Sprints kann je nach Bedarf zwischen einer und
vier Wochen variieren. Während des Sprints gibt es ein tägliches
Meeting, welches Daily genannt wird (vgl. Kapitel 2.1.1).

Am Ende jedes Sprints wird ein spezieller Security Sprint durchgeführt
(vgl. Konzept E in \[6, S. 11\]). Das Ziel dieses Security Sprints ist
die Implementierung der User Storys aus dem Security Backlog sowie der
User Storys mit einem S-Tag. Automatisierte Penetrationstests werden
bereits während der Implementierungsphase durchgeführt (vgl. Konzept D
in \[6, S. 11\]). Nach dem Security Sprint wird ein
Netzwerk-Penetrationstest durchgeführt, bei welchem zusätzliche Elemente
wie beispielsweise die Firewall getestet werden. Alle dabei erkannten
Risiken werden in das Security Backlog zurückgeführt. Diese
Zusammenführung aller Methoden versucht den höchsten Grad an
IT-Sicherheit bei der Softwareentwicklung zu erreichen. Abbildung 5
zeigt das VS-Scrum Framework in seiner Gesamtheit.

![](media/image6.emf){width="5.902083333333334in" height="2.78125in"}

[]{#_Ref144157731 .anchor}Abbildung 5: Das VS-Scrum Framework nach
Schubert \[6, S. 14\][^3]

Nach der Präsentation des VS-Scrum Frameworks widmet sich das nächste
Kapitel seiner umfassenden Evaluierung.
