<h1> Netzwerkanalyse Unterstützungsnetzwerk Hitler - Codebuch </h1>

<b> Edgelist: </b> <br>
<i> from </i> <br>
definiert den Sender. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort. <br>
<i> to </i>  	<br>
definiert den Sender. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort. <br>

<i> weight </i>  	<br>
Ausprägung der Kantenstärke (Beziehungsstärke), definiert nach vorgegeben Skalen.<br>
1 = indirekte Unterstützung<br>
2 = passive Wegebnung/Hilfe<br>
3 = aktive Wegebnung/Hilfe<br>

<i> relation </i>  	<br>
beschreibt die Art der Beziehung.<br>
1 = persönliche Beziehung<br>
2 = Verbundenheit durch gleiche Ideologie und Ziele<br>
3 = oberflächliche Arbeitsbeziehung aus Pflicht durch äußere Einflüsse<br>
4 = Zweckbeziehung zum Eigennutz <br>
5 = finanzielle Unterstützung<br>
6 = Mitglied<br>

<i> start </i>  	<br>
definiert den Zeitpunkt, zu dem eine Beziehung zwischen zwei Knoten begonnen hat (Jahreszahl).
Beziehungen, die vor dem Jahr 1919 bereits bestanden, werden ebenfalls mit 1919 angegeben.<br>

<i> end </i>  	<br>
definiert den Zeitpunkt, zu dem eine Beziehung zwischen zwei Knoten geendet hat (Jahreszahl). Beziehungen, die noch nach dem Jahr 1939 bestanden, werden ebenfalls mit 1939 angegeben.<br>

<i> time </i>  	<br>
definiert den Beginn der Beziehungen skaliert nach den Wahlperioden in der Weimarer Republik bis zur Ernennung Hitlers zum Reichskanzler. <br>
1 = Januar 1919 - Juni 1920<br>
2 = Juni 1920 - Mai 1924<br>
3 = Mai 1924 - Dezember 1924<br>
4 = Dezember 1924 - Mai 1928<br>
5 = Mai 1928 - September 1930<br>
6 = September 1930 - Juli 1932<br>
7 = Juli 1932 - November 1932<br>
8 = ab November 1932<br>

<b> Nodelist: </b> <br>
<i> id </i> <br>	eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird. <br>

<i> name </i> <br>	Name oder Bezeichnung des Knotens <br>

<i> sex </i>	<br> Geschlecht des Knotens; <br>
dichotome Ausprägung:<br>
1 = male,<br>
2 = female<br>

<i> background </i>	<br> definiert das primäre Arbeitsfeld des Knotens.<br>
1 = Politik<br>
2 = Wirtschaft<br>
3 = Militär<br>
4 = Andere<br>

<i> type </i><br>	definiert, um welche Art von Knoten es sich handelt.<br>
1 = Person<br>
2 = Organisation<br>
