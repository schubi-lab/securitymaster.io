---
title: "4 Initialer Relevanz-Zyklus"
description: ""
icon: "article"
date: "2023-08-29T17:02:21+02:00"
lastmod: "2023-08-29T17:02:21+02:00"
draft: false
toc: true
weight: 104
---
Der Relevanz-Zyklus verbindet die Umwelt mit den DSR-Aktivitäten (vgl.
[]{.mark}Abbildung 1). Der Zyklus beginnt in den meisten Fällen mit der
Identifizierung von Problemen in einer Anwendungsdomäne \[8, S. 89\]. Im
Anschluss daran werden Anforderungen definiert sowie Akzeptanzkriterien
für die Bewertung des Forschungsergebnisses festgelegt \[8, S. 89\]. Je
nach Ausgang einer Evaluierung kann es nötig sein, weitere Iterationen
durchzuführen \[8, S. 89\].

In den nachfolgenden Kapiteln wird zuerst auf die Herausforderungen bei
der Integration von Anforderungen der IT-Sicherheit in Scrum-Projekten
eingegangen. Weiterführend werden neue Anforderungen an eine
weiterentwickelte Version des VS-Scrum Frameworks gestellt.

## Herausforderungen bei der Integration von IT-Sicherheit in agile Projekte

Bei der Integration von IT-Sicherheit in agile Projekte gibt es diverse
Herausforderungen, die nachfolgend beschrieben werden. Bartsch \[40\]
identifiziert in der Literatur verschiedene Herausforderungen, die er in
folgende Bereiche unterteilet \[22, S. 479 f.\].

1. **Herausforderungen im Prozesslebenszyklus:** „Dynamic process
   changes hinder process audits \[41\] and the iterative nature of the
   processes result in difficulties with in-depth assurance activities
   \[42\], \[43\]" \[22, S. 479 f.\].
2. **Kommunikation und Interaktion:** Der Fokus liegt bei Scrum
   Projekten auf den funktionalen Anforderungen, sodass nicht
   funktionale Anforderungen häufig vernachlässigt werden (vgl. ID57,
   Tabelle 5 im Anhang) \[24, S. 3\], \[44, S. 64\].
3. **Vertrauen in Teams und Einzelpersonen:** Durch die enge

   > Zusammenarbeit, die in agilen Projekten entsteht, kann es
   > passieren, dass die Objektivität von Entwicklern beeinträchtigt
   > wird \[42, S. 49\]. Ohne die explizite Rolle eines
   > IT-Sicherheitsexperten kann es zudem an Expertise im Bereich der
   > IT-Sicherheit mangeln \[24, S. 3\].
   >

Eine weitere Herausforderungen ist die Schnelllebigkeit in der heutigen
kommerziellen Softwareentwicklung \[17, S. 1\], \[45, S. 1\].
IT-Sicherheitsstandards erfordern häufig einen Prozess bezüglich der
Identifizierung sowie Behebung von Sicherheitslücken \[45, S. 1\]. Dies
widerspricht jedoch dem agilen Ansatz, starre Prozesse zu vermeiden und
diese unter Individuen und Interaktionen zu stellen (vgl. Kapitel 2.1).

Eine weitere Herausforderung entsteht, da der Fokus bei der agilen
Softwareentwicklung auf funktionierende Software und nicht auf
umfassende Dokumentation liegt (vgl. Kapitel 2.1). Mit weniger Fokus auf
Dokumentation ist allerdings nur ein ineffektiver Wissensaustausch
zwischen den Teammitgliedern und dem IT-Sicherheits-Experten möglich
\[24, S. 3\].

Im Rahmen des ersten Fokusgruppeninterviews haben die befragten Experten
ebenfalls Herausforderungen genannt, die bei der Integration von
IT-Sicherheit in agilen Projekten auftreten können. Ähnlich wie es
bereits in der Literatur beschrieben wird, sehen die Interviewpartner
die Problematik, dass IT-Sicherheit keinen Funktionsmehrwert bietet
(vgl. ID57, Tabelle 5 im Anhang). Weil dadurch kein Business-Wert
entsteht, kann es zu einem „Interessenskonflikt oder Zielkonflikt"
(ID58, Tabelle 5 im Anhang) kommen.

Die Befragten sind sich einig, dass eine frühe und kontinuierliche
Berücksichtigung der IT-Sicherheit Probleme zum Ende der Entwicklung
verhindern kann (vgl. ID58, ID59, ID60 , Tabelle 5 im Anhang).
Allerdings stellt die kontinuierliche Mitbetrachtung eine
Herausforderung dar, weil sie zu einer längeren Entwicklungsdauer führen
kann (vgl. ID60, Tabelle 5 im Anhang). Eine zentrale Herausforderung
liegt zudem in der Ressourcenallokation und Budgetierung für
IT-Sicherheitsexperten (vgl. ID48, Tabelle 5 im Anhang).

Nachdem geklärt wurde, welche Herausforderungen es bei der Integration
von IT-Sicherheit in agilen Projekten gibt und die Wissensbasis
dargelegt wurde, erfolgt im nachfolgenden Kapitel die Definition von
Anforderungen und Akzeptanzkriterien an das VS-Scrum Framework 2.0.

## Anforderungen und Akzeptanzkriterien an das VS-Scrum Framework 2.0

Nach der Evaluierung des Frameworks (vgl. Kapitel 3.2) werden im
weiteren Verlauf die Anforderungen und Akzeptanzkriterien formuliert, um
ein in Bezug auf IT-Sicherheit optimiertes VS-Scrum Framework zu
gestalten. Hierfür wurde im Rahmen des Fokusgruppeninterviews ergänzend
zur Evaluierung die folgende Frage gestellt: „Welche Verbesserungen oder
Änderungen würden Sie am VS-Scrum Framework vorschlagen, um es besser an
Ihre spezifischen Projektanforderungen anzupassen?" (Folie 15, \[39\]).

**Integration in ein IT-Sicherheitsmanagement-Konzept**

Ein Interviewpartner schlug vor, das VS-Scrum Framework in ein
IT-Sicherheitsmanagement-Konzept zu integrieren, damit die
Praktikabilität und Relevanz für die Praxis erhöht wird (vgl. ID10,
Tabelle 5 im Anhang). Dies lässt sich im Rahmen des VS-Scrum Frameworks
nicht abbilden, kann aber anhand einer Implementierungsbeschreibung im
Unternehmen berücksichtigt werden.

**User Story:**

Als Experten möchten wir das agile Framework in unser
IT-Sicherheitsmanagement-Konzept integrieren, um die Praktikabilität und
Relevanz für die Praxis zu erhöhen.

**Akzeptanzkriterium:**

Das agile Framework wird im Rahmen einer Implementierung vollständig in
das bestehende IT-Sicherheitsmanagement-Konzept integriert.

**Security Backlog und Security Master**

Der Security Backlog wurde im Interview eher auf der Unternehmensebene
als sinnvoll erachtet (vgl. ID18, Tabelle 5 im Anhang). Durch diese
Maßnahme entsteht eine übergreifende Transparenz über alle Projekte
hinweg. Zudem können wiederkehrende Themen zentral im unternehmensweiten
Security Backlog erfasst und ganzheitlich adressiert werden (vgl. ID11,
ID12, Tabelle 5 im Anhang). Im Umkehrschluss kann sich der Security
Master bezüglich Standardanforderungen aus dem Security Backlog bedienen
und diese dem Product Owner bereits von Beginn an bereitstellen (vgl.
ID25, ID26, Tabelle 5 im Anhang). Der Security Master selbst wird aus
einem Pool von Security Mastern gestellt, welcher auf der
Organisationebene integriert ist (vgl. ID70, Tabelle 5 im Anhang). Die
Verantwortung für den Security Backlog und die Steuerung des Security
Master Pools liegt beim Security Owner als neue Rolle (vgl. ID71,
Tabelle 5 im Anhang).

**User Story 1:**

Als Experten möchten wir Security-Themen aus dem Projekt an ein
zentrales Security Backlog melden können, um projektübergreifende
Transparenz zu schaffen, damit Themen bei Bedarf zentral bearbeitet
werden können.

**Akzeptanzkriterien 1:**

- Es gibt einen zentralen Security Backlog auf der Organisationsebene.
- Der Security Backlog auf der Projektebene wird entfernt.
- Der Security Master hat die Möglichkeit, Themen an den Security
  Backlog zu melden.

**User Story 2:**

Als Experten möchten wir dem Product Owner einen Katalog an relevanten
Anforderungen aus dem Security Backlog bereitstellen können, damit
organisationsweite standardisierte Anforderungen ressourcenschonend in
das Projekt übernommen werden können.

**Akzeptanzkriterien 2:**

- Im Security Backlog sind Standardanforderungen bezüglich der
  IT-Sicherheit definiert.
- Der Security Master kann Anforderungen aus dem unternehmensweiten
  Security Backlog in das Projekt übernehmen.

**User Story 3:**

Als Experten möchten wir die Einführung einer spezifischen Rolle, die
für den organisationsweiten Security Backlog verantwortlich ist, um
klare Zuständigkeiten sicherzustellen.

**Akzeptanzkriterium 3:**

Es gibt eine neue Rolle, welche die Verantwortung über den
organisationsweiten Security Backlog innehat.

**User Story 4:**

Als Experten möchten wir, dass der Security Master aus einem
organisationsweiten Pool an Security Mastern gestellt wird, damit diese
in verschiedenen Projekten eingesetzt werden können.

**Akzeptanzkriterium 4:**

Es gibt auf der Organisationsebene einen Pool an Security Mastern.

**Security Sprints**

Es soll keine spezifischen Security Sprints geben. Stattdessen wurde von
den Experten im Interview vorgeschlagen, bei Bedarf den Fokus in den
Sprintzielen auf die IT-Sicherheit zu legen (vgl. ID34, ID86, Tabelle 5
im Anhang). Dadurch sollen die Konflikte in Bezug auf die
Verantwortlichkeiten zwischen dem Security Master und dem Scrum Master
vermieden werden (vgl. ID27, Tabelle 5 im Anhang).

**User Story:**

Als Experten möchten wir bei Bedarf einen Security Fokus in den
Sprintzielen setzten und keine separaten Security Sprints durchführen,
damit keine Konflikte bezüglich der Verantwortlichkeit zwischen Security
Master und Scrum Master entstehen und es eine hohe Flexibilität gibt.

**Akzeptanzkriterien:**

- Der Security Sprint wird aus dem VS-Scrum Framework entfernt.
- Bei Bedarf wird ein Security Fokus in den Sprintzielen gesetzt.

**S-Tags**

Ergänzend dazu würden die Interviewten die Prüfung, ob S-Tags nötig
sind, bereits im Refinement ansiedeln (vgl. ID22, ID23, Tabelle 5 im
Anhang). Dort findet die Prüfung jeder einzelnen User Story hinsichtlich
der Notwendigkeit eines S-Tags statt (vgl. ID24, Tabelle 5 im Anhang).
Dabei wird der Product Owner bei Bedarf vom Security Master entsprechend
beraten (vgl. ID24, Tabelle 5 im Anhang).

**User Story:**

Als Experten möchten wir während des Refinements sicherstellen, dass die
Notwendigkeit eines S-Tags geprüft wird. Außerdem wünschen wir uns bei
Bedarf eine gezielte Beratung durch den Security Master, damit die
Anforderungen im Product Backlog bereits korrekt eingeschätzt sind.

**Akzeptanzkriterien:**

- Im VS-Scrum Framework wird das Refinement ergänzt.
- Die Prüfung, ob S-Tags notwendig sind, findet im Rahmen des
  Refinements statt.

**Penetrationstests**

Im aktuellen Stadium des VS-Scrum Frameworks sind die Penetrationstests
nach dem Sprint angesiedelt (vgl. Kapitel 2.3.2), weshalb sie von den
Befragten als Endtests angesehen wurden (vgl. ID33, Tabelle 5 im
Anhang). Aus diesem Grund waren sich die Experten einig, dass nicht von
Penetrationstests, sondern von Validierungsmaßnahmen gesprochen werden
sollte (vgl. ID33, Tabelle 5 im Anhang), die bereits im Rahmen des
Sprints durchgeführt werden (vgl. ID35, Tabelle 5 im Anhang). Die
Validierungsmaßnahmen können entweder allgemeine Vorgaben der
Organisation sein, die aus dem unternehmensweiten Security Backlog
stammen, oder sie können projektspezifisch definiert werden (vgl. ID33,
ID36, Tabelle 5 im Anhang). Standardisierte Vorgehensweisen, wie
beispielsweise ein Red Team Assessment, befinden sich ebenfalls im
organisationsweiten Security Backlog und können dort im Rahmen von
Services gebucht werden (vgl. ID36, Tabelle 5 im Anhang).

**User Story 1:**

Als Experten möchten wir, dass die Penetrationstests als ein Teil von
umfänglicheren Validierungsmaßnahmen gesehen werden, die bereits während
des Sprints durchgeführt werden, um eine höhere Flexibilität zu
erreichen.

**Akzeptanzkriterien 1:**

- Die Penetrationstests nach dem Sprint werden aus dem VS-Scrum
  Framework entfernt.
- Die Penetrationstests werden Teil der Validierungsmaßnahmen.

**User Story 2:**

Als Experten möchten wir einen unternehmensweiten Security Backlog mit
buchbaren, standardisierten Validierungsmaßnahmen und
organisationsweiten Anforderungen, damit einheitliche Standards gesetzt
und redundante Arbeiten vermieden werden können.

**Akzeptanzkriterien 2:**

- Im organisationsweiten Security Backlog gibt es
  Validierungsmaßnahmen mit buchbaren Services.
- Im organisationsweiten Security Backlog gibt es standardisierte
  organisationsweite Anforderungen.

**Ergänzende** **Anforderung**

Des Weiteren wurde während des Interviews angemerkt, dass die
Darstellung des Pfeils vom Scrum Master lediglich auf das Daily zeigt
(vgl. Abbildung 5). Dies könnte den Eindruck erwecken, dass der Scrum
Master ausschließlich für das Daily verantwortlich ist. Aus diesem Grund
wurde vorgeschlagen, den Pfeil so zu modifizieren, dass dieser auf den
gesamten Sprint zeigt.

**User Story:**

Als Experten möchten wir, dass der Pfeil vom Scrum Master auf den
gesamten Sprint zeigt, um zu verdeutlichen, dass er den gesamten Sprint
und nicht nur das Daily koordiniert.

**Akzeptanzkriterium:**

Der Pfeil vom Scrum Master zeigt auf den gesamten Sprint.

Nach Hevner \[8, S. 89\] definieren die festgelegten Anforderungen und
Akzeptanzkriterien den Abschluss des Relevanz-Zyklus. Im nachfolgenden
Kapitel wird ein neuer Design-Zyklus eingeleitet, in dessen Rahmen das
VS-Scrum Framework 2.0 gestaltet wird. Nach der Weiterentwicklung des
VS-Scrum Frameworks wird eine erneute Evaluierung anhand eines zweiten
Fokusgruppeninterviews vorgenommen.
