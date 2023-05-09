# Punktevergabeprozess WWI20SEA

## Allgemeines Feedback 
Die Studierenden haben die beiden Semester (5 & 6) m.E. hervorragend genutzt, um innovative Konzepte und Technologien im Rahmen der Entwicklung mobiler Applikationen zu erkunden.   

Neben vielen konkreten Technologien ging es mir insbesondere darum den Studierenden Erfahrungsräume aufzuspannen innerhalb derer sie die Entwicklung mobiler Applikationen konkret im Kontext von aktuellen Megatrends im Bereich des Software Engineerings erkunden konnten. So wurde beispielsweise der aktuelle Megatrend hin zu mehr **Open Source Software** und der Megatrend hin zu mehr **Dezentralisierung (Web3)** ins Kalkül genommen und kreativ genutzt und mitgestaltet.  

Um die Lernziele möglichst effizient zu erreichen und die Lernerfahrungen mit Begeisterung zu kombinieren hatten die Studierenden bei der Gestaltung der konkreten Projekte sehr viele Freiräume, welchen sie aus meiner Perspektive gut genutzt haben. 

## Besondere Herausforderungen für die Studierenden
Weite Teile der aktuell einflussreichen politischen Kaste verursachten in der jüngeren Vergangenheit einige Rückschläge seitens einiger Crypto- / Web3 Startups und dadurch auch seitens einiger Web3 Technologien bzw. Web3 Tools. Das hat die Studierenden auch insofern mit beeinflusst als dass viele der Web3 Tools aktuell in einem schlechten Maintenance- und Dokumentationszustand sind was natürlich den Fortschritt im Hinblick auf die Umsetzung einiger Aspekte stark verlangsamt hat (z.B. "https://flutter.dev not ready for web3" uvm.). Die Studierenden blieben fast immer mutig und haben kreativ nach Workarounds etc. gesucht und fast immer auch weitgehend passende Workarounds gefunden.


## Bewertungskriterien
Ein repräsentatives Value Proposition Canvas wurde angefertigt  
Die User Stories sind klar dokumentiert  
Die App funktioniert performant und fehlerfrei  
Die App bietet eine gute User Experience (mit wenigen "clicks" ... zum gewünschten Ergebnis...)  
Die App ist sicher (Datenschutz, need to know prinzip etc. / Möglichst resistent gegenüber (D)DOS Attacks etc.)  
Hohe Codequalität (Separation of Concerns, High Cohesion, Loose Coupling, automatisierte Tests --> leichte Wartbarkeit...)  
Continuous Integration / Continuous Deployment ist sauber automatisiert (z.B. via GitHub Actions)  
Die Lernerfahrungen der einzelnen Gruppen wurden sauber dokumentiert (z.B. in einer learnings.md Datei)  
Die Technologieentscheidungen der einzelnen Gruppen wurden sauber dokumentiert (z.B. in einer technology-decisions.md Datei)  
Jedes Teammitglied hat erfolgreich zum Projekt beigetragen (e.g. erkennbar an der Commit Historie...)  

## Umsetzung von Feedbacks
Die Feedbacks, welche ich im Laufe der Semester zu den einzelnen Projekten gegeben habe, wurden von den Studierenden ausdauernd aufgegriffen, geprüft und reflektiert. Diese Feedbacks führten fast immer zu sehr zeitnahen Optimierungen bzw. Ergänzungen innerhalb der jeweiligen Repositories. 



## Abschlussbewertung & Offen gebliebene Punkte
### Gang of Fork
Bei der Abschlussbewertung bin ich durch die unterschiedlichen Repositories gegangen. Das war in Ordnung für mich, da ich die Zusammenhänge zwischen den einzelnen Repositories kenne. Für jemanden, der diese Zusammenhänge nicht kennt und auch für Euch wenn ihr in ein paar Jahren ab und zu mal wieder draufschaut, sowie für mögliche Contributors wäre es m.E. hilfreich einen vollständigen Single Point of Entry zu haben. https://github.com/gang-of-fork/p2p-marketplace-doku bzw. das wiki dahinter (https://github.com/gang-of-fork/p2p-marketplace-doku/wiki/Anforderungsanalyse#value-proposition-canvas...) ist nur bedingt ein guter Einstiegspunkt, da ich z.B. darüber nicht die Links zu den deployten Apps... finden konnte.  

Ich empfehle zusätzlich die Veröffentlichung von Teilen der Präsentationsvideos (welche ihr mir per Telegram gesendet habt) bei rumble.com oder youtube, um möglichen Nutzern und Contributors den Einstieg zu erleichtern.

Bei der [Plantexchange App](https://plantexchange.gang-of-fork.de/) sind mir auch aktuell einige Unregelmäßigkeiten aufgefallen - z.B. beim Login via Metamask vs. Brave Browser. Die In-App Guidance für den User ist suboptimal. Das ist sicherlich dem geschuldet, dass ihr euch im 6. Semester eher auf den OData Parser ... konzentriert habt. 

Die OData Parser Story sowie z.B. dessen Testautomatisierung hat mich geflasht!!! Super. Die Entwicklung mobiler Applikationen wird m.E. stets feingranularer und mit mehr und mehr Open Source Komponenten wahrscheinlich immer effizienter. Dazu habt ihr mit dem OData Parser Projekt m.E. einen super Beitrag geleistet.

Insgesamt könnt ihr Euch angewöhnen viel mehr Links in den einzelnen README Dateien / Wiki Pages etc. anzugeben, um eine klare "Forward Navigation" zu bieten. Auch READMEs werden normalerweise öfter gelesen als geschrieben :) --> Geht möglichst wertschätzend mit der Zeit Eurer Leser um und bietet einen klaren Pfad der Erkenntnis + Education. 



### Decentralized Chat App
Da wir die einzelnen Bewertungskriterien bei Euch sehr häufig gemeinsam durchgegangen sind, scheint mir an dieser Stelle nichts mehr groß hinzuzufügen. Toll dass ihr trotz der vielen web3 spezifischen Tool Challenges am Ball geblieben seid. Ich würde mich freuen wenn wir dem Thema Deployment auf Polygon und oder Arbitrum weiter nachgehen, um die Decentralized Chatapp kostengünstig produktiv nutzbar zu machen. 
Euren Umgang mit den vielen Challenges mit den Testnets lasse ich zusätzlich positiv in die Bewertung einfließen.  
https://polygonscan.com/tx/0x7bba1e639bd1e216039e353a29420e0e36dcafd5a7b0cc40389d0a828d8ac94c sollte eigentlich den ChatApp Smart Contract korrekt auf Polygon deployed haben. ... Hier können wir vielleicht bei Gelegenheit weiterforschen.


Auch bei Euch ist m.E. der "Single Point of Entry" / bzw. die "Forward Navigation" (z.B. via https://github.com/App-Entwicklung/Pruefungsleistung) optimierungsfähig. So wäre z.B. von hier aus https://github.com/App-Entwicklung/Pruefungsleistung/blob/main/svelte_documentation.md beispielsweise ein Link zur deployten App oder eine Beschreibung wie ein möglicher contributor das frontend lokal startet hilfreich. Für die Flutter App habt ihr das gut gemacht (siehe https://github.com/App-Entwicklung/Pruefungsleistung/blob/main/flutter_documentation.md). Gleichzeitig weiß ich dass die svelte app nur ein workaround war weil flutter zumindest im aktuellen Zustand nicht web3 ready ist.


### Allgemein
Das Interesse, die Begeisterung und die Überzeugung seitens der Studierenden an wertvollen Projekten (mit nach bestem Wissen und Gewissen den am besten passenden Werkzeugen) zu arbeiten hat dazu geführt dass den Projekten sehr viel mehr Zeit geschenkt wurde als dies laut Stundenplan der Studierenden erwartbar gewesen wäre. 
Selbst bei sehr differenzierter und kritischer Herangehensweise bei der Bewertung der Artefakte kann ich daher nicht anders als die folgenden sehr guten Noten zu geben. 


### Projekt- / Linksammlung
| Name | Projektsammlung | Vorläufige Anzahl Punkte | 
| ---- | ---- | ---- |
| Fynn Weyrich  | https://github.com/gang-of-fork | 116 (1,2) |
| Robin Reyer  | https://github.com/gang-of-fork | 116 (1,2) |
| Steffen Huels  | https://github.com/gang-of-fork | 116 (1,2) |
| Maik Kebernik  | https://github.com/gang-of-fork | 116 (1,2) |
| Patrick Vollstedt  | https://github.com/App-Entwicklung | 118 (1,1) |
| Florian Hase  | https://github.com/App-Entwicklung | 118 (1,1) |
| Rebekka Miguez  | https://github.com/App-Entwicklung | 118 (1,1) |
| Matthias Biermanns  | https://github.com/App-Entwicklung | 118 (1,1) |


## Genutzte Notenskala
https://github.com/michael-spengler/DHBW-Wissenschaftliche-Arbeiten/blob/main/Punkte-Noten-Tabelle%202022.pdf

## Empfehlung bzw. Reminder für die Zukunft
Da viele der konkreten Technologien dynamisch im Zeitablauf durch andere Technologien (Plattformen, Frameworks, Laufzeitumgebungen, ...) ersetzt werden, empfehle ich stets weiterhin das Thema **Design for Flexibility** hochzuhalten. Hierbei kann es helfen Artefakte extrem modular (Beispiele siehe u.A. https://deno.land gute 3rd Party Modules...) zu gestalten und bereitzustellen um die einzelnen Module bei Bedarf leicht auszutauschen / wiederzuverwenden. 
Ich spreche diesen Punkt hier so ausdrücklich an weil dieser in der Praxis genauso wie die Testautomatisierung häufig links liegen gelassen wird. Bei der Testautomatisierung weiß es m.E. schon jeder, dass es lediglich an Disziplin fehlt. Zum Punkt der Testautomatisierung ist der [OData Parser](https://github.com/gang-of-fork/odatafy-parser/blob/dev/test/parsing/topParser.test.ts) der Gang of Fork m.E. eines der vorbildlichsten Projekte.

## Danke
Herzlichen Dank an alle Beteiligten. Ihr wart einer meiner Top 2 Lieblingskurse in meiner bisherigen DHBW Karriere. 

