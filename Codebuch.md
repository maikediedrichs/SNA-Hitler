<h1> Netzwerkanalyse Unterstützungsnetzwerk Hitler - Codebuch </h1>

<b> Edgelist: </b> <br>
<i> from </i> <br>
definiert den Sender. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort. <br>
<i> to </i>  	<br>
definiert den Sender. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort. <br>

<i> weight </i>  	<br>
beschreibt die Art der Unterstützung.<br>
11 = finanzielle Unterstützung <br>
12 = Kontaktvermittlung <br>
13 = gesellschaftliche & persönliche Bildung <br>
14 = militärische Unterstützung <br>
15 = indirekte Hilfe durch Berufsausübung <br>
16 = politische Hilfe <br>
17 = Kontaktvermittlung + gesellschaftliche & persönliche Bildung <br>
18 = finanzielle Unterstützung + pol. Hilfe <br>
20 = finanzielle U. + Kontaktvermittlung <br>
21 = finanzielle U. + gesellsch. & pers. Bildung <br>
22 =militärische U.+ pol. Hilfe <br>
23 = juristische Hilfe <br>
24 = direkte Unterstützung als Mitarbeiter Hitlers im gelernten Beruf<br>
99 = NA <br>

<i> relation </i>  	<br>
beschreibt die Art der Beziehung.<br>
1 = persönliche Beziehung<br>
2 = Verbundenheit durch gleiche Ideologie und Ziele<br>
3 = oberflächliche Arbeitsbeziehung aus Pflicht durch äußere Einflüsse<br>
4 = Zweckbeziehung zum Eigennutz <br>
5 = finanzielle Unterstützung<br>
6 = Mitglied o. Teilnahme <br>
7 = hat eine Verbindung mir <br>

<i> start </i>  	<br>
definiert den Zeitpunkt, zu dem eine Beziehung zwischen zwei Knoten begonnen hat (Jahreszahl).
Beziehungen, die vor dem Jahr 1919 bereits bestanden, werden ebenfalls mit 1919 angegeben.<br>

<i> end </i>  	<br>
definiert den Zeitpunkt, zu dem eine Beziehung zwischen zwei Knoten geendet hat (Jahreszahl). Beziehungen, die noch nach dem Jahr 1939 bestanden, werden ebenfalls mit 1939 angegeben.<br>

<i> time </i>  	<br>
definiert den Beginn der Beziehungen skaliert nach den Wahlperioden in der Weimarer Republik bis zur Ernennung Hitlers zum Reichskanzler. <br>
10 = Januar 1919 - Juni 1920<br>
11 = Juni 1920 - Mai 1924<br>
12 = Mai 1924 - Dezember 1924<br>
13 = Dezember 1924 - Mai 1928<br>
14 = Mai 1928 - September 1930<br>
15 = September 1930 - Juli 1932<br>
16 = Juli 1932 - November 1932<br>
17 = ab November 1932<br>
18 = Genauer Zeitpunkt unbekannt, entstand aber vor der Neugründung der NSDAP 1925 <br>
99 = NA <br>

<b> Nodelist: </b> <br>
<i> id </i> <br>	eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird. <br>

<i> name </i> <br>	Name oder Bezeichnung des Knotens <br>

<i> sex </i>
1 = male<br>
2 = female<br>
3 = kein Geschlecht, da Organisation <br>
9 = NA <br>

<i> background </i>	<br> definiert das primäre Arbeitsfeld des Knotens.<br>
1 = Politik<br>
2 = Wirtschaft<br>
3 = Militär<br>
4 = Andere<br>

<i> type </i><br>	definiert, um welche Art von Knoten es sich handelt.<br>
1 = Person<br>
2 = Organisation<br>
3 = Station in Hitlers Leben <br>

<i> place </i> <br>
beschreibt den Wohnort zur Zeit der Unterstützung.<br>
1 = München <br>
2 = Berlin<br>
3 = Preussen<br>
4 = Bayern<br>
5 = Württemberg<br>
6 = Thüringen<br>
7 = Böhmen<br>
8 = Baden<br>
10 = Hessen<br>
11 = Wien<br>
9 = NA<br>
