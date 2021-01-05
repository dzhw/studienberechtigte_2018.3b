

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________aus\_00_________________________________________\_
-----------------------------------------------------------

tc: IF wave=1 OR wave=2 OR wave=3 OR wave=4 OR wave=5

vn:

qt:

hl:

in:

q: Zwischenseite Berufsausbildung.

is:

it:

ao:

mv:

ka:

vc:[Zwischenseite_4] visible if wave=1 OR wave=2 OR wave=3 OR wave=4 OR wave=5

av:

kh:

fv:

hv:

fo:

tr:



GOTO aus\_01 IF h\_ausbever=0



GOTO aus\_04 IF h\_ausbever=1

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________aus\_01_________________________________________\_
-----------------------------------------------------------

tc:

vn: ausabs\_183b, sf\_ausabs\_183b

qt: Einfachauswahl mit vertikalen ao

hl:

in:

q: Beabsichtigen Sie, eine (weitere) Berufsausbildung (z. B.

Lehre) aufzunehmen?

is:

it:

ao1:1: ja, auf jeden Fall

ao2:2: ja, wahrscheinlich

ao3:3: eventuell

ao4:4: nein, wahrscheinlich nicht

ao5:5: nein, auf keinen Fall

mv:

ka:

vc:

av:

kh:

fv: sf\_ausabs\_183b: Für den weiteren Fragebogenverlauf und

die Auswertung der Daten ist es wichtig, dass Sie die Frage

beantworten.

hv:

fo:

tr: 

GOTO stu\_00 IF ausabs\_183b=4 OR ausabs\_183b=5 OR

(ausabs\_183b==MISSING AND sf\_ausabs\_183b==1)



GOTO aus\_02 IF ausabs\_183b=1 OR ausabs\_183b=2 OR

ausabs\_183b=3

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________aus\_02_________________________________________\_
-----------------------------------------------------------

tc:

vn: aubemon\_183b/ aubejahr\_183b

qt: 2x Dropdown

hl:

in:

q: Wann werden Sie diese Ausbildung aufnehmen?

is:

it:

ao0(aubemon\_183b):0:Monat

ao1(aubemon\_183b):1:Januar

ao2(aubemon\_183b):2:Februar

ao3(aubemon\_183b):3:März

ao4(aubemon\_183b):4:April

ao5(aubemon\_183b):5:Mai

ao6(aubemon\_183b):6:Juni

ao7(aubemon\_183b):7:Juli

ao8(aubemon\_183b):8:August

ao9(aubemon\_183b):9:September

ao10(aubemon\_183b):10:Oktober

ao11(aubemon\_183b):11:November

ao12(aubemon\_183b):12:Dezember

ao0(aubejahr\_183b):0:Jahr

ao1(aubejahr\_183b):1:2021

ao2(aubejahr\_183b):2:2022

ao3(aubejahr\_183b):3:2023

ao4(aubejahr\_183b):4:2024

ao5(aubejahr\_183b):5:oder später

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO aus\_03

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________aus\_03_________________________________________\_
-----------------------------------------------------------

tc:

vn: aube\_183b

qt: offene Frage

hl:

in:

q: Welcher Ausbildungsberuf wird dies voraussichtlich sein?

is:

it:

ao1:1: Präfix: Ausbildungsberuf: \[string\] offene Frage mit

60 Zeichen (Breite des Textfeldes=7cm)

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO stu\_00

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________aus\_04_________________________________________\_
-----------------------------------------------------------

tc: IF h\_ausbever=1

vn: auzufint\_183b/ auzuffaeh\_183b/ auzufkont\_183b/

auzufausb\_183b/ auzuflehr\_183b/ auzufprax\_183b/

auzufcha\_183b/ auzufauf\_183b/ auzufinsg\_183b

qt: Einfachauswahlmatrix mit horizontal abgetragenen ao

hl:

in:

q: Wie zufrieden sind bzw. waren Sie mit Ihrer Ausbildung

hinsichtlich ...

is:

it1: der Übereinstimmung mit Ihren Interessen?

it2: der Übereinstimmung mit Ihren Fähigkeiten?

it3: des Kontaktes zu anderen Auszubildenden?

It4: der Ausbilder(innen) im Betrieb?

It5: der Lehrer(innen) in der Schule?

It6: der Vorbereitung auf die Berufspraxis?

It7: der Arbeitsmarktchancen?

It8: der beruflichen Aufstiegsmöglichkeiten?

It9: der Ausbildung insgesamt?

ao1:1: sehr zufrieden (1)

ao2:2: (2)

ao3:3: (3)

ao4:4: (4)

ao5:5: sehr unzufrieden (5)

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO aus\_05

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________aus\_05_________________________________________\_
-----------------------------------------------------------

tc:

vn: ausbleist\_183b

qt: Einfachauswahl mit vertikalen ao

hl:

in:

q: Wie schätzen Sie persönlich Ihre Ausbildungsleistung im

Vergleich zu anderen ein?

is:

it:

ao1:1: (-5) unterdurchschnittlich

ao2:2: (-4)

ao3:3: (-3)

ao4:4: (-2)

ao5:5: (-1)

ao6:6: (0) durchschnittlich

ao7:7: (+1)

ao8:8: (+2)

ao9:9: (+3)

ao10:10: (+4)

ao11:11: (+5) überdurchschnittlich

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO stu\_00 IF (h\_ausbakt=0 OR h\_ausbakt=MISSING) OR

(h\_ausb20=0 OR h\_ausb20=MISSING) OR (h\_ausbakt=1 AND

(h\_studever=1 OR h\_studever=MISSING)) OR (h\_ausb20=1 AND

(h\_studever=1 OR h\_studever=MISSING))



GOTO aus\_06 IF (h\_ausbakt=1 AND h\_studever!=1) OR

(h\_ausb20=1 AND h\_studever!=1)

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________aus\_06_________________________________________\_
-----------------------------------------------------------

tc:

vn: llmoaus01\_183b/ llmoaus02\_183b/ llmoaus03\_183b/

llmoaus04\_183b/ llmoaus05\_183b/ llmoaus06\_183b/

llmoaus07\_183b/ llmoaus08\_183b/ llmoaus09\_183b/

llmoaus10\_183b/ llmoaus11\_183b/ llmoaus12\_183b/

llmoaus13\_183b/ llmoaus14\_183b/ llmoaus15\_183b/

llmoaus10\_183b/ llmoaus17\_183b/ llmoaus18\_183b/

llmoaus19\_183b/ llmoaus20\_183b/ llmoaus21\_183b/

llmoaus22\_183b/ llmoaus23\_183b/ llmoaus24\_183b/

llmoaus25\_183b/ llmoaus26\_183b/ llmoaus27\_183b/

llmoaus28\_183b/ llmoaus29\_183b/ llmoaus30\_183b/

llmoaus31\_183b

qt: Einfachauswahlmatrix mit horizontal abgetragenen

Antwortoptionen

hl:

in:

q: Im Folgenden möchten wir gerne wissen, worum es Ihnen in

der Ausbildung geht bzw. ging, was Ihnen also in der

Ausbildung besonders wichtig oder auch weniger wichtig ist

bzw. war.

is: In meiner Ausbildung geht es mir darum ...

st:

it1: neue Ideen zu bekommen.

it2: zu zeigen, dass ich bei einer Sache gut bin.

it3: dass andere Auszubildende nicht denken, ich sei dumm.

it4: keine schwierigen Tests oder Arbeiten zu haben.

it5: etwas Interessantes zu lernen.

it6: mich nicht zu blamieren (z. B. durch falsche Ergebnisse

oder dumme Fragen).

it7: zu Hause keine Arbeiten erledigen zu müssen.

it8: später kniffelige Probleme lösen zu können.

it9: Arbeiten besser zu schaffen als andere.

it10: dass niemand merkt, wenn ich etwas nicht verstehe.

it11: keine schwierigen Fragen oder Aufgaben lösen zu müssen.

it12: komplizierte Inhalte zu verstehen.

it13: bessere Noten oder Beurteilungen zu bekommen als andere.

it14: nicht zu zeigen, falls ich weniger schlau bin als

andere.

it15: nicht so schwer zu arbeiten.

it16: dass das Gelernte für mich Sinn ergibt.

it17: dass andere denken, dass ich klug bin.

it18: zu verbergen, wenn ich weniger weiß als andere.

it19: dass die Arbeit leicht ist.

it20: zum Nachdenken angeregt zu werden.

it21: zu zeigen, dass ich die Inhalte beherrsche.

It22: keine falschen Antworten auf Fragen der Lehrer\*innen

oder Ausbildenden zu geben.

It23: aufwendige Aufgaben nicht selber erledigen zu müssen.

It24: so viel wie möglich zu lernen.

It25: das was ich kann und weiß auch zu zeigen.

It26: nicht durch dumme Fragen aufzufallen.

It27: mit wenig Arbeit durch die Ausbildung zu kommen.

It28: ein tiefes Verständnis für die Inhalte zu erwerben.

It29: dass die anderen merken, dass ich in Tests und Prüfungen

gut abschneide.

It30: nicht zu zeigen, wenn mir eine Aufgabe schwerer fällt

als anderen.

It31: den Arbeitsaufwand stets gering zu halten.

ao1:1: stimmt genau (1)

ao2:2: (2)

ao3:3: (3)

ao4:4: (4)

ao5:5: stimmt gar nicht (5)

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO stu\_00

hi:

