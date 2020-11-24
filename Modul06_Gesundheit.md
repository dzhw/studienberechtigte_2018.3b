

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________gsh\_00_________________________________________\_
-----------------------------------------------------------

tc: IF wave=1 OR wave=2 OR wave=3 OR wave=4 OR wave=5

vn:

qt:

hl:

in:

q: Zwischenseite Gesundheit

is:

it:

ao:

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO gsh\_01

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________gsh\_01_________________________________________\_
-----------------------------------------------------------

tc:

vn: gesund\_183b

qt: Einfachauswahl mit horizontaler ao

hl:

in:

q: Wie würden Sie Ihren Gesundheitszustand im Allgemeinen

beschreiben?

is:

it:

ao1:1: sehr gut

ao2:2: gut

ao3:3: mittelmäßig

ao4:4: schlecht

ao5:5: sehr schlecht

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO gsh\_02

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________gsh\_02_________________________________________\_
-----------------------------------------------------------

tc:

vn: pss01\_183b, pss02\_183b, pss03\_183b, pss04\_183b,

pss05\_183b, pss06\_183b, pss07\_183b, pss08\_183b,

pss09\_183b, pss10\_183b

qt: Einfachauswahlmatrix mit horizontalen ao

hl:

in: Die folgenden Fragen beschäftigen sich damit, wie

häufig Sie sich während des letzten Monats durch Stress

belastet fühlten.

q: Wie oft hatten/haben Sie (sich) im letzten Monat \...

is:

It1: \... darüber aufgeregt, dass etwas völlig

Unerwartetes eingetreten ist?

It2: \... das Gefühl, wichtige Dinge in Ihrem Leben nicht

beeinflussen zu können?

It3: \... nervös und gestresst gefühlt?

It4: \... sicher im Umgang mit persönlichen Aufgaben und

Problemen gefühlt?

It5: \... das Gefühl, dass sich die Dinge nach Ihren

Vorstellungen entwickeln?

It6: \... das Gefühl, mit all den anstehenden Aufgaben und

Problemen nicht richtig umgehen zu können?

It7: \... das Gefühl, mit Ärger in Ihrem Leben klar zu

kommen?

It8: \... das Gefühl, alles im Griff zu haben?

It9: \... darüber geärgert, wichtige Dinge nicht

beeinflussen zu können?

it10: \... das Gefühl, dass sich die Probleme so

aufgestaut haben, dass Sie diese nicht mehr bewältigen

können?

ao1:1: sehr oft (1)

ao2:2: (2)

ao3:3: (3)

ao4:4: (4)

ao5:5: nie (5)

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO gsh\_03

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________gsh\_03_________________________________________\_
-----------------------------------------------------------

tc:

vn: kgsndtag\_183b

qt: offene Frage

hl:

in:

q: Bitte denken Sie an Ihre körperliche Gesundheit - dazu

zählen körperliche Krankheiten und Verletzungen. An wie

vielen Tagen der letzten vier Wochen ging es Ihnen

körperlich nicht gut?

is:

it:

ao: Tage: \[number\]

mv:

ka:

vc:

av: \[number\]: 2-stellig: 0 TO 28

kh: Bitte tragen Sie eine Zahl zwischen 0 und 28 ein.

fv:

hv:

fo:

tr: 

GOTO gsh\_04

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________gsh\_04_________________________________________\_
-----------------------------------------------------------

tc:

vn: sgsndtag\_183b

qt: Offene Abfrage

hl:

in:

q: Bitte denken Sie an Ihr seelisches Befinden - dazu

zählen auch Stress, Depressionen oder Ihre Stimmung ganz

allgemein. An wie vielen Tagen der letzten vier Wochen

ging es Ihnen seelisch nicht gut?

is:

it:

ao: Tage: \[number\]

mv:

ka:

vc:

av: \[number\]: 2-stellig: 0 TO 28

kh: Bitte tragen Sie eine Zahl zwischen 0 und 28 ein.

fv:

hv:

fo:

tr: 

GOTO gsh\_05

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------

\__________________________________________gsh\_05_________________________________________\_
-----------------------------------------------------------

tc:

vn: gsndtag\_183b

qt: Offene Abfrage

hl:

in:

q: An wie vielen Tagen der letzten vier Wochen waren Sie

durch Ihre körperliche Gesundheit oder Ihr seelisches

Befinden in der Ausübung alltäglicher Aktivitäten - wie

Berufstätigkeit, Ausbildung, Studium, Versorgung, Erholung

oder Pflege sozialer Kontakte - beeinträchtigt?

is:

it:

ao: Tage: \[number\]

mv:

ka:

vc:

av: \[number\], 2-stellig: 0 TO 28

kh: Bitte tragen Sie eine Zahl zwischen 0 und 28 ein.

fv:

hv:

fo:

tr: 

GOTO msg\_00

hi:

