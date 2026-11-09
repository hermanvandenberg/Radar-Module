# Lesstof uit boek "Varen met behulp van radar" (STC Next, 2025) — samenvatting per pagina

## Inleiding (p5-9)
- Radar: navigatie-instrument binnenvaart. Boek volgt CCV-eindtermen; EU 2017/2397, ES-QIN.
- Voorwaarden kwalificatiecertificaat Varen met radar: min. 18 jaar; kwalificatiecertificaat Schipper; certificaat radio-operator (marifoon).
- Kandidaat moet: vóór afvaart passende maatregelen nemen; radarbeelden interpreteren/analyseren; interferenties verminderen; regels (bemanning, technische voorschriften) toepassen; omgaan met druk verkeer, uitval apparatuur, gevaarlijke situaties.
- Cursus 5 dagen incl. examens (theorie op CBR-locatie, praktijk op radarsimulator door CCV/CBR). Simulator: 5 stuurhuizen, beurtelings schipper.
- Simulator-stuurstelling: o.a. voetpedaal intercom/hoorn/VHF-1, telegraaf, ECDIS met AIS (10), radarscherm (11), multiflexscherm (14), noodstuurwerk tijdafhankelijk (16), roerwerk wegafhankelijk en rivierpiloot (18). Geen standaardopstelling in binnenvaart; ES-TRIN stelt wel eisen aan éénmansstuurstelling.
- Stuurwerk: MANUAL = wegafhankelijk; FIXED RATE = rivierpiloot; daarna ACTIVE bij het pookje. Boegschroef: menu > Thruster Control > BOW aanraken.

## H1 Radartechniek
1.1 Waarom techniek kennen: vertrouwen, geen onberedeneerd wantrouwen of ongefundeerd vertrouwen, beoordeling kwaliteit info.
1.2 RADAR = Radio Detection And Ranging. Eerste radar: zender, ontvanger, oscilloscoop. Nu: afstand en richting direct aflezen.
1.3 Principe = echolocatie (vleermuis, dolfijn). Sonar = geluid onder water; radar = elektromagnetische golven in de lucht.
1.4 Vier hoofdonderdelen: zender (transmitter), antenne (scanner), ontvanger (receiver), scherm/beeldkast (display). Plus synchronisatie-eenheid en zend/ontvangschakelaar. Werking: HF elektromagnetische golf, in bepaalde richting, bepaalde lengte, constante snelheid; tijd tussen uitzenden en echo → afstand; antennestand bij ontvangst → peiling.
1.5.1 Elektromagnetische golf: elektrisch + magnetisch deel loodrecht op elkaar. Magnetisch deel verticaal = verticaal gepolariseerd; horizontaal = horizontaal gepolariseerd.
1.5.2 Snelheid = lichtsnelheid: 300.000 km/s = 300 m/µs.
1.5.3 Golflengte = afstand tussen twee opeenvolgende toppen van sinusgolf, symbool λ (lambda); amplitude = sterkte. Rivierradar golflengte ≤ 3,2 cm.
1.5.4 Frequentie = aantal golflengtes (oscillaties) per seconde, eenheid hertz (Hz). kHz/MHz/GHz. Rivierradar 9300–9500 MHz.
1.6 Radarpuls = uitgezonden golf van bepaalde tijdsduur/lengte. Pulsduur in microseconden (µs). 1 µs = 300 m; 0,1 µs = 30 m; 0,01 µs = 3 m. ES-TRIN Bijlage 5 onderdeel III art 7 lid k: minimum af te beelden afstand ten hoogste 15 m. Binnenvaartradar korte puls, bv ≤0,05 µs (15 m) voor bereiken tot 2000 m.
1.6.1 Pulsherhalingsfrequentie (PRF) = aantal pulsen per seconde; mede bepaald door draaisnelheid antenne en gekozen bereik. Object moet meerdere keren getroffen worden. Magnetron zwaar belast → rustperiode; langere puls → lagere PRF. Tabel: 1,2 km 0,04 µs 4000 Hz; 8 km 0,3 µs 2000 Hz; 16 km 0,6 µs 1000 Hz. Pulsherhalingsperiode = ontvangsttijd + dode tijd.
1.7.1 Scanner 3 functies: zenden met gebundelde straal; ontvangen echo; peilen en maken van de kiellijn. Max aanwijsfout 1°. Smalle horizontale bundel (max 1,2°), brede verticale bundel (max 30°). Smalle hor. bundel → nauwkeurige peiling, echo niet vertekend. Bundelhoek = 70 × golflengte(cm) / antennelengte(cm); 70×3,2/180 = 1,2°. Langere scanner = smallere bundel. ES-TRIN min scannerlengte 1,80 m. Leverbaar 6,7,8,9 voet (180/210/240/270 cm). Langere scanner aanbevolen voor kleinere vaarwegen.
1.7.2 Kiellijn (KL) = heading line (HL) = heading marker (HM): gemaakt door contact in scannerhuis op moment dat scanner loodrecht op lengteas staat (bedoeld: in lengteas wijst). Huidige radars controleren automatisch.
1.7.3 Meeste scanners gesloten golfgeleider, afscherming, kunststof huis.
1.7.4 Opstelling (ES-TRIN bijl 5 ond III art 4): zo dicht mogelijk boven de lengteas; geen objecten in stralingsbereik (valse echo's/schaduwen); evt. op voorschip; stabiel. Na correctie afwijking koerslijn–lengteas max 1°. Bij twee radars scanners niet op gelijke hoogte.
Omwentelingen: min 24 per minuut; snelle schepen optie 40 (niet verplicht). Sneller draaien = vloeiender beeld.
1.8.1 Zender zendt korte krachtige puls; ontvanger tijdens uitzending gesloten (vgl. simplex marifoon). Plaats op scherm bepaald door richting (scannerstand t.o.v. kiellijn) en afstand (tijd).
1.8.2 Zend-ontvangschakelaar blokkeert ontvanger bij uitzenden. Te korte blokkade → beschadiging mengkristal; te lange → grotere dode zone. In sluizen/bij hoge objecten zender op stand-by; laagste vermogen kiezen indien regelbaar. Nieuwe installaties beveiligd.
1.8.4 Voeding: spanningsvariaties ±10% moeten verwerkt kunnen worden; stabiele voeding belangrijk.
1.8.5 Modulator bouwt spanning op, afgegeven als ontladingen; duur afhankelijk van pulsduur/bereik.
1.8.6 Magnetron = de zender, wekt zeer HF radiogolf op.
1.8.7 Zendpuls via kabel (vroeger golfpijp) naar antenne; zend-ontvangschakelaar in antennehuis. Max zendvermogen rivierradar 5 kW.
1.8.8 Echo veel zwakker dan uitgezonden; hoe verder hoe groter verlies; in ontvanger versterkt. Voorbeeld bereik 1200 m: echo 600 m terug na 4 µs (4×300=1200 heen-terug /2 = 600), 1200 m na 8 µs. Peiling: antennestand elektronisch overgebracht; antenne en tijdbasis synchroon (synchroonsysteem).
1.9 Beeldweergave: binnenvaart HEAD-UP (kiellijn naar boven). Zeevaart North-up en Course-up.
1.9.1 Head-up: gerefereerd aan koerslijn, altijd naar boven; geen andere sensoren nodig; uitzicht uit ramen = beeld scherm.
1.9.2 North-up: gerefereerd aan kompas, noorden boven; lijkt op kaart; koerslijn draait bij koerswijziging; consistente oriëntatie met ECDIS/kaart.
1.9.3 Course-up: als head-up maar kompas-gerefereerd; huidige koers boven, beeld stabiel; koersregel draait bij koerswijziging; voordeel kanalen en zuidelijke koersen (links/rechts fouten voorkomen).
1.10 Radiaal/afstand onderscheidend vermogen: twee objecten in één lijn achter elkaar → gescheiden als ze > ½ pulslengte uit elkaar liggen. 0,04µs=12m→>6m; 0,05µs=15m→>7,5m; 0,1µs=30m→>15m; 0,25µs=75m→>37,5m; 0,5µs=150m→>75m; 1µs=300m→>150m. ≤½ pulslengte → één echo. Radarreflector brugpijler op > ½ pulslengte van pijler. Bij 0,1 µs halve puls = 15 m.
1.11 Horizontaal (azimutaal) onderscheidend vermogen, EU-norm: twee objecten op 1200 m, loodrecht op peilrichting, 30 m uit elkaar, moeten gescheiden weergegeven worden. Mogelijk bij hor. bundelbreedte max 1,2°. Door bundelbreedte geeft object op grote afstand bredere echo; twee objecten binnen bundel → één echo. Factoren: bundelbreedte (scannerlengte, golflengte), afstand.
1.12 Dode zone: gebied rond scanner zonder echo's; straal = ½ pulslengte (bepaald door pulslengte). 0,05 µs → ~7,5 m. Tabel: 16000m 0,6µs 180m pulslengte → dode zone 90m, afstandonderscheiding 90m; 8000m 0,3µs 90m → 45m; 4000m 0,1µs 30m → 15m; 1200m 0,05µs 15m → 7,5m.
1.13 Dode hoek: ruimte voor schip die u vanuit stuurhuis niet kunt overzien (stuurlastig, opbouw voorschip, hoge deklast). Ook radar ziet dit niet; hoogte scanner meest bepalend. Containerschepen tevens scanner op voorschip. Formule dode hoek = hoogte voorschip × afstand roerganger–voorschip / (hoogte roerganger − hoogte voorschip).
Blinde sector/zone: door verticale bundelhoek (max 30°) wordt dichtbij gebied niet aangestraald → objecten daar niet zichtbaar. Voorbeeld: scanner 3 m hoog, blinde afstand 8 m; hogere scanner/slagzij vergroot blinde afstand (bv 100 m bij 20° helling).
1.14 Kleuren TFT-scherm: kleuren aanpasbaar; volledig digitaal. ES-TRIN: portretformaat, korte kant min 270 mm. Inland ECDIS combineren met radar = overlay. Positie eigen schip moet zeer nauwkeurig. LET OP: Overlay mag bij slecht zicht alleen in 'Navigatiemodus'.
1.14.1 ECDIS = Electronic Chart Display (and Information) System; S57 Inland ECDIS standaard.
1.14.2 ENC = Electronic Navigational Chart = vectorkaart; elementen individueel opgeslagen in lagen; meer mogelijkheden dan RNC/rasterkaart. Verplicht in ECDIS: ENC-data (officiële hydrografische instellingen), kleuren en symbolen, positie schip, schaalwijziging (waarschuwingen), dieptecijfers. Bronnen: GPS, gyrokompas koers, snelheid, radar. Voordelen ENC: weinig geheugen, binnenvaartobjecten/verkeerstekens, pickreport, lagen aan/uit, route checken op diepgang. Basisuitvoering is navigatie-ondersteunend: je kunt er NIET op navigeren; alleen type-goedgekeurde systemen in navigatiemodus.
1.14.3 Informatiemodus: elektronische atlas, oriëntatie, niet voor navigeren. Navigatiemodus: radarbeeld geïntegreerd (overlay); radar moet voldoen aan Rijnvaart-voorschriften; positie van doorlopend positiebepalend systeem; vereist radarpatent. Sinds april 2016 ENC van alle Europese vaarwegen CEMT klasse V+ (en aansluitende IV) beschikbaar; geen kant-en-klare vaarkaarten; ECDIS-viewer nodig; commerciële kaarten meer info.
Bijwerken: RIS (River Information Services) server NL, sinds maart 2005 operationeel; Inland ENC's, waterstanden, berichten aan scheepvaart, ijsberichten, weer. Diepte-info t.o.v. GLW of actuele waterstand; peildatum in ENC. Vaarweginformatie.nl (FIS, Fairway Information System) gratis ECDIS-cellen. NL IV+ vaarweginformatie.nl; Vlaanderen Va+ ris.vlaanderen.be; Duitsland Va+ elwis.de. Producten: AlphaChart River, Periskal, Tresco Navigis, PC Navigo.

## 1.15 Oefenvragen H1 (28 vragen, boek p31): afstand bepalen; snelheid; golflengte; golflengte rivierradar; frequentie; eenheid Hz; frequentie rivierradar; pulsduur; eenheid µs; pulslengte; PRF; voorwaarden echo; 3 functies scanner; plaats scanner; max bundelhoeken; kiellijn; echo juiste plaats; head-up; radiaal OV; factoren radiaal OV; eis radiaal; horizontaal OV; factoren; eis horizontaal; dode zone; grootte dode zone; dode hoek; grootte dode hoek.
(Antwoorden staan in H8, p113 — nog niet ontvangen.)
