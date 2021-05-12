---
layout: post
title:  "A closer look at EV adoption"
date:   2022-03-25
published: false
blurb: "Test"

---


In den letzten Monaten habe ich großes Interesse an der Auswertung und Visualisierung von Daten gefunden und wollte neben meiner Arbeit und Studium, wo ich die Themen in Teilen auch betrachte, mal eine umfangreiche Auswertung von vorne bis hinten fahren. Im Lockdown habe ich etwas Zeit gehabt und mir Daten zur Elektroautoadoption angeguckt. Hierfür habe ich verschiedene Datensets [vom Kraftfahrt-Bundesamt (KBA) zu Elektroautobeständen](https://www.kba.de/DE/Statistik/Produktkatalog/produkte/Fahrzeuge/fz1_b_uebersicht.html?nn=1146130){:target="_blank"}, [von der Bundesnetzagentur zu öffentlicher Ladeinfrastruktur](https://www.bundesnetzagentur.de/DE/Sachgebiete/ElektrizitaetundGas/Unternehmen_Institutionen/HandelundVertrieb/Ladesaeulenkarte/Ladesaeulenkarte_node.html){:target="_blank"} und [vom Statistischen Bundesamt (destatis) zu verschiedenen Kreis Kennzahlen](https://www.destatis.de){:target="_blank"} ausgewertet. Ziel dieses Projekts war es für mich persönlich einmal von vorne bis hinten eine Anlayse zu fahren - von der Überlegung der Problemstellung, der Datenextraktion, der Bereinigung und Verarbeitung der Daten, der eigentlichen Analyse, der Visualisierung, dem Deployment eines interaktiven Auswertungstools und der Veröffentlichung auf einer eigenen Website. Der Fokus war der Prozess und nicht das Ergebnis. Ich habe für dieses Projekt nicht den Anspruch eine perfekte und fehlerfreie Analyse über Elektroautoadoption zu entwickeln, freue mich aber gerne über Anregungen zur Verbesserung.

Diese Analyse ist in zwei Teile geteilt: in diesem Post lege ich einen Fokus auf die Ergebnisse und in einem zweiten Post erläutere ich die technischen Details, wie die Analyse und Visualisierungen erstellt wurden. Ferner können auf dieser Website die Daten interaktiv ausgewertet werden.




Terminologie EV, BEV, HEV, PHEV

{% include figures/interactive_graph.html %}

Zuerst gilt es die verschiedenen Datensets zu finden und zu importieren. Die meisten Datensets ziehe ich einfach in dem Format wie diese publiziert wurden. Für die destatis Seiten gibt es aber eigentlich eine eigene [RESTful JSON und SOAP XML API](https://www-genesis.destatis.de/genesis/online?Menu=Webservice#abreadcrumb). Da war ich aber zu faul mich einzuarbeiten, wahrscheinlich ist dies aber eine sehr sinnvolle Sache :). 

##### FOOTNOTES

[^1]: This is a note!
