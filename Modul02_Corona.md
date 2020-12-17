

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________cor\_00_________________________________________\_
-----------------------------------------------------------

tc: IF wave=1 OR wave=2 OR wave=3 OR wave=4 OR wave=5

vn:

qt:

hl:

in:

q: Zwischenseite Corona

is:

it:

ao:

mv:

ka:

vc: [Zwischenseite_2] visible if wave=1 OR wave=2 OR wave=3 OR wave=4 OR wave=5

av:

kh:

fv:

hv:

fo:

tr: 

GOTO cor\_01

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________cor\_01_________________________________________\_
-----------------------------------------------------------

tc:

vn: dirkons1\_183b/dirkons2\_183b/dirkons3\_183b/

dirkons4\_183b

qt: Einfachauswahlmatrix mit horizontalen ao

hl:

in: Im Folgenden geht es um mögliche Auswirkungen der

Corona-Krise seit März 2020 bis heute.

q: Wie stark sind Sie persönlich durch die Corona-Krise

von folgenden Dingen betroffen?

is:

it1: Einschränkungen Ihres Lebensstandards

it2: Geldproblemen

it3: Einsamkeit

it4: Problemen bei der Vereinbarkeit von Familie und

Beruf/Ausbildung/Studium

ao1:1: sehr stark (1)

ao2:2: stark (2)

ao3:3: mittelmäßig (3)

ao4:4: kaum (4)

ao5:5: gar nicht (5)

ao6:6: trifft nicht zu \[abgesetzt darstellen\]

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO cor\_02

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________cor\_02_________________________________________\_
-----------------------------------------------------------

tc:

vn: coraus\_183b/ corstu\_183b/ corjob\_183b/

corselb\_183b/ corson1\_183b/ corson2\_183b/ corno\_183b

qt: Mehrfachauswahl mit vertikal abgetragenen

Antwortoptionen

hl:

in:

q: Und in welchen der folgenden Bereiche haben Sie durch

die Corona-Krise bislang Probleme oder Einschränkungen

erfahren?

is: Mehrfachnennung möglich. Bitte kreuzen Sie alle

zutreffenden Antworten an.

ao1: Ausbildung

ao2: Studium

ao3: Erwerbstätigkeit (nicht selbständige)

ao4: Selbständige Erwerbstätigkeit

ao5: Sonstiges, und zwar: \[string\]

ao6: in keinem dieser Bereiche \[abgesetzt darstellen\]

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:



GOTO cor\_03 IF coraus\_183b=1



GOTO cor\_04 IF coraus\_183b=0 AND corstu\_183b=1



GOTO cor\_05 IF coraus\_183b=0 AND corstu\_183b=0 AND

corjob\_183b=1



GOTO cor\_06 IF coraus\_183b=0 AND corstu\_183b=0 AND

corjob\_183b=0 AND corselb\_183b=1



GOTO cor\_07 IF coraus\_183b=0 AND corstu\_183b=0 AND

corjob\_183b=0 AND corselb\_183b=0

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________cor\_03_________________________________________\_
-----------------------------------------------------------

tc:

vn: einaus1\_183b/ einaus2\_183b/ einaus3\_183b/

einaus4\_183b/ einaus5\_183b/ einaus6\_183b/

einaus7\_183b/ einaus8\_183b/ einaus9\_183b/

einaus10\_183b/ einaus11\_183b

qt: Einfachauswahlmatrix mit horizontal abgetragenen

Antwortoptionen

hl:

in:

q: Welche Probleme oder Einschränkungen hatten Sie wegen

der Corona-Krise seit März 2020 bis heute mit Ihrer

Ausbildung?

is:

it1: Viel Unterrichtsausfall

it2: Eingeschränkte persönliche Anwesenheit in Schule

it3: Überwiegend digitaler Unterricht

it4: Betrieb wurde zeitweise geschlossen

it5: Betrieb wurde dauerhaft geschlossen

it6: Einschränkung der betrieblichen Anwesenheit

it7: Ausbildungsplatz konnte nicht angetreten werden

it8: Verzögerung des Ausbildungsstarts

it9: Ausbildung musste abgebrochen werden

it10: Sonstiges, und zwar: \[string\]

ao1:1: ja

ao2:2: nein

ao3:3: trifft nicht zu \[abgesetzt darstellen\]

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:



GOTO cor\_04 IF corstu\_183b=1



GOTO cor\_05 IF corstu\_183b=0 AND corjob\_183b=1



GOTO cor\_06 IF corstu\_183b=0 AND corjob\_183b=0 AND

corselb\_183b=1



GOTO cor\_07 IF corstu\_183b=0 AND corjob\_183b=0 AND

corselb\_183b=0

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________cor\_04_________________________________________\_
-----------------------------------------------------------

tc:

vn: einstu1\_183b/ einstu2\_183b/ einstu3\_183b/

einstu4\_183b/ einstu5\_183b/ einstu6\_183b/

einstu7\_183b/ einstu8\_183b/ einstu9\_183b/

einstu10\_183b/ einstu11\_183b/ einstu12\_183b/

einstu13\_183b

qt: Einfachauswahlmatrix mit horizontalen ao

hl:

in:

q: Welche Probleme oder Einschränkungen hatten Sie wegen

der Corona-Krise seit März 2020 bis heute mit Ihrem

Studium?

is:

It1: Reduktion des Lehrveranstaltungsangebots

It2: Totalausfall von angekündigten Lehrveranstaltungen

It3: Eingeschränkte persönliche Anwesenheit

It4: Eingeschränkte persönliche Studienberatung

It5: Überwiegend digitale Vorlesungen

It6: Überwiegend digitale Seminare und Übungen

It7: Eingeschränkte Möglichkeiten, Prüfungen abzulegen

It8: Verzögerung des Studiums

It9: Verlust des Studienplatzes

It10: Eingeschränkter Zugang zu Angeboten der Hochschule,

z. B. zu Bibliotheken oder zum Rechenzentrum

It11: Schwierigkeiten, Dozierende zu erreichen

It12: Sonstiges, und zwar: \[string\]

ao1:1: ja

ao2:2: nein

ao3:3: trifft nicht zu \[abgesetzt darstellen\]

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:



GOTO cor\_05 IF corjob\_183b=1



GOTO cor\_06 IF corjob\_183b=0 AND corselb\_183b=1



GOTO cor\_07 IF corjob\_183b=0 AND corselb\_183b=0

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________cor\_05_________________________________________\_
-----------------------------------------------------------

tc:

vn: einber1\_183b/ einber2\_183b/ einber3\_183b/

einber4\_183b/ einber5\_183b/ einber6\_183b/

einber7\_183b/ einber8\_183b/ einber9\_183b

qt: Einfachauswahlmatrix mit horizontalen aos

hl:

in:

q: Welche Probleme oder Einschränkungen hatten Sie wegen

der Corona-Krise seit März 2020 bis heute mit Ihrer

Erwerbstätigkeit?

is:.\

it1: Verlust des Arbeitsplatzes

it2: Eine (in Aussicht stehende) Stelle konnte nicht

angetreten werden

it3: Verzögerung bei der Aufnahme einer Erwerbstätigkeit

it4: Kurzarbeit

it5: Freistellung ohne Gehaltsbezug

it6: Erschwerte Arbeitsbedingungen

it7: Probleme bei der Stellensuche

it8: Sonstiges, und zwar: \[string\]

ao1: ja

ao2: nein

ao3: trifft nicht zu \[abgesetzt darstellen\]

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:



GOTO cor\_06 IF corselb\_183b=1



GOTO cor\_07 IF corselb\_183b=0

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________cor\_06_________________________________________\_
-----------------------------------------------------------

tc:

vn: corselbauf\_183b

qt: Einfachauswahl mit vertikalen ao

hl:

in:

q: **Wie hat sich seit Beginn der Corona-Krise im März

2020 Ihre Auftrags- bzw. Einkommenssituation verändert?**

is:

ao1: mehr Aufträge bzw. Einnahmen

ao2: keine Veränderung

ao3: eher weniger Aufträge bzw. Einnahmen

ao4: viel weniger Aufträge bzw. Einnahmen

ao5: gar keine Aufträge bzw. Einnahmen

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO cor\_07

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________cor\_07_________________________________________\_
-----------------------------------------------------------

tc:

vn: berzucor\_183b

qt: Einfachauswahl mit vertikalen ao

hl:

in:

q: **Denken Sie, dass sich Ihre berufliche Zukunft durch

die Corona-Krise verbessert oder verschlechtert?**

is:

ao1: stark verbessert

ao2: verbessert

ao3: gleich

ao4: verschlechtert

ao5: stark verschlechtert

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO zwischen_epi

hi:

