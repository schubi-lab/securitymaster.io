---
title: "1 Einleitung"
description: ""
icon: "article"
date: "2023-08-25T23:13:05+02:00"
lastmod: "2023-08-25T23:13:05+02:00"
draft: false
toc: true
weight: 101
---
> „It takes 20 years to build a reputation and few minutes of
> cyber-incident to ruin it."
>
> \- Stephane Nappo -

In einer Welt, in der dieses Zitat von Stephano Nappo (Vice President
der Groupe SEB) immer relevanter wird, ist die Bedeutung der
IT-Sicherheit nicht zu unterschätzen. Die digitale Landschaft hat sich
rasant entwickelt und mit ihr sind die Bedrohungen und Herausforderungen
gewachsen, welchen Unternehmen täglich gegenüberstehen \[1, S. 11 f.\].
Im Bericht des Bundesamts für Sicherheit in der Informationstechnik
(BSI) ‚Die Lage der IT-Sicherheit in Deutschland 2022' wird darauf
hingewiesen, dass 2021 ein Anstieg der bekannten Schwachstellen um zehn
Prozent im Vergleich zum Vorjahr verzeichnet wurde. Im gesamten Jahr
2021 wurden 20.174 Schwachstellen in Deutschland gemeldet.

Scrum, als eines der führenden agilen Frameworks, hat sich in vielen
Branchen als bevorzugte Methode zur Softwareentwicklung durchgesetzt
\[2, S. 5\]. Aber wie sicher sind die Produkte, die mit Scrum entwickelt
werden?

Die Notwendigkeit, die IT-Sicherheit in den Entwicklungsprozess zu
integrieren, ist offensichtlich. Doch die Verbindung von agilen Methoden
wie Scrum mit robusten IT-Sicherheitspraktiken ist komplex.
Traditionelle Sicherheitsansätze können den schnellen und flexiblen
Abläufen von Scrum im Weg stehen. Daher ist die Entwicklung eines
Frameworks, das Scrum mit den Anforderungen an die IT-Sicherheit
harmonisch miteinander verbindet, von entscheidender Bedeutung.

In den kommenden Kapiteln wird deshalb zunächst die aktuelle
Problemstellung präzisiert. Daraufhin wird das Ziel dieser Arbeit sowie
die zugehörigen Forschungsfragen erläutert. Im Rahmen der
Forschungsmethodik wird dargelegt, wie diese Fragen untersucht werden
und abschließend wird die Struktur der Arbeit aufgezeigt.

## Problemstellung

Wie bereits in der Einleitung deutlich wird, ist die Anzahl der
Schwachstellen in der IT-Landschaft besorgniserregend hoch. Diese
Schwachstellen bieten Einfallstore für die Entwicklung und Verbreitung
von Malware. Im Zeitraum von Juni 2021 bis Mai 2022 nahm die Anzahl neu
verzeichneter Schadprogramm-Varianten in Deutschland um rund 116,6
Millionen zu \[1, S. 13\].

Mittlerweile sind es nicht nur die großen Konzerne, die ins Visier von
Cyberkriminellen geraten. Auch kleinere Unternehmen mit einer
Belegschaft zwischen zehn und 99 Mitarbeitenden sind betroffen \[3, S.
10\]. Eine von Bitkom im Jahr 2021 durchgeführte Studie ergab, dass 86 %
der Cyberangriffe in deutschen Unternehmen zu finanziellen Verlusten
führten \[3, S. 6\], wobei der Gesamtschaden auf 223 Milliarden Euro
anstieg \[3, S. 10\]. Fast die Hälfte der befragten Unternehmen ist
davon überzeugt, dass die Anzahl der Cyberangriffe in der Zukunft
weiterhin stark ansteigen wird \[3, S. 5\]. Dies unterstreicht die
Notwendigkeit für robuste IT-Sicherheitsmaßnahmen in der heutigen Zeit.

Trotz dieser Bedrohungen setzen viele Unternehmen in ihrer
Softwareentwicklung auf das agile Framework Scrum \[2, S. 5\]. Obwohl
Scrum viele Vorteile bietet, fehlen in seiner Grundkonzeption klare
Richtlinien für den Umgang mit IT-Sicherheitsaspekten in der
Softwareentwicklung \[4, S. 647\]. Dies kann dazu führen, dass
Scrum-Teams Schwierigkeiten haben, notwendige Sicherheitspraktiken zu
implementieren. Das Resultat könnte eine anfällige Software sein, die
von Cyberkriminellen ausgenutzt werden kann. Ein Szenario das, wie die
Statistiken zeigen, bereits Realität ist. Wenn sich Scrum-Teams jedoch
ausschließlich auf die Behebung von IT-Sicherheitsproblemen
konzentrieren, könnte dies die Agilität und Effizienz des
Scrum-Prozesses beeinträchtigen \[5, S. 753\].

Um diese Lücke zu schließen, hat der Verfasser dieser Arbeit auf
Grundlage einer umfassenden Literaturrecherche das VS-Scrum Framework
entwickelt \[6\]. Dieses zielt darauf ab, den genannten
Herausforderungen entgegenzuwirken. Jedoch wurde das VS-Scrum Framework
bisher noch nicht ausführlich evaluiert. Im nächsten Abschnitt wird auf
die Zielsetzung der Arbeit eingegangen sowie die Forschungsfragen
formuliert.

## Zielsetzung und Forschungsfrage

Die vorangegangene Einleitung und Problemstellung heben die wachsende
Bedeutung von IT-Sicherheit in der heutigen digitalen Landschaft sowie
die Herausforderungen, die sich bei der Integration von
IT-Sicherheitspraktiken in Scrum ergeben, hervor. Es wird deutlich, dass
trotz der Vorteile, die Scrum bietet, klare Richtlinien für den Umgang
mit IT-Sicherheitsaspekten in seiner Grundkonzeption fehlen. Dies führt
zu einer Diskrepanz zwischen der Notwendigkeit robuster
IT-Sicherheitsmaßnahmen und der agilen Natur von Scrum.

Das Hauptziel dieser Arbeit besteht darin, diese Lücke zu schließen und
ein Framework vorzustellen, das sowohl die Anforderungen an
IT-Sicherheit als auch die Agilität von Scrum berücksichtigt. Das
entwickelte VS-Scrum Framework, soll Scrum-Teams dabei unterstützen,
IT-Sicherheitspraktiken effektiv in ihre Entwicklungsprozesse zu
integrieren, ohne die Vorteile von Scrum zu beeinträchtigen.

Um dieses Ziel zu erreichen und die Relevanz sowie die Wirksamkeit des
VS-Scrum Frameworks zu überprüfen, werden die folgenden Forschungsfragen
aufgestellt:

Frage 1: Wie bewerten Experten[^1] das VS-Scrum Framework in Bezug auf
die Sicherstellung von IT-Sicherheit in Scrum-Projekten?

Diese Frage zielt darauf ab, ein tieferes Verständnis darüber zu
gewinnen, wie das VS-Scrum Framework aus der Perspektive von Experten
wahrgenommen wird. Ihre Bewertungen und Rückmeldungen können wertvolle
Einblicke bieten, um das Framework weiter zu verbessern.

Frage 2: Wie gestaltet sich ein in Bezug auf IT-Sicherheit optimiertes
VS-Scrum Framework?

Anhand dieser Frage soll ermittelt werden, welche spezifischen Merkmale
und Bestandteile in das VS-Scrum Framework integriert oder umgestaltet
werden sollten, um es hinsichtlich der IT-Sicherheit zu optimieren.
Dadurch soll das Framework effektiver und relevanter für Scrum-Teams
gestaltet werden.

Frage 3: Wie bewerten Experten das weiterentwickelte VS-Scrum Framework?

Nachdem das VS-Scrum Framework basierend auf den Erkenntnissen aus Frage
2 weiterentwickelt wurde, ist es wichtig, erneut Feedback von den
Experten einzuholen. Dadurch soll sichergestellt werden, dass das
überarbeitete Framework den Anforderungen gerecht wird und tatsächlich
dazu beiträgt, die IT-Sicherheit in Scrum-Projekten zu verbessern. Im
nächsten Kapitel wird die Methodik beschrieben, mithilfe der diese
Forschungsfragen beantwortet werden sollen.

## Forschungsmethodik

Die Forschungsmethodik legt den methodischen Rahmen für diese
Masterarbeit fest und dient als Leitfaden für die systematische
Beantwortung der Forschungsfragen. Hierfür werden verschiedene
wissenschaftliche Ansätze und Techniken miteinander kombiniert, um eine
fundierte und umfassende Analyse zu gewährleisten.

Das Grundgerüst bildet die problemlösungsorientierte Design Science
Research (DSR) Methode nach Hevner et al. \[7\]. „The design-science
paradigm seeks to extend the boundaries of human and organizational
capabilities by creating new and innovative artifacts" \[7, S. 75\].
Artefakte können nach der Definition von Hevner et al. Konstrukte,
Modelle und Methoden sein, die bei der Entwicklung und Nutzung von
Informationssystemen angewendet werden \[7, S. 82 f.\]. Das in dieser
Arbeit vorgestellte und zu evaluierende Modell, das VS-Scrum Framework,
fällt unter diese Definition und wird daher als zentrales Artefakt der
Forschung herangezogen.

Hevner definierte 2007 zudem die drei Aktivitätszyklen: den Relevanz-,
Stringenz- und Design-Zyklus \[8, S. 87\]. Der Relevanz-Zyklus legt den
Grundstein für die DSR-Methode und bestimmt die Anforderungen einer
bestimmten Anwendungsdomäne, die aus Menschen, Organisationen und
Anwendungssystemen besteht \[8, S. 87\]. Der Stringenz-Zyklus
konzentriert sich auf eine gründliche Literaturrecherche und die
Referenzierung der Wissensbasis \[8, S. 90\]. In der vorliegenden
Masterarbeit dient als Wissensbasis eine Projektarbeit, welche bereits
vom Autor dieser Arbeit zum Thema ‚Gestaltung eines Scrum-Frameworks
unter Einbeziehung der IT-Sicherheit' \[6\] erstellt wurde. Im Rahmen
dieser Arbeit wurde zudem bereits das Artefakt, das VS-Scrum Framework,
entwickelt. Der darauffolgende Design-Zyklus befasst sich mit der
Bewertung und Weiterentwicklung des Artefakts. Hierfür empfehlen
Sonnenberg und vom Brocke \[9\] Fokusgruppeninterviews \[9, S. 8\].
Diese Interviews dienen dazu, Meinungen und Erfahrungen von Experten zu
sammeln und dadurch konstruktives Feedback zum VS-Scrum Framework zu
erhalten \[10, S. 299\].

Fokusgruppeninterviews stellen eine bewährte Methode dar, um qualitative
Daten durch interaktive Diskussionen zwischen den Teilnehmenden zu
sammeln \[10, S. 300\]. Sie bieten die Möglichkeit, tiefe Einblicke in
die Meinungen, Erfahrungen und Perspektiven der Experten zu gewinnen
\[10, S. 299 f.\]. Im Kontext dieser Arbeit sind Fokusgruppeninterviews
besonders wertvoll, weil das VS-Scrum Framework bisher hauptsächlich auf
theoretischen Grundlagen basiert. Es ist daher von entscheidender
Bedeutung, die Perspektiven und Erfahrungen von Praktikern zu
integrieren, um das Framework praxistauglich zu gestalten und an die
realen Anforderungen anzupassen.

Die Planung der Stichprobe für die Fokusgruppeninterviews basiert auf
dem Top-Down-Verfahren nach Hussy et al. \[11, S. 194\]. Für die
gründliche Evaluierung und Weiterentwicklung des Frameworks ist die
Expertise der Interviewpartner von zentraler Bedeutung. Es ist
essenziell, dass Fachleute aus den Bereichen IT-Sicherheit und Scrum in
die Bewertung einbezogen werden. Um sicherzustellen, dass sowohl
IT-Sicherheitsthemen für Scrum-Experten als auch Scrum-relevante Inhalte
für IT-Sicherheitsexperten klar und verständlich sind, wurde ein
Stichprobenplan erstellt (vgl. []{.mark}Tabelle 1). Teil der Stichprobe
soll deshalb ein Experte mit spezifischem Fachwissen im Bereich
IT-Sicherheit und ein weiterer Experte mit einem Schwerpunkt auf Scrum
sein. Zur Vervollständigung der Stichprobe sollen zudem zwei weitere
Fachleute hinzugezogen, die sowohl in der IT-Sicherheit als auch im
Scrum-Bereich versiert sind. Dieser Ansatz gewährleistet eine umfassende
und fundierte Analyse aus verschiedenen Fachperspektiven.

Tabelle 1: Der qualitative Stichprobenplan

| Expertise im Bereich |               | Anzahl: 4 |
| -------------------- | ------------- | --------- |
| Scrum                | IT-Sicherheit | Anzahl    |
| X                    |               | 1         |
| X                    | X             | 2         |
|                      | X             | 1         |

Die Rekrutierung der Teilnehmer für die Fokusgruppeninterviews erfolgte
über einen LinkedIn-Post am 14.04.2023. Der genaue Wortlaut des Aufrufs
zur Teilnahme ist im [Anhang I](#anhang-i-linkedin-post) dokumentiert.
Bei positiven Rückmeldungen oder Interessensbekundungen wurde den
potenziellen Teilnehmern ein Informationsdokument zugesandt, welches im
[Anhang II](#anhang-ii-informationsdokument-zu-vs-scrum) zu finden ist.
Die Rekrutierungsphase wurde am 30.06.2023 abgeschlossen.

Nach Abschluss der Rekrutierungsphase wurden fünf geeignete Kandidaten
gemäß des Stichprobenplans identifiziert. Darunter eine Person, die
ausschließlich Expertise im Bereich Scrum mitbringt, drei Personen, die
sowohl in Scrum als auch in IT-Sicherheit bewandert sind, und eine
Person, die sich auf IT-Sicherheit spezialisiert hat. Die Gruppengröße
von fünf Personen entspricht den Empfehlungen von Kitzinger, die angibt,
dass eine ideale Teilnehmerzahl bei Fokusgruppeninterviews zwischen vier
und acht Personen liegt \[10, S. 301\]. Diese Größe ermöglicht eine
ausgewogene Diskussion, bei der jeder Teilnehmer ausreichend Gelegenheit
hat, seine Meinung zu äußern.

Im nächsten Schritt wurde versucht, einen Termin für die Interviews zu
koordinieren. Da es jedoch nicht gelang, ein Datum zu finden, das für
alle Experten möglich war, konnte ein Experte, der sowohl in Scrum als
auch in der IT-Sicherheit versiert ist, nicht an den Interviews
teilnehmen. Dadurch schrumpfte die Teilnehmerzahl auf vier Personen, was
laut Kitzinger dennoch im Idealbereich liegt \[10, S. 301\] und die
vorherige Stichprobenplanung erfüllt. Das erste Fokusgruppeninterview
fand am 10.07.2023 statt und das zweite Gespräch erfolgte am 09.08.2023.
Die Interviews wurden online über Microsoft Teams durchgeführt, um die
geografischen Herausforderungen zu überwinden, da die Teilnehmenden aus
Deutschland und Frankreich kamen. Dieses Format bot zusätzlich den
Vorteil einer einfacheren Aufzeichnung der Gespräche, was ebenfalls von
Kitzinger empfohlen wird \[10, S. 301\].

Der Ablauf der Fokusgruppeninterviews orientierte sich am Vorgehen von
Krueger \[12, S. 2\]. Nach einer kurzen Vorstellungsrunde wurde den
Teilnehmenden das VS-Scrum Framework präsentiert. Anschließend wurde das
geplante Vorgehen erläutert und anhand der Leifragen über das VS-Scrum
Framework diskutiert.

Die Leitfragen wurden speziell auf die Neuerungen im VS-Scrum Framework
ausgerichtet, insbesondere auf jene Aspekte, die sich vom traditionellen
Scrum-Ansatz unterscheiden. Jede Frage zielt dabei auf einen
spezifischen, neu integrierten Bestandteil ab, um eine umfassende
Evaluierung des VS-Scrum Frameworks zu gewährleisten. Darüber hinaus
wurden Fragen formuliert, um die Effektivität und Anwendbarkeit des
Frameworks zu bewerten. Die Experten wurden zudem dazu befragt, welche
Herausforderungen sie bei einer Implementierung des VS-Scrum Frameworks
sehen und welche Optimierungsvorschläge sie für das Framework haben.
Eine detaillierte Übersicht über die Leitfragen aus beiden
Fokusgruppeninterviews ist in den Anhängen
[III](#anhang-iii-leitfragen-des-ersten-fokusgruppeninterviews) und
[V](#anhang-v-leitfragen-des-zweiten-fokusgruppeninterviews) zu finden.

Im Nachgang wurden die jeweiligen Fokusgruppeninterviews transkribiert.
Hierfür wurde die Methode von Dresing und Pehl \[13\] angewendet. Diese
Methode gewährleistet, dass die Transkriptionen nicht nur wortgetreu,
sondern auch inhaltlich präzise sind \[13, S. 21\]. Nach Abschluss der
Transkription wurde für jedes Interview eine zusammenfasende
Inhaltsanalyse nach Mayring durchgeführt \[14, S. 195\]. Dabei werden
die zentralen Inhalte des Fokusgruppeninterviews paraphrasiert und durch
Reduktion bedeutungsgleicher Paraphrasen reduziert. Dieses Verfahren
ermöglich es, die wesentlichen Informationen herauszufiltern und in
einer strukturierten Form darzustellen \[14, S. 195\]. Die Ergebnisse
dieser Analysen sind in den Anhängen
[IV](#anhang-iv-die-inhaltsanalyse-des-ersten-fokusgruppeninterviews)
und [VI](#anhang-vi-inhaltsanalyse-des-zweiten-fokusgruppeninterviews)
detailliert dargestellt.

Die Inhaltsanalyse liefert Einblicke in die Bewertungen und Meinungen
der Experten bezüglich des VS-Scrum Frameworks. Die Auswertung dieser
Daten ermöglichte es, die erste Forschungsfrage zu beantworten, wie
Experten das VS-Scrum Framework bewerten.

Die Fragen des Fokusgruppeninterviews zielten außerdem darauf ab,
Verbesserungsvorschläge für die Weiterentwicklung zu sammeln, woraus im
Nachgang die Anforderungen und Akzeptanzkriterien formuliert werden
können. Diese Kriterien dienen, basierend auf den Erkenntnissen aus den
Interviews und der Literatur \[8, S. 89\], als Leitfaden für die
Weiterentwicklung des VS-Scrum Frameworks. Mit dem gesammelten Feedback
und den festgelegten Akzeptanzkriterien wurde ein neuer Design-Zyklus
initiiert. Ziel dieses Zyklus war es, ein optimiertes VS-Scrum Framework
zu entwickeln. Dieser Ansatz ermöglicht es, die zweite Forschungsfrage,
wie sich ein in Bezug auf IT-Sicherheit optimiertes Framework gestaltet,
zu beantworten.

Nach Abschluss des Design-Zyklus und der Entwicklung des überarbeiteten
Artefakts ist es von entscheidender Bedeutung, dessen Wirksamkeit und
Relevanz erneut zu überprüfen. Daher wurde die Fokusgruppe erneut
einberufen, um das neu gestaltete VS-Scrum Framework zu evaluieren. Das
Feedback ermöglicht nicht nur die Identifizierung von Stärken und
Schwächen des überarbeiteten VS-Scrum Frameworks, sondern auch die
Anpassung und Optimierung basierend auf den realen Anforderungen und
Erwartungen der Experten. Durch diese iterative Evaluationsmethode kann
schließlich die dritte Forschungsfrage beantwortet werden: Wie bewerten
Experten das weiterentwickelte VS-Scrum Framework?

Die nachfolgende Abbildung 1 zeigt die ganzheitliche Forschungsmethodik
dieser Arbeit. Es handelt sich dabei um ein entsprechend der
Forschungsmethodik angepasstes Modell der DSR-Methode nach Hevner et al.
\[7\].

![Ein Bild, das Text, Screenshot, Kreis, Schrift enthält. Automatisch
generierte Beschreibung](media/image2.png){width="5.885714129483815in"
height="2.731359361329834in"}

[]{#_Ref144157481 .anchor}Abbildung 1: Design Science Research Methode
nach Hevner et al. \[7\]

## Aufbau der Arbeit

Zu Beginn der Masterarbeit wird die zentrale Problemstellung erörtert.
Agile Methoden zählen global zu den bevorzugten Ansätzen in der
Softwareentwicklung. Doch gerade bei der Einbindung von
IT-Sicherheitsanforderungen treten signifikante Herausforderungen auf,
die oft übersehen werden (vgl. Kapitel 1.1). Der Fokus dieser Arbeit
liegt auf dem Vorgehensmodell Scrum. Im Zentrum steht das vom Autor
konzipierte VS-Scrum Framework, welches bisher lediglich auf
literarischen Grundlagen basiert.

Das primäre Ziel dieser Arbeit ist die Evaluation, Optimierung und
erneute Überprüfung des bestehenden VS-Scrum Frameworks. Im Kapitel zur
Forschungsmethodik wird dargelegt, wie mithilfe der DSR-Methode,
unterstützt durch Fokusgruppeninterviews, die Forschungsfragen
beantwortet werden.

Das [zweite Kapitel](#wissensbasis) legt den theoretischen Grundstein
für die Arbeit. Es bietet eine Einführung in die agile Methode Scrum,
wobei zentrale Prinzipien und Rollen beschrieben werden. Im Anschluss
wird die Bedeutung der IT-Sicherheit in der Softwareentwicklung
diskutiert, um ein fundiertes Verständnis für ihre Relevanz und die
damit verbundenen Herausforderungen zu schaffen. Das Kapitel endet mit
einer Vorstellung des VS-Scrum Frameworks, welches als Lösungsansatz für
die Integration von IT-Sicherheit in Scrum dient und im Laufe der Arbeit
weiter untersucht wird. Das [Kapitel
3](#die-evaluierung-im-initialen-design-zyklus) markiert anschließend
den Beginn des initialen Design-Zyklus, in welchem Experten das
Framework evaluieren.

Im darauffolgenden [Kapitel 4](#der-initiale-relevanz-zyklus) wird der
initiale Relevanz-Zyklus beschrieben. Außerdem werden die
Schwierigkeiten bei der Integration von IT-Sicherheit in agile Projekte
beleuchtet. Darauf aufbauend folgt die Formulierung von Anforderungen
und Akzeptanzkriterien für das VS-Scrum Framework 2.0.

Als nächstes erfolgt in [Kapitel
5](#entwicklung-des-vs-scrum-frameworks-2.0) die Konsolidierung der
Ergebnisse des ersten Relevanz-Zyklus. Daraus wird im Rahmen des
Design-Zyklus die Weiterentwicklung des VS-Scrum Frameworks abgeleitet.
Dieser Abschnitt endet mit einer erneuten Evaluation des optimierten
Modells.

Im weiteren Verlauf ([Kapitel
6](#entwicklung-des-vs-scrum-frameworks-3.0)) werden basierend auf dem
Feedback des zweiten Fokusgruppeninterviews erneut Anforderungen und
Akzeptanzkriterien formuliert, die zur Gestaltung des VS-Scrum Framework
3.0 führen.

Im abschließenden [Kapitel 7](#fazit-und-ausblick) werden die Ergebnisse
der Arbeit zusammengefasst und das wissenschaftliche Vorgehen kritisch
reflektiert. Im Rahmen des Stringenz-Zyklus wird der Mehrwert für die
Praxis und die Wissenschaft aufgezeigt. Zum Schluss folgt ein Ausblick
auf zukünftige Forschungsansätze und potenzielle
Weiterentwicklungsmöglichkeiten für das VS-Scrum Framework.
