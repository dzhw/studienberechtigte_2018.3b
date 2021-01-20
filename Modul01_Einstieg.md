  

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________beg\_00_________________________________________\_
-----------------------------------------------------------

tc: IF wave=1 OR wave=2 OR wave=3 OR wave=4 OR wave=5

vn:

qt:

hl:

in:

q: Zwischenseite Einstieg

is:

it:

ao:

mv:

ka:

vc: [Zwischenseite_1] visible if wave=1 OR wave=2 OR wave=3 OR wave=4 OR wave=5

av:

kh:

fv:

hv:

fo:

tr: 

GOTO beg\_01

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________beg\_01_________________________________________\_
-----------------------------------------------------------

tc:

vn: bbfried\_183b

qt: Einfachauswahl mit vertikalen ao

hl:

in:

q: Wie zufrieden sind Sie mit Ihrem bisherigen Bildungs-

und Berufsweg?

is:

it:

ao1:1: (1) sehr zufrieden 

ao2:2: (2)

ao3:3: (3)

ao4:4: (4)

ao5:5: (5) sehr unzufrieden 

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO beg\_02

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________beg\_02_________________________________________\_
-----------------------------------------------------------

tc:

vn: wuber\_183b

qt: offene Frage

hl:

in:

q: Unabhängig von Ihrer aktuellen Situation, welchen Beruf

würden Sie später einmal am liebsten ergreifen?

is:

it:

ao: \[string\] offene Frage mit 60 Zeichen (Breite des

Textfeldes=7cm)

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO beg\_03

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________beg\_03_________________________________________\_
-----------------------------------------------------------

tc:

vn: planber\_183b

qt: offene Frage

hl:

in:

q: Und wenn Sie einmal an alles denken, was Sie jetzt

wissen: Welchen Beruf werden Sie wohl tatsächlich einmal

ergreifen?

is:

it:

ao: \[string\] offene Frage mit 60 Zeichen (Breite des

Textfeldes=7cm)

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO beg\_04

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________beg\_04_________________________________________\_
-----------------------------------------------------------

tc:

vn: chakaall\_183b / chabaall\_183b / chselbst\_183b

qt: Einfachauswahlmatrix mit horizontalen ao

hl:

in:

q: Wie schätzen Sie ...

is: Bitte jeweils den zutreffenden Skalenwert ankreuzen.

it1: ... allgemein die Berufsaussichten für Absolventen

eines **Studiums** ein?

it2: ... allgemein die Berufsaussichten für Absolventen

eines **beruflichen Ausbildungsweges** ohne Studium ein?

it3: ... Ihre **persönlichen Berufsaussichten** ein?

st:

ao1:1: sehr gut (1)

ao2:2: (2)

ao3:3: (3)

ao4:4: (4)

ao5:5: sehr schlecht (5)

ao6:6: weiß nicht \[abgesetzt darstellen\]

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO beg\_05

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________beg\_05_________________________________________\_
-----------------------------------------------------------

tc:

vn: simgeh3\_183b

qt: Einfachauswahl mit vertikalen ao

hl:

in:

q: Stellen Sie sich vor, Ihnen werden drei verschiedene

Jobs mit unterschiedlichem Anfangsgehalt angeboten,

welchen würden Sie wählen?

is:

it:

st:

ao1:1 den Job mit durchschnittlichem Gehalt von Beginn an

ao2:2 den Job mit geringem Gehalt in den ersten beiden

Jahren und anschließend hohem Gehalt

ao3:3 den Job mit geringem Gehalt in den ersten vier

Jahren und anschließend sehr hohem Gehalt

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO beg\_06

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________beg\_06_________________________________________\_
-----------------------------------------------------------

tc:

vn: risky\_183b

qt: Einfachauswahl mit vertikalen ao

hl:

in:

q: Wie schätzen Sie sich persönlich ein: Wie risikobereit

sind Sie im Allgemeinen?

is:

it:

ao1: (1) sehr risikobereit 

ao2: (2)

ao3: (3)

ao4: (4)

ao5: (5)

ao6: (6)

ao7: (7) gar nicht risikobereit 

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO cor\_00

hi:

