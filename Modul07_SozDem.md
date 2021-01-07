

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_00_________________________________________\_
-----------------------------------------------------------

tc: IF wave=1 OR wave=2 OR wave=3 OR wave=4 OR wave=5

vn:

qt:

hl:

in:

q: Zwischenseite Soziodemographie

is:

it:

ao:

mv:

ka:

vc:[Zwischenseite_7] visible if wave=1 OR wave=2 OR wave=3 OR wave=4 OR wave=5

av:

kh:

fv:

hv:

fo:

tr: 

GOTO msg\_01

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_01_________________________________________\_
-----------------------------------------------------------

tc:

vn: slburt01\_183b/ slburt02\_183b/ slburt03\_183b

qt: Einfachauswahlmatrix mit horizontalen ao

hl:

in:

q: Die folgenden Aussagen können mehr oder weniger auf Sie

zutreffen. Bitte geben Sie bei jeder Aussage an, inwieweit

diese auf Sie persönlich zutrifft.

is:

it1: In schwierigen Situationen kann ich mich auf meine

Fähigkeiten verlassen.

it2: Die meisten Probleme kann ich aus eigener Kraft gut

meistern.

it3: Auch anstrengende und komplizierte Aufgaben kann ich

in der Regel gut lösen.

st:

ao1:1: trifft voll und ganz zu (1)

ao2:2: (2)

ao3:3: (3)

ao4:4: (4)

ao5:5: trifft gar nicht zu (5)

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:



GOTO msg\_02

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_02_________________________________________\_
-----------------------------------------------------------

tc:

vn: fairy\_183b

qt: Einfachauswahl mit vertikalen ao

hl:

in:

q: Nun geht es um Ihre Meinung: Inwiefern verhalten sich

andere Menschen im Allgemeinen fair?

is:

it:

ao1:1: (1) Menschen verhalten sich im Allgemeinen nicht fair 

ao2:2: (2)

ao3:3: (3)

ao4:4: (4)

ao5:5: (5)

ao6:6: (6)

ao7:7: (7)

ao8:8: (8)

ao9:9: (9)

ao10:10: (10)

ao11:11: (11) Menschen verhalten sich im Allgemeinen fair 

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr:



GOTO msg\_03

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_03_________________________________________\_
-----------------------------------------------------------

tc:

vn: menver\_183b

qt: Einfachauswahl mit vertikalen ao

hl:

in:

q: Inwiefern kann man anderen Menschen im Allgemeinen vertrauen?

is:

it:

ao1:1: (1) man kann im Allgemeinen nicht vertrauen 

ao2:2: (2)

ao3:3: (3)

ao4:4: (4)

ao5:5: (5)

ao6:6: (6)

ao7:7: (7)

ao8:8: (8)

ao9:9: (9)

ao10:10: (10)

ao11:11: (11) man kann im Allgemeinen vertrauen 

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO msg\_04

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_04_________________________________________\_
-----------------------------------------------------------

tc:

vn: pereig01\_183b/ pereig02\_183b/ pereig03\_183b/

pereig04\_183b/ pereig05\_183b/ pereig06\_183b/

pereig07\_183b/ pereig08\_183b/ pereig09\_183b/

pereig10\_183b/ pereig11\_183b/ pereig12\_183b/

pereig13\_183b/ pereig14\_183b/ pereig15\_183b

qt: Einfachauswahlmatrix mit horizontalen ao

hl:

q1: Die eigenen Entscheidungen werden durch die

Persönlichkeitseigenschaften beeinflusst. Inwieweit

treffen die folgenden Aussagen auf Sie zu?

is: Bitte jeweils den zutreffenden Skalenwert ankreuzen.

q2: Ich bin jemand, der ...


it1: ... gründlich arbeitet.

it2: ... kommunikativ, gesprächig ist.

it3: ... manchmal etwas grob zu anderen ist.

it4: ... originell ist, neue Ideen einbringt.

it5: ... sich oft Sorgen macht.

it6: ... zurückhaltend ist.

It7: ... verzeihen kann.

It8: ... eher faul ist.

It9: ... aus sich herausgehen kann, gesellig ist.

It10: ... künstlerische Erfahrungen schätzt.

It11: ... leicht nervös wird.

It12: ... Aufgaben wirksam und effizient erledigt.

It13: ... rücksichtsvoll und freundlich mit anderen

umgeht.

It14: ... eine lebhafte Phantasie, Vorstellung hat.

It15: ... entspannt ist, mit Stress gut umgehen kann.

st:

ao1:1: trifft voll zu (1)

ao2:2: (2)

ao3:3: (3)

ao4:4: (4)

ao5:5: (5)

ao6:6: (6)

ao7:7: trifft überhaupt nicht zu (7)

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO msg\_05 IF wave=1 OR wave=2 OR wave=3



GOTO msg\_06 IF wave=4 OR wave=5

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_05_________________________________________\_
-----------------------------------------------------------

tc:

vn: epist01\_183b/ epist03\_183b/ epist04\_183b/

epist05\_183b/ epist06\_183b/ epist07\_183b/

epist08\_183b/ epist09\_183b/ epist10\_183b/

epist11\_183b/ epist12\_183b/

qt: Einfachauswahlmatrix mit horizontalen ao

hl:

in:

q: Wie sehr stimmen Sie mit den folgenden Aussagen zu

Wissen und Wissenschaft überein?

is:

it1: Wissen entwickelt sich weiter, wenn man sich kritisch

damit auseinander setzt.

it2: Wissenschaftler(innen) können letztendlich zur

Wahrheit kommen.

it3: Durch neue Erkenntnisse wird häufig das bisherige

Wissen in Frage gestellt.

it4: Durch die Beschäftigung mit neuen Wissensinhalten

erscheinen bekannte Wissensinhalte oft in einem ganz

anderen Licht.

it5: In der Wissenschaft werden verschiedene Phänomene der

Welt objektiv erklärt.

it6: Die Kernaussagen in der Wissenschaft sind in hohem

Maße objektiv.

It7: Es gibt unumstößliche Wahrheiten.

It8: In der Wissenschaft gibt es einen festen Kern von

Wissen.

It9: Nach intensivem Nachdenken sieht man Probleme oft mit

anderen Augen.

It10: Wissenschaftliche Forschung zeigt, dass es auf die

meisten Probleme eine richtige Antwort gibt.

It11: Die Beurteilung von Wissen verändert sich mit neuen

Erfahrungen.

st:

ao1:1: stimme voll und ganz zu (1)

ao2:2: (2)

ao3:3: (3)

ao4:4: (4)

ao5:5: (5)

ao6:6: stimme überhaupt nicht zu (6)

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO msg\_06

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_06_________________________________________\_
-----------------------------------------------------------

tc:

vn: finsistu\_183b/finsiaus\_183b/ finsile\_183b

qt: Einfachauswahl mit vertikaler ao

hl:

in:

q: Inwieweit trifft die nachfolgende Aussage auf Ihre

finanzielle Situation zu?

is:

it1: Die Finanzierung meines Lebensunterhaltes ist bis zu

meinem Studienabschluss sichergestellt.

it2: Die Finanzierung meines Lebensunterhaltes ist bis zu

meinem Ausbildungsabschluss sichergestellt.

it3: Die Finanzierung meines Lebensunterhaltes ist

sichergestellt.

ao1:1: trifft voll und ganz zu (1)

ao2:2: (2)

ao3:3: (3)

ao4:4: (4)

ao5:5: trifft gar nicht zu (5)

mv:

ka:

vc:

SHOW it1 IF h\_studakt=1

SHOW it2 IF h\_ausbakt=1

SHOW it3 IF h\_ausbakt=0 AND h\_studakt=0

av:

kh:

fv:

hv:

fo:

tr: 

GOTO msg\_07

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_07_________________________________________\_
-----------------------------------------------------------

tc:

vn: wohnelt\_183b

qt: Einfachauswahl, vertikale ao

hl:

in:

q: Leben Sie im Haushalt Ihrer Eltern?

is:

st:

it:

ao1:1: ja

ao2:2: nein

mv:

ka:

vc:

av1:

av2:

kh1:

kh2:

fv:

hv:

fo:

tr:



GOTO msg\_08 IF wohnelt\_183b==2



GOTO msg\_09 IF (wohnelt\_183b ==1 OR wohnelt\_183b ==MISSING)

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_08_________________________________________\_
-----------------------------------------------------------

tc:

vn: auszmon\_183b, auszjahr\_183b,

qt: 2x Dropdown

hl:

in:

q: Seit wann leben Sie nicht mehr im Haushalt Ihrer Eltern?

is:

st:

it:

ao0(auszmon\_183b):0:Monat

ao1(auszmon\_183b):1:Januar

ao2(auszmon\_183b):2:Februar

ao3(auszmon\_183b):3:März

ao4(auszmon\_183b):4:April

ao5(auszmon\_183b):5:Mai

ao6(auszmon\_183b):6:Juni

ao7(auszmon\_183b):7:Juli

ao8(auszmon\_183b):8:August

ao9(auszmon\_183b):9:September

ao10(auszmon\_183b):10:Oktober

ao11(auszmon\_183b):11:November

ao12(auszmon\_183b):12:Dezember

ao0(auszjahr\_183b):0:Jahr

ao1(auszjahr\_183b):1:2000 oder früher

ao2(auszjahr\_183b):2:2001

ao3(auszjahr\_183b):3:2002

ao4(auszjahr\_183b):4:2003

ao5(auszjahr\_183b):5:2004

ao6(auszjahr\_183b):6:2005

ao7(auszjahr\_183b):7:2006

ao8(auszjahr\_183b):8:2007

ao9(auszjahr\_183b):9:2008

ao10(auszjahr\_183b):10:2009

ao11(auszjahr\_183b):11:2010

ao12(auszjahr\_183b):12:2011

ao13(auszjahr\_183b):13:2012

ao14(auszjahr\_183b):14:2013

ao15(auszjahr\_183b):15:2014

ao16(auszjahr\_183b):16:2015

ao17(auszjahr\_183b):17:2016

ao18(auszjahr\_183b):18:2017

ao19(auszjahr\_183b):19:2018

ao20(auszjahr\_183b):20:2019

ao21(auszjahr\_183b):21:2020

ao22(auszjahr\_183b):22:2021

mv:

ka:

vc:

av1:

av2:

kh: Bitte überprüfen Sie Ihre Eingabe. Sie haben ein Datum

eingegeben, das in der Zukunft liegt.

fv:

hv:

fo:

tr: 

GOTO msg\_09

hi: Wir möchten hier 2 Dropdown-Menüs für Monat bzw. Jahr

haben. Beim Monat soll \"Januar\" bis \"Dezember\" angezeigt

werden, dahinter liegen aber numerische Werte (1-12).

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_09_________________________________________\_
-----------------------------------------------------------

tc:

vn: wohn\_183b, woort\_183b, woplz\_183b, woaland\_183b,

woaort\_183b

qt: Einfachauswahl (vertikal) + offene Angaben

hl:

in:

q1: Bitte geben Sie Ihren Wohnort an.

is:

st:

it:

ao1: 1:1: in Deutschland: Ort: \[string\] PLZ: \[number\]

ao2: 2:2: nicht in Deutschland, sondern: Land: \[string\] Ort:

\[string\]

mv:

ka:

vc:

av: woplz\_183b: \[number\]: 5-stellig, 10000 TO 99999

kh: Bitte geben Sie eine 5-stellige Postleitzahl an.

fv:

hv:

fo:

tr: 

GOTO msg\_10 IF wave=2 OR wave= 3 OR wave=4 OR wave=5



GOTO msg\_11 IF wave=1

hi: Rangecheck für Variable plz einfügen: maxLength=\"5\"

maxValue=\"99999\" minValue=\"1000\". Infield-Einblendungen

für alle vier Textfelder: \"Ort\", \"PLZ\", \"Land\", \"Ort\"

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_10_________________________________________\_
-----------------------------------------------------------

tc:

vn: geschl\_183b

qt: Einfachauswahl, vertikale ao

hl:

in:

q: Welches Geschlecht haben Sie?

is:

st:

it:

ao1:1: männlich

ao2:2: weiblich

ao3:3: divers

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO msg\_11

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_11_________________________________________\_
-----------------------------------------------------------

tc:

vn: bezstand\_183b

qt: Einfachauswahl, vertikale ao

hl:

in:

q: Sind Sie in einer festen Partnerschaft?

is:

st:

it:

ao1:1: ja, in fester Partnerschaft

ao2:2: ja, verheiratet oder in eingetragener Lebenspartnerschaft

ao3:3: nein, ich bin ohne feste(n) Partner(in)

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO msg\_13 IF bezstand\_183b =MISSING OR bezstand\_183b =3



GOTO msg\_12 IF bezstand\_183b =1 OR bezstand\_183b =2

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_12_________________________________________\_
-----------------------------------------------------------

tc:

vn: famhsh\_183b

qt: Einfachauswahl, vertikale ao

hl:

in:

q: Leben Sie mit Ihrem/Ihrer Partner(in) in einem gemeinsamen

Haushalt?

is:

st:

it:

ao1:1: ja, wir haben einen gemeinsamen Haushalt

ao2:2: ja, aber neben dem gemeinsamen Haushalt führen ich bzw.

mein(e) Partner(in) einen zweiten Haushalt (z. B. wegen

Erwerbstätigkeit in anderer Stadt)

ao3:3: nein

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO msg\_13

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_13_________________________________________\_
-----------------------------------------------------------

tc:

vn: kinder\_183b, kinderanz\_183b

qt: Einfachauswahl, vertikale ao mit offener Antwortoption

hl:

in:

q: Haben Sie Kinder?

is:

st:

it:

ao1:1: ja, und zwar: \[number\] Kinder (kinderanz\_183b)

ao2:2: nein

mv:

ka:

vc:

av: \[number\]: soft Rangecheck 0 TO 9

kh: Bitte überprüfen Sie Ihre Eingabe. Sie haben einen Wert

kleiner 0 oder größer 9 eingegeben. Wenn Ihre Angabe korrekt

ist, können Sie diesen Hinweis ignorieren.

fv:

hv:

fo:

tr:



GOTO msg\_14 IF kinder\_183b=1 OR kinderanz\_183!=MISSING



GOTO msg\_15 IF (kinder\_183b=2 OR kindanz\_183b=MISSING) AND

(wave=4 OR wave=5)



GOTO msg\_20 IF (kinder\_183b=2 OR kinderanz\_183b=MISSING)

AND (wave=1 OR wave=2 OR wave3)

hi: Die Angabe der Kinderanzahl darf nicht in Kombination mit

„nein" möglich sein!

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_14_________________________________________\_
-----------------------------------------------------------

tc:

vn: kind1mon\_183b, kind1ja\_183b, kind1wo\_183b,

kind2mon\_183b, kind2ja\_183b, kind2wo\_183b

qt1: offene Angabe (kind1mon\_183b, kind1ja\_183b,

kind2mon\_183b, kind2ja\_183b)

qt2: Einfachauswahl mit horizontalen ao (kind1wo\_183b,

kind2wo\_183b)

hl:

in:

q1: Wann wurde dieses Kind geboren?

q2: Wann wurden diese Kinder geboren?

q3: Wann wurde(n) diese(s) Kind(er) geboren?

is: Geben Sie bitte sowohl eigene Kinder (leibliche Kinder

oder Adoptivkinder) an als auch Kinder Ihres Partners/Ihrer

Partnerin, die in Ihrem Haushalt leben. \[VISIBLE IF

kinderanz\_183b\>2 OR kinderanz\_183b=MISSING\] Wenn Sie mehr

als zwei Kinder haben, machen Sie bitte Angaben zu Ihrem

ältesten und jüngsten Kind.

it:

ao1:1: 1. Kind \[number\] (Monat) / \[number\] (Jahr)

q4: Lebt dieses Kind in Ihrem Haushalt?

ao2:2: ja

ao3:3: nein

ao4:4: 2. Kind \[number\] (Monat) / \[number\] (Jahr)

q5: Lebt dieses Kind in Ihrem Haushalt?

ao5:5: ja

ao6:6: nein

mv:

ka1: ka1 (ao1 TO ao3) 1. Kind

ka2: ka2 (ao4 TO ao6) 2. Kind

vc: SHOW q1 IF kinderanz\_183b ==1

SHOW q2 IF kinderanz\_183b \>1

SHOW q3 IF kinderanz\_183b ==MISSING

SHOW ao4 q5 ao5 ao6 IF kinderanz\_183b \>1 OR kinderanz\_183b

==MISSING

av:

av1: \[number\] (kind1mon\_183b): 2-stellig: 1 TO 12

av2: \[number\] (kind1ja\_183b): 4-stellig: 1950 TO 2021

av3: \[number\] (kind2mon\_183b): 2-stellig: 1 TO 12

av4: \[number\] (kind2ja\_183b): 4-stellig: 1950 TO 2021

kh1: Bitte geben Sie den Monat zweistellig (zwischen 1 und 12)

an.

kh2: Bitte geben Sie eine vierstellige Jahreszahl an.

kh3: Bitte geben Sie den Monat zweistellig (zwischen 1 und 12)

an.

kh4: Bitte geben Sie eine vierstellige Jahreszahl an.

fv:

hv:

fo:

tr: 

GOTO msg\_15 IF wave=4 OR wave=5



GOTO msg\_20 IF wave=1 OR wave=2 OR wave=3

Hi: mehrere Fragen und Fragetypen gleichzeitig auf einer Seite

(je 2 mal, für erstes und zweites Kind, eine offene Abfrage,

wann Kind geboren und Einfachauswahl, ob im eigenen Haushalt

wohnhaft ja/nein

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_15_________________________________________\_
-----------------------------------------------------------

tc:

vn: schvat\_183b/ schulmut\_183b/ schulvats\_183b/

schulmuts\_183b (die beiden letzten Variablen sind die für

die sonstige strings)

qt: Einfachauswahlmatrix mit horizontalen ao

hl:

in:

q: Welchen höchsten Schulabschluss haben Ihre Eltern?

is:

it1: Allgemeine oder fachgebundene Hochschulreife/Abitur

it2: Fachhochschulreife

it3: Realschulabschluss (Mittlere Reife), Polytechnische

Oberschule der DDR mit Abschluss der 10. Klasse

it4: Hauptschulabschluss, Polytechnische Oberschule der

DDR mit Abschluss der 8. Oder 9. Klasse

it5: kein Abschluss/unter 8. Klasse

it6: Abschluss unbekannt

it7: einen anderen Schulabschluss, und zwar: Vater

\[string\], Mutter \[string\]

st:

ao1:1: Vater

ao2:2: Mutter

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO msg\_19 IF wave=4



GOTO msg\_16 IF wave=5

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_16_________________________________________\_
-----------------------------------------------------------

tc:

vn: vatpromo\_183b/mutpromo\_183b/ vatuni\_183b/

mutuni\_183b/ vatfh\_183b/ mutfh\_183b/ vatmei\_183b/

mutmei\_183b/ vatlehre\_183b/ mutlehre\_183b/

vatschul\_183b/ mutschul\_183b/ vatohne\_183b/

mutohne\_183b/ vatunbek\_183b/ mutunbek\_183b

qt: Mehrfachauswahlmatrix mit horizontalen ao

hl:

in:

q: Welche beruflichen Ausbildungsabschlüsse haben Ihre

Eltern?

is:

it1: Promotion (Doktortitel)

it2: Universitätsabschluss

it3: Fachhochschulabschluss

it4: Abschluss an einer Meister-/Techniker-/Fachschule,

Berufs- oder Fachakademie

it5: beruflich-betriebliche Berufsausbildung (Lehre)

it6: beruflich-schulische Ausbildung (Berufsschule,

Handelsschule)

it7: kein beruflicher Abschluss

it8: beruflicher Abschluss unbekannt

st:

ao1:1: Vater

ao2:2: Mutter

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO msg\_17

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_17_________________________________________\_
-----------------------------------------------------------

tc:

vn: mutgebger\_183b/ mutgebaus\_183b

qt: Einfachauswahl mit vertikalen ao

hl:

in:

q: Wo ist Ihre Mutter geboren?

is:

it:

ao1: in Deutschland

ao2: in einem anderen Land, und zwar in: \[string\]

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO msg\_18

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_18_________________________________________\_
-----------------------------------------------------------

tc:

vn: vatgebger\_183b/ vatgebaus\_183b

qt: Einfachauswahl mit vertikalen ao

hl:

in:

q: Wo ist Ihr Vater geboren?

is:

it:

ao1: in Deutschland

ao2: in einem anderen Land, und zwar in: \[string\]

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO msg\_19

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_19_________________________________________\_
-----------------------------------------------------------

tc:

vn: eltsprac\_183b/ eltspr1\_183b/ eltspr2\_183b/

eltspr3\_183b

qt: Einfachauswahl mit vertikalen ao

hl:

in:

q: Welche Sprache wird in Ihrem Elternhaus normalerweise

gesprochen?

is:

it:

ao1: Deutsch

ao2: Deutsch sowie eine andere Sprache, und zwar:

\[string\] (eltspr1\_183b)

ao3: nicht Deutsch, sondern: \[string\] (eltspr2\_183b),

\[string\] (eltspr3\_183b)

mv:

ka:

vc:

av:

kh:

fv:

hv:

fo:

tr: 

GOTO msg\_20

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_20_________________________________________\_
-----------------------------------------------------------

tc:

vn: zuf4leben\_183b

qt: Einfachauswahl, vertikale ao

hl:

in:

q: Wie zufrieden sind Sie gegenwärtig alles in allem mit Ihrem Leben?

is:

st:

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

GOTO msg\_21

hi:

-------------------------------------------------------------------------------------------------------------------------------------------------
\__________________________________________msg\_21_________________________________________\_
-----------------------------------------------------------

tc:

vn: 

qt: 

hl:

in:

q: 

is:

st:

it:

ao:

mv:

ka:

vc: [Zwischenseite_8] visible if wave=1 OR wave=2 OR wave=3 OR wave=4 OR wave=5

av:

kh:

fv:

hv:

fo:

tr: 

GOTO \[ENDPAGE\]

hi:
