Aufgabe MALIS 19.3 WPM_T9.1: Data Science / Data Librarianship / IT-Praxis

# Beschreibung von datenintensiven und datenfokussierten Aktivitäten in der Fachhochschule Südwestfalen (FHSwf)

## Einleitung
Die Fachhochschule Südwestfalen (FHSwf)- University of Applied Sciences ist eine Hochschulbildungs-Einrichtung, welche auf fünf (5) Standorte rund um NRW: Hagen, Iserlohn, Meschede, Soest und Lüdenscheid verteilt ist. Außer in dieser letzten Stadt finden die Studierenden an jedem Standort eine Fachbibliothek. Die Medienanzahl der vier Bibliotheken besteht aus 158.000 Monographien sowie 522 Zeitschriftentiteln. Des Weiteren stehen 530.000 E-Books und 4.800 elektronische Zeitschriftentitel zur Verfügung [1] . Aufgrund der aktuellen Krise blieben die drei Fachbibliotheken zwischen dem 19.03. bis 10.05. geschlossen.  Allerdings tritt in der Fachhochschule ab dem 11.05.2020 ein Rückkehrszenario in Kraft und sie werden drei Tagen in der Woche (dienstags, donnerstags und samstags) ihre Türen öffnen, um die folgenden Dienste zu leisten: die Ausleihe und die Rückgabe. Es werden nur bereits vorgemerkte oder Fernleihexemplare (die seit dem 16.03.2020 zur Abholung liegen) ausgeliehen. Der Freihandbereich bleibt gesperrt.

Um die Informationsbedürfnisse der Studenten in Lüdenscheid zu decken, gibt es eine Kooperation zwischen einem Medienlieferdienst und der Stadtbücherei. Dennoch hat jede Zweigstelle ihre Medienangebote auf die angebotenen Studiengänge angepasst. Das hat zur Folge, dass die Bibliotheken sich auch auf ein Thema fokussieren. Da diese Dienste mit Hilfe der Kommune funktionieren und die Bücherei noch geschlossen ist, werden zur Zeit keine Dienste vor Ort angeboten. 

In der Fachbibliothek Hagen gehöre ich zu Team 2 - Medienverarbeitung und Fernleihe. Meine Aufgaben in dieser Gruppe sind die Verarbeitung der Katalogisate für den Standort Meschede (ggf. für Soest) und die Bereitstellung der passiven Fernleihen für alle Standorten. Es ist bekannt, dass diese Aufgaben zu den datenintensiven und datenfokusierten Prozessen gehören. Um diese Verfahren zu erklären wird mit folgender Gliederung fortgefahren. Zuerst werden die genutzten Schnittstellen des Bibliothekskatalogs der FHSwf erläutert. An zweiter Stelle werden Bespiele gegeben, die zu diesem Prozess gehören. Zum Schluss werden Verbesserungsvorschläge präsentiert, welche die Katalogisierung vereinfachen oder nachhaltiger machen könnten.

## Schnittstellen
Die FHSwf gehört zu dem hbz Verbund. Der größte Teil der Katalogisierung und Fernleihe läuft über diese kooperative Arbeit. Deswegen werden Informationen aus der Internetseite des Verbunds zitiert.

Die hbz-Verbunddatenbank wird mit der Bibliothekssoftware Aleph der Firma Ex Libris betrieben. Die Katalogisierung in der hbz-Verbunddatenbank erfolgt mit dem Software-Client (Windows-Anwendung) der Aleph Bibliothekssysteme. In Bibliotheken mit diesen Systemen, wie ist der Fall bei der FHSwf und der Fernuniversität, kann der lokale Client für die zentrale Erschließung genutzt werden. Die Synchronisierung der Metadaten der hbz-Verbunddatenbank und der Lokalsysteme erfolgt über Online-Schnittstellen. 

Die Bestandsdaten (Exemplarnachweise) werden aus den lokalen Systemen der Verbundbibliotheken in die hbz-Verbunddatenbank hochgeladen [2].

Die Erfassung der Exemplardaten erfolgt auf zwei unterschiedliche Weisen, da es zwei unterschiedliche Klassifikationssysteme gibt: die Allgemeine Systematik für öffentliche Bibliotheken (ASB), für die Standorte Hagen und Iserlohn und die Gesamthochschulbibliothekssystematik (GHBS), welche in den Standorten Meschede und Soest angewendet wird. Eine Anleitung um ein neues Exemplar in der Fachbibliotheken hinzufügen steht auf der institutionellen Wiki [3] zur Verfügung. Diese Anleitung wurde als Grundlage für die folgende Tabelle genutzt:

|Standort       |	Hagen            |	Iserlohn      |	Meschede                  |	Soest                            |
|---------------|------------------|--------------- |----------------------------|----------------------------------|
|Präfix         |	 E/ZB- ; W ; W/IV| 	M/P-	        | * 76: Medium nicht ausleihbar  * 77: allgemeiner Bestand	 | * 80/81/ = Maschinenbau, E-Technik  * 84/85= Agrarwiss., Frühpädagogik.|
|Numerus Currens|	Manuell vergeben. Exemplarzählung durch Buchstaben. Nicht benutzte Exemplarbuchstaben: I, J, O	Automatische Vergabe.| Gleiches Vorgehen wie in Hagen | Signaturzähler "i" rechts neben dem Feld Signatur einstellen, hinter die Systematikgruppe "?" eingeben.  * Mehrfachexemplare durch +1,... kennzeichnen| Gleiches Vorgehen wie in Meschede|
|Exemplarstatus| X am Ende der Signatur = Exemplarstatus 40 (keine Ausleihe) XY am Ende der Signatur = Exemplarstatus 50 (Sonderstandort). W und W/IV: jedes 3. Ex. nicht ausleihbar|  Gleiches Vorgehen wie in Hagen   | Gerade Zahlen = 78 (für Meschede). Jedes 3. Ex. nicht ausleihbar. |86 (für Soest) = Sonderstandort|
|Aufbau der Signaturen (gilt für alle vier Fachbibliotheken)| Standortkürzel + Systemstelle + Nummerus currens + ggf. Auflage + ggf. Bandzählung + ggf. Mehrfachexemplar |

### Signaturbeispiele: 
-Hagen: E/ZB-Sak 4/1:15P
  * E/ZB =Standort Präfix
  * -Sak =Systemstelle 
  * 4/1 =Nummerus currens/Band
  * :15 =Auflage
  * P =Mehrfachexemplar (Exemplar Nummer 17)
  
-Iserlohn: M/P-Sak 6/1:15F
  * M/P =Standort Präfix
  * -Sak =Systemstelle 
  * 6/1 =Numerus currens/Band
  * :15 =Auflage 
  * F =Mehrfachexemplar (Exemplar 7)

-Meschede: 77TSE4612(11)-1+1 
  * 77 =Standort Präfix
  * TSE =Systemstelle 
  * 4612 =Numerus currens
  * (11)=Auflage
  * -1 =Band
  * +1 =Mehrfachexemplar (Exemplar 2)

-Soest: 81TSE4699(2)-1+4 
  * 81 =Standort Präfix
  * TSE =Systemstelle 
  * 4699	 =Numerus currens
  * (2) =Auflage
  * -1 =Band
  * +4 =Mehrfachexemplar (Exemplar 5)

Als Beispiel für den Standort Soest wird folgendes betrachtet und zwar *Emile oder über die Erziehung* von Jean-Jacques Rousseau. Es wurden 10 Exemplare für diese Zweigstelle erworben und ich musste zwei Felder durch Copy Paste ändern: die Signatur, 2. Signatur und die Inventarnummer. Das Ergebnis der 10 Exemplare sieht im Aleph Katalogisierungsmodul so aus [4], [5]:

Im Bereich Erfassung der Exemplardaten werden drei Optimierungsmöglichkeiten entdeckt. Die Erste ist das Feld 2.Signaturtyp. Dieses muss ausgefüllt werden, damit das Medium über KAI (das Discovery System VuFind der Fachbibliothek) durchsuchbar ist. Hier muss man die frisch erzeugte Signatur ohne den Standort Präfix  (E/ZB- ; W ; W/IV für Hagen; M/P- für Iserlohn; 76 und 77 für Meschede und 81, 82, 85 und 86 für Soest) kopieren. Mir ist es schon mal passiert, dass ich dieses Feld übersehen habe und folglich ist das Buch für den Kunden nicht findbar. Als Vorschlag würde ich empfehlen, dass die Daten nicht gespeichert werden können, bis dieses Feld mit Informationen ausgefüllt wird. Eine andere Möglichkeit wäre, den Inhalt des 2.Signaturtyp automatisch zu erzeugen mittels des vorherigen Signatur Feldes. Hiermit könnte zugleich eine automatisierte Kontrolle des Signatur Feldes erfolgen.

Der zweite Verbesserungsvorschlag betrifft das Feld Inventarnummer. Jedes Exemplar hat eine Inventarnummer und diese muss in das entsprechende Feld geschrieben werden. Bei mehreren Exemplaren fast die gleiche Nummer zu kopieren, abgesehen von den letzten zwei Ziffern, könnte eine mühsame Aufgabe sein. Eine automatische Erzeugung der Nummer wäre in diesem Fall auch erwünscht.

Die dritte Optimierungsmöglichkeit bezieht sich auf den Standort Präfix für Soest.  Da es zwei unterschiedliche Präfixe gibt, muss man überprüfen zu welcher Disziplin das Medium gehört, bevor diese Angabe mit der Systemstelle usw. in das Signatur Feld eingegeben wird. Die Vereinfachung dieses Verfahren würde mittels einer mini Datenbank erfolgen. Sie enthält die unterschiedlichen Stellen der Gesamthochschulbibliothekssystematik (GHBS), die in Soest genutzt werden, und die dazugehörigen Präfixe. Eine Anfrage in diese Datenbank würde stattfinden, bevor die Signatur für die Medien von Soest erzeugt wird. Einige Signaturen und deren Präfixe werden in der folgenden Tabelle angezeigt.

|Präfix| Signatur|
|------|---------|
|81| IIS|
|  | PZI|
|  | IGFA|
|  | AGD|
|85| IKC|
| | IEH|
| | IAZ|
| | HVH|
| | ROJ|

Das Ergebnis dieser Anfrage wird auf dem Signatur Feld angezeigt und somit die Suche in anderen Quellen vermieden. Zusammenfassend wurden in dieser Arbeit drei Optimierungsmöglichkeiten auf Ebene der Exemplardaten in Aleph Katalogisierungsmodul der FHSwf präsentiert. 

## Quellenverzeichnis

[1]: https://www4.fh-swf.de/de/home/studierende/bibliothek/beruns/allgemeines_3/index.php/ "FH-SWF Allgemeines"
[2]: https://www.hbz-nrw.de/produkte/verbunddienstleistungen/verbundsystem "HBZ Verbundsystem"
[3]: http://confluence.fhb.fh-swf.de/display/TEAM2/Lokaldaten "Wiki Fachbibliotheken FHSwf"
[4]: https://commons.wikimedia.org/wiki/File:Exemplar_Ansicht.jpg "Exemplar Ansicht"
[5]: https://commons.wikimedia.org/wiki/File:Inventar_nummer.jpg "Inverntarnummer Ansicht"

# Quellen

[1](/lRn5oAsqQZWyghSrEmVmBQ): https://www4.fh-swf.de/de/home/studierende/bibliothek/beruns/allgemeines_3/index.php/ "FH-SWF Allgemeines"

[2](/gvrfnd38TaaqT9KToARxDA): https://www.hbz-nrw.de/produkte/verbunddienstleistungen/verbundsystem "HBZ Verbundsystem"

[3](/tutPOrUDTGGM7AW8zxoJjA): http://confluence.fhb.fh-swf.de/display/TEAM2/Lokaldaten "Wiki Fachbibliotheken FHSwf"

[4](/rhiV_FL_QpWFxQUgHWdBqQ): https://commons.wikimedia.org/wiki/File:Exemplar_Ansicht.jpg "Exemplar Ansicht"

[5](/Rl66lDa3QQatD0aKO5WpOA): https://commons.wikimedia.org/wiki/File:Inventar_nummer.jpg "Inverntarnummer Ansicht"

