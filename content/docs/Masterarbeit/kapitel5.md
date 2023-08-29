---
title: "5 Entwicklung des VS-Scrum Frameworks 2.0"
description: ""
icon: "article"
date: "2023-08-29T17:02:51+02:00"
lastmod: "2023-08-29T17:02:51+02:00"
draft: false
toc: true
weight: 105
---
Nachdem im vorherigen Kapitel die Anforderungen und Akzeptanzkriterien detailliert dargelegt wurden, liegt der Fokus in diesem Kapitel auf der
Entwicklung und Gestaltung des VS-Scrum Frameworks 2.0. Dabei wird
besonderer Wert auf die Integration der zuvor identifizierten
Anforderungen gelegt, um ein optimiertes Framework zu schaffen.

Der nachfolgende Design-Zyklus stellt einen systematischen Ansatz dar,
damit die im vorherigen Kapitel definierten Anforderungen in ein
konkretes Framework überführt werden. Als erstes wird die Konsolidierung
der Ergebnisse aus dem Relevanz-Zyklus vorgenommen.

Im darauffolgenden Schritt erfolgt die Konzeptionierung. Hierbei werden
die zuvor definierten Anforderungen und Akzeptanzkriterien in konkrete
Design-Entscheidungen überführt. Abschließend wird das VS-Scrum
Framework überarbeitet, indem die Design-Entscheidungen eingearbeitet
werden. Besonderer Wert wird dabei auf die Integration von
IT-Sicherheitsaspekten gelegt.

## Konsolidierung der Ergebnisse des ersten Relevanz-Zyklus

Die Konsolidierung der Ergebnisse des Relevanz-Zyklus stellt einen
entscheidenden Schritt im Design-Zyklus dar. Hierbei werden die im
vorherigen Kapitel 4.2 identifizierten Anforderungen und
Akzeptanzkriterien systematisch analysiert und in eine strukturierte
Form gebracht, um als Grundlage für die Weiterentwicklung des VS-Scrum
Frameworks 2.0 zu dienen.

Zunächst werden die zentralen Anforderungen, die aus dem
Fokusgruppeninterview hervorgegangen sind, zusammengefasst und im
Folgenden aufgelistet.

**Security Backlog auf Organisationsebene:** Ein zentraler Security
Backlog auf Organisationsebene soll für eine übergreifende Transparenz
über alle Projekte hinweg sorgen und wiederkehrende IT-Sicherheitsthemen
zentral adressieren. Der Security Owner ist für den Security Backlog
verantwortlich.

**Security Master Pool auf Organisationsebene:** Ein zentraler Pool mit
einer Vielzahl an Security Mastern, die bedarfsgesteuert in
verschiedenen Projekten mitarbeiten.

**Vermeidung spezifischer Security Sprints:** Statt separater Security
Sprints wird auf einen flexibleren Ansatz gesetzt, bei dem bei Bedarf
ein Fokus auf IT-Sicherheit in den Sprintzielen gesetzt wird.

**Frühe Einbindung von S-Tags:** Die Notwendigkeit von S-Tags soll
bereits im Refinement geprüft werden, um sicherzustellen, dass
IT-Sicherheitsanforderungen von Anfang an berücksichtigt werden.

**Neudefinition der Penetrationstests:** Die Penetrationstests sollen
als Teil umfassenderer Validierungsmaßnahmen betrachtet werden, die
bereits während des Sprints durchgeführt werden. Validierungsmaßnahmen
und organisatorische Anforderungen sind im organisationsweiten Security
Backlog hinterlegt. Der Security Master kann Anforderungen aus dem
Projekt an den Security Backlog melden und Anforderungen daraus
bedarfsgesteuert in das Projekt einbringen.

**Visuelle Darstellungsanpassung:** Der Scrum Master koordiniert den
gesamten Sprint und nicht nur das Daily.

Im nachfolgenden Kapitel werden konkrete Design-Entscheidungen
getroffen, die zur Überarbeitung des VS-Scrum Frameworks notwendig sind.

## Weiterentwicklung des VS-Scrum Framework

Für die Weiterentwicklung des VS-Scrum Frameworks werden die
konsolidierten Ergebnisse aus dem vorherigen Kapitel in
Design-Entscheidungen überführt, woraus letztendlich das VS-Scrum
Framework 2.0 entsteht. Die nachfolgende Tabelle 2 zeigt die
zugrundeliegenden Design Entscheidungen.

[]{#_Ref144159218 .anchor}Tabelle 2: Design-Entscheidungen zur
Weiterentwicklung des VS-Scrum Frameworks

+---------------+---+---------------------------------------------------+
| Thema         |   | Design-Entscheidung                               |
+===============+===+===================================================+
| Security      |   | 1.  Es gibt die folgenden zwei Bereiche: das      |
| Backlog auf   |   |     > Projektumfeld und das Organisationsumfeld.  |
| Organ         |   |     > Jedes Projekt ist Teil der Organisation und |
| isationsebene |   |     > wird daher innerhalb des                    |
|               |   |     > Organisationsumfelds dargestellt.           |
|               |   |                                                   |
|               |   | 2.  Der Security Backlog wird aus dem             |
|               |   |     > Projektumfeld entfernt und zentral auf der  |
|               |   |     > Organisationsebene geführt.                 |
|               |   |                                                   |
|               |   | 3.  Auf der Organisationsebene wird die Rolle     |
|               |   |     > ‚Security Orga Lead' hinzugefügt.           |
+---------------+---+---------------------------------------------------+
| Security      |   | 1.  Es wird neben dem Projektumfeld im            |
| Master Pool   |   |     > Organisationsumfeld ein weiterer Bereich    |
| auf           |   |     > hinzugefügt, der den Namen ‚Security Master |
| Organ         |   |     > Pool' trägt.                                |
| isationsebene |   |                                                   |
|               |   | 2.  Ein neuer Pfeil mit der Beschriftung          |
|               |   |     > ‚steuert' zeigt vom Security Orga Lead auf  |
|               |   |     > den Security Master Pool.                   |
+---------------+---+---------------------------------------------------+
| Security      |   | Der Security Sprint wird aus dem Framework        |
| Sprints       |   | entfernt.                                         |
+---------------+---+---------------------------------------------------+
| Frühe         |   | 1.  Es wird ein Refinement hinzugefügt, welches   |
| Einbindung    |   |     > direkt auf den Product Backlog verweist.    |
| von S-Tags    |   |                                                   |
|               |   | 2.  Vom Security Master verweist ein Pfeil auf    |
|               |   |     > das Refinement, beschriftet mit ‚Prüfung,   |
|               |   |     > ob S-Tag nötig'.                            |
+---------------+---+---------------------------------------------------+
| Neudefinition |   | 1.  Penetrationstests, die nach dem Sprint        |
| der           |   |     > durchgeführt werden, sind nicht mehr Teil   |
| Pene          |   |     > des VS Scrum Frameworks.                    |
| trationstests |   |                                                   |
|               |   | 2.  Im unternehmensweiten Security Backlog sind   |
|               |   |     > sowohl Validierungsmaßnahmen als auch       |
|               |   |     > organisationsweite Anforderungen verankert. |
|               |   |                                                   |
|               |   | 3.  Vom Security Master zeigt ein Pfeil zum       |
|               |   |     > Security Backlog. Dieser Pfeil ist mit      |
|               |   |     > ‚meldet neue Anforderungen aus dem Projekt  |
|               |   |     > zurück' beschriftet.                        |
|               |   |                                                   |
|               |   | 4.  Ein weiterer Pfeil verbindet den Security     |
|               |   |     > Master mit dem Security Backlog und trägt   |
|               |   |     > die Beschriftung ‚prüft Bedarf'.            |
+---------------+---+---------------------------------------------------+
| Visuelle      |   | 1.  Ein neues Element wird integriert, welches    |
| Darstell      |   |     > eine Zusammenstellung von ‚User Storys,     |
| ungsanpassung |   |     > Features und Epics' darstellt. Vom Security |
|               |   |     > Master zeigt ein Pfeil über den Security    |
|               |   |     > Backlog zu diesem Element. Der Pfeil ist    |
|               |   |     > mit ‚bringt bei Bedarf ein' gekennzeichnet. |
|               |   |                                                   |
|               |   | 2.  Vom Element ‚User Storys, Features und Epics' |
|               |   |     > führt ein neuer Pfeil mit dem Namen         |
|               |   |     > ‚Refinement' zum Product Backlog.           |
|               |   |                                                   |
|               |   | 3.  Der mit ‚koordiniert' beschriftetet Pfeil vom |
|               |   |     > Scrum Master zeigt auf den gesamten Sprint. |
+---------------+---+---------------------------------------------------+

Die untenstehende Abbildung 6 zeigt die Implementierung der obigen
Design-Entscheidungen in das Framework und beantwortet somit die zweite
Forschungsfrage, wie sich ein in Bezug auf IT-Sicherheit optimiertes
Framework gestaltet.

![Ein Bild, das Diagramm, technische Zeichnung, Plan enthält.
Automatisch generierte
Beschreibung](media/image7.png){width="9.315972222222221in"
height="3.939583333333333in"}

[]{#_Ref144159245 .anchor}Abbildung 6: Das VS-Scrum Framework 2.0[^4]

## Ergebnisse des zweiten Fokusgruppeninterviews

Nach der Durchführung des initialen Design-Zyklus und der Betrachtung
der Herausforderungen, die bei der Integration von IT-Sicherheit in
agilen Projekten identifiziert wurden, erfolgt im weiteren Verlauf der
zweite Schritt des Design-Zyklus, die Evaluierung (vgl. Abbildung 1).
Diese erfolgt auf der Basis eines zweiten Fokusgruppeninterviews \[46\].

Als erstes wurde im Interview eine detaillierte Rückblende auf das
VS-Scrum Framework 1.0 durchgeführt, um den Teilnehmern einen
eindeutigen Kontext und ein Verständnis für die bisherige Entwicklung zu
geben. Anschließend wurde das aktualisierte VS-Scrum Framework 2.0
vorgestellt. Dabei wurden alle Neuerungen und Optimierungen, die
aufgrund der Anforderungen und Akzeptanzkriterien aus dem ersten
Fokusgruppeninterview entwickelt wurden, erläutert. Während dieser
Vorstellung hatten die Interviewten jederzeit die Gelegenheit, Fragen zu
stellen, insbesondere wenn es Schwierigkeiten beim Verständnis gab.
Daraus entstanden bereits weitere Verbesserungsvorschläge, die im
nächsten Kapitel ausführlich dargelegt werden.

Im Anschluss daran wurden, ähnlich wie im ersten Interview, Leitfragen
zur Evaluierung des Frameworks gestellt. Diese dienten als Grundlage für
die Evaluierung des aktualisierten Modells. Als nächstes werden die
Leitfragen (vgl. Tabelle 6) inklusive der daraus resultierenden
Ergebnisse präsentiert.

**Security Master**

Die erste Frage bezog sich, ähnliche wie im ersten Interview, auf die
Rolle des Security Masters. Die Fragestellung lautete: „Wie beurteilen
Sie die Rolle des Security Masters im VS-Scrum Framework 2.0?" (Folie 6,
\[47\]).

Daraufhin wurde von den Interviewten diskutiert, ob die Bezeichnung
‚Security Expert' anstelle von ‚Security Master' verwendet werden
könnte, um eine eindeutige Abgrenzung zum Scrum Master zu schaffen (vgl.
ID14, Tabelle 7 im Anhang). Es wurde vom Interviewer jedoch darauf
hingewiesen, dass der Begriff ‚Security Master' nicht willkürlich
gewählt wurde, sondern seine Wurzeln in der Literatur hat (vgl. ID15,
Tabelle 7 im Anhang). Einige Interviewte vermuteten, dass die Wahl des
Begriffs ‚Master' dazu dient, der Rolle eine ähnliche Bedeutung wie dem
Scrum Master zu verleihen und dadurch die Wichtigkeit der IT-Sicherheit
hervorzuheben (vgl. ID16, ID20, Tabelle 7 im Anhang). Zudem gab es
Bedenken, dass die Bezeichnung ‚Security Expert' den Eindruck erwecken
könnte, dass die Rolle optional ist (vgl. ID19, Tabelle 7 im Anhang).
Zusätzlich betont die Bezeichnung ‚Master' die Bedeutung der Rolle (vgl.
ID20, Tabelle 7 im Anhang). Es gab außerdem den Vorschlag, dass es
sinnvoll sein könnte, Begriffe direkt aus dem Scrum Framework zu
übernehmen, insbesondere da der Fokus auf dem IT-Sicherheitsmanagement
im Kontext von Scrum liegt (vgl. ID21, Tabelle 7 im Anhang).
Abschließend wurde noch angemerkt, dass es möglicherweise
Akzeptanzprobleme geben könnte, wenn jemand mit dem Titel ‚Security
Master' Anweisungen zur IT-Sicherheit gibt (vgl. ID18, Tabelle 7 im
Anhang), weshalb Schulungen zwingend erforderlich seien (vgl. ID30,
Tabelle 7 im Anhang).

Des Weiteren ist es den Interviewten schwergefallen, den Transfer zu
leisten, wie der Pfeil vom Security Master zu den User Storys, Features
und Epics übergeht (vgl. ID4, Tabelle 7 im Anhang).

**Security Orga Lead**

Die zweite Frage bezog sich auf die neue Rolle Security Orga Lead. Die
Fragestellung hierzu lautete: „Wie bewerten Sie die Rolle des Security
Orga Lead im VS-Scrum Framework 2.0?" (Folie 7, \[47\]).

Ein Interviewpartner schlug vor, die Steuerung des Security Master Pools
von einem Projektmanagementbüro übernehmen zu lassen, während die
Verantwortung für den Security Backlog idealerweise, beim Chief
Information Security Officer (CISO) liegen sollte (vgl. ID22, Tabelle 7
im Anhang). Es gab jedoch Bedenken hinsichtlich der Notwendigkeit einer
separaten Rolle des Security Orga Leads, weil der CISO bereits die
anstehenden IT-Sicherheitsmaßnahmen und sein Team betreut. Aus diesem
Grund wurde die Einführung einer solchen Rolle schlussendlich als
überflüssig eingestuft (vgl. ID23, Tabelle 7 im Anhang). Des Weiteren
schlugen die Experten vor, das VS-Scrum Framework im Rahmen einer
Implementierung beim CISO anzusiedeln (vgl. ID24, Tabelle 7 im Anhang).

**Security Backlog**

Bezüglich des neuen organisationsweiten Security Backlogs wurde die
dritte Frage „Wie bewerten Sie die Idee eines organisationsweiten
Security Backlogs im VS-Scrum Framework 2.0?" gestellt (Folie 8,
\[47\]).

Zu diesem Thema gab es, bis auf einen Änderungswunsch bezüglich der
Formulierung, kein weiteres Feedback mehr (vgl. ID25, ID26, Tabelle 7 im
Anhang). Es sollte lediglich die Begrifflichkeit ‚allgemeine
Anforderungen' durch ‚organisationsweite IT-Sicherheitsanforderungen'
ersetzt werden (vgl. ID26, Tabelle 7 im Anhang).

**Anwendbarkeit**

Anhand der vierten Frage wurde die Anwendbarkeit des VS-Scrum Frameworks
diskutiert. Der Interviewer stellte hierzu die folgende Leitfrage: „Wie
bewerten Sie die Anwendbarkeit des VS-Scrum Frameworks 2.0 in Ihrer
aktuellen Arbeitsumgebung?" (Folie 9, \[47\]).

Die aktuelle Version des Frameworks erhielt eine positive Bewertung
hinsichtlich ihrer Anwendbarkeit \[46, S. 23\]. Ein Merkmal ist die
klare Definition von IT-Sicherheitsanforderungen. Diese Strukturierung
gibt dem Projektteam nicht nur eine klare Richtung vor, sondern lässt
ihnen auch genügend Spielraum. Das Team hat die Flexibilität,
eigenständig zu entscheiden, wann genau diese Anforderungen umgesetzt
werden sollen. Diese Balance zwischen Struktur und Flexibilität wurde
von den Befragten besonders geschätzt (vgl. ID27, Tabelle 7 im Anhang).

**Herausforderungen**

Anlässlich der fünften Frage „Welche Herausforderungen sehen Sie bei der
Implementierung des VS-Scrum Frameworks 2.0 in einer Organisation?"
(Folie 10, \[47\]) konnten einige Herausforderungen identifiziert
werden.

Die Interviewpartner zeigten ein gemeinsames Verständnis dafür, dass die
Implementierung des VS-Scrum Frameworks 2.0 durchaus realisierbar ist
\[46, S. 30\]. Dennoch wurde betont, dass die Implementierungsphase die
größte Herausforderung sein könnte (vgl. ID28, Tabelle 7 im Anhang).

Ein weiterer Aspekt ist die potenzielle zeitliche Belastung für den
Security Master, insbesondere wenn er die Verantwortung für mehrere
Projekte gleichzeitig übernehmen muss (vgl. ID29, Tabelle 7 im Anhang).
Ein weiteres kritisches Thema stellt die Ressourcenplanung dar. Dabei
könnte es eine Herausforderung sein, sicherzustellen, dass alle
Teammitglieder kontinuierlich präsent und die erforderlichen Ressourcen
stets verfügbar sind (vgl. ID31, Tabelle 7 im Anhang).

Die Diskussion im Fokusgruppeninterview hat bereits aufgezeigt, dass es
hinsichtlich der Benennung des Security Masters zu Verständnisproblemen
kommen könnte. Dies und die Einführung neuer Konzepte erfordert deshalb
gezielte Schulungen (vgl. ID30, Tabelle 7 im Anhang).

Abschließend wurde die Häufigkeit von Refinements angesprochen. Es
bleibt abschließend unklar, wie oft diese stattfinden sollten. Deshalb
stellt dies eine wichtige Entscheidung im Kontext des jeweiligen
Projekts dar (vgl. ID32, Tabelle 7 im Anhang).

**Effektivität**

Des Weiteren beantworteten die Interviewpartner die Fragestellung: „Wie
schätzen Sie die Effektivität des VS-Scrum Frameworks 2.0 im Hinblick
auf die Verbesserung der IT-Sicherheit in Scrum-Projekten ein?" (Folie
11, \[47\]).

Unter den Befragten herrschte ein Konsens darüber, dass die Beteiligung
eines Experten, der sich auf IT-Sicherheitsanforderungen spezialisiert
hat und bedarfsgesteuert S-Tags vergibt, eine wesentliche Bereicherung
für den Prozess darstellt (vgl. ID33, Tabelle 7 im Anhang).

Ein weiterer Vorteil besteht darin, dass das VS-Scrum Framework nicht
nur zur Produktentwicklung, sondern auch als agiler Ansatz zur
sukzessiven Umsetzung von IT-Sicherheitsmaßnahmen in verschiedenen
Organisationsbereichen, in welchen IT-Sicherheit relevant ist, genutzt
werden kann (vgl. ID35, Tabelle 7 im Anhang).

Des Weiteren wurde die Integration von Anforderungen aus dem Security
Backlog in das Projekt als positiv angesehen. Diese können so formuliert
werden, dass sie von den Projektmitarbeitern leicht verstanden und
einfach vom Security Backlog in das Product Backlog übertragen werden
können (vgl. ID35, Tabelle 7 im Anhang).

Im Anschluss an die Evaluierung des weiterentwickelten Modells widmet
sich das folgende Kapitel der Ausarbeitung des VS-Scrum Framework 3.0.
Dieses basiert auf den Anforderungen und Akzeptanzkriterien, die aus dem
zweiten Fokusgruppeninterview abgeleitet werden.
