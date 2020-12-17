

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________reife\_00_________________________________________\_
-----------------------------------------------------------

tc: IF wave=4 OR wave=5

vn:

qt:

hl:

in:

q: Zwischenseite Schulabschluss

is:

it:

ao:

mv:

ka:

vc:[Zwischenseite_3] visible if wave=4 OR wave=5

av:

kh:

fv:

hv:

fo:

tr: 

GOTO reife\_01

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________reife\_01_________________________________________\_
-----------------------------------------------------------

tc:

vn: reifeart\_183b/ sf\_reifeart\_183b

qt: Einfachauswahl mit vertikaler ao

hl:

in:

q: Bitte geben Sie die Art der Hochschulreife an.

is:

it:

ao1:1: allgemeine Hochschulreife

ao2:2: fachgebundene Hochschulreife

ao3:3: Fachhochschulreife

ao4:4: fachgebundene (einschl. landesgebundene)

Fachhochschulreife

ao5:5: schulischer Teil der Fachhochschulreife

mv:

ka:

vc:

av:

kh:

fv: sf\_reifeart\_183b: Für den weiteren Fragebogenverlauf

und die Auswertung der Daten ist es wichtig, dass Sie die

Frage beantworten. Ich möchte diese Frage dennoch nicht

beantworten.

hv:

fo:

tr: 

GOTO reife\_02 IF reifeart\_183b=5



GOTO reife\_03 IF reifeart\_183b=1 OR reifeart\_183b=2 OR

reifeart\_183b=3 OR reifeart\_183b=4



GOTO reife\_03 IF (reifeart\_183b=MISSING OR

sf\_reifeart\_183b=1)

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________reife\_02_________________________________________\_
-----------------------------------------------------------

tc:

vn: bevor\_183b

qt: Einfachauswahl mit vertikalen ao

hl:

in:

q: Für Personen mit schulischem Teil der

Fachhochschulreife: Haben Sie ein Praktikum oder eine

Berufsausbildung zur Erlangung der vollen

Fachhochschulreife absolviert?

is:

it:

ao1: ja, ich habe das Praktikum/die Berufsausbildung zur

Erlangung der vollen Fachhochschulreife bereits absolviert

ao2: ja, ich absolviere zurzeit das Praktikum/die

Berufsausbildung zur Erlangung der vollen

Fachhochschulreife

ao3: nein

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO reife\_03

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________reife\_03_________________________________________\_
-----------------------------------------------------------

tc:

vn: reifterm1\_183b/ reifterm2\_183b/ sf\_reifterm1\_183b/

sf\_reifterm2\_183b

qt: Einfachauswahl (2x Dropdown)

hl:

in:

q: Wann haben Sie diese Hochschulreife erworben?

is:

it:

ao0(reifterm1\_183b):0:Monat

ao1(reifterm1\_183b):1:Januar

ao2(reifterm1\_183b):2:Februar

ao3(reifterm1\_183b):3:März

ao4(reifterm1\_183b):4:April

ao5(reifterm1\_183b):5:Mai

ao6(reifterm1\_183b):6:Juni

ao7(reifterm1\_183b):7:Juli

ao8(reifterm1\_183b):8:August

ao9(reifterm1\_183b):9:September

ao10(reifterm1\_183b):10:Oktober

ao11(reifterm1\_183b):11:November

ao12(reifterm1\_183b):12:Dezember

ao0(reifterm2\_183b):Jahr

ao1(reifterm2\_183b):1: 2016 oder früher

ao1(reifterm2\_183b):1:2017

ao2(reifterm2\_183b):2:2018

ao3(reifterm2\_183b):2:2019

ao4(reifterm2\_183b):2:2020 oder später

mv:

ka:

vc:

av:

kh:

fv: sf\_reifterm1\_183b: Für den weiteren

Fragebogenverlauf und die Auswertung der Daten ist es

wichtig, dass Sie die Frage beantworten. Ich möchte diese

Frage dennoch nicht beantworten.

sf\_reifterm2\_183b: Für den weiteren Fragebogenverlauf

und die Auswertung der Daten ist es wichtig, dass Sie die

Frage beantworten. Ich möchte diese Frage dennoch nicht

beantworten.

hv:

fo:

tr:



GOTO reife\_04

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________reife\_04_________________________________________\_
-----------------------------------------------------------

tc:

vn: abinote\_183b/ abipkte\_183b

qt: offene Angaben

hl:

in:

q: Geben Sie bitte Ihre Abschlussnote als Note oder

Punktzahl an.

is:

it1: Zensurendurchschnitt Ihres Abschlusszeugnisses:

ao1: Note (z. B. 2,6): \[grade\]

ao2: Punktzahl (z. B. 09): \[number\]

mv:

ka:

vc:

av1: \[grade\]: 2-stellig: 0,7 to 6,0

av2: \[number\]: \<=2-stellig: 0 to 15

kh1: Bitte überprüfen Sie Ihre Eingabe und tragen Sie

einen Wert zwischen 0,7 und 6,0 ein.

kh2: Bitte überprüfen Sie Ihre Eingabe und tragen Sie

einen ganzzahligen Wert zwischen 0 und 15 ein.

fv:

hv:

fo:

tr: 

GOTO zwischen_cal_bm IF jsCheck2.value AND width2.value <=768"
GOTO zwischen_cal_bd IF jsCheck2.value AND width2.value >=768"
Goto zwischen_k IF !jsCheck2.value

hi:

