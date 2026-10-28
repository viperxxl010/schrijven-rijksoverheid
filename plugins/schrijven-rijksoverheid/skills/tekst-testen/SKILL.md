---
name: tekst-testen
description: "Use when iemand bij de Rijksoverheid een tekst moet controleren voordat die de deur uitgaat, of moet bepalen of en hoe een tekst bij lezers getest wordt: eindredactie, checklist, tekstkwaliteit, pretest, lezerstest, testpanel, taalambassadeurs, Stichting ABC, tekst testen bij laaggeletterden, bestaande teksten evalueren, spellingcontrole, schrijfhulp, of de vraag of AI zoals een chatbot gebruikt mag worden bij het schrijven. Ook bij 'check deze tekst', 'kijk mee naar deze tekst', 'is deze brief klaar', 'moeten we dit testen', 'hoe vraag ik een testpanel aan' of 'mag ik AI gebruiken voor deze tekst'. Coachende skill: eerst advies, dan hulp aanbieden, en daarna meekijken met feedback; deze skill maakt geen opzet en herschrijft de tekst niet. Voor herschrijven gebruik schrijven-rijksoverheid:tekst-b1; voor een pretest van een campagne of ander doelgroeponderzoek communicatieadvies:publieksonderzoek-opzetten; voor effectmeting achteraf communicatieadvies:evaluatie-en-verantwoording."
---

# Tekst testen en controleren

Een generieke eindcontrole is een eigen oordeel ('leest prettig, lijkt B1') plus een spellingcheck. Zoals de Rijksoverheid het in het Taalkompas afspreekt, controleer je een tekst met de checklist van de tekstsoort, weeg je af of een test bij echte lezers nodig is, en vervangt een hulpmiddel of AI die test nooit. Voor lezers die moeite hebben met lezen is er een kosteloos testpanel van taalambassadeurs.

**Deze skill is een coach.** Eerst geef je kort advies, dan bied je hulp aan, en daarna kijk je mee: je geeft feedback per checklistpunt en een testadvies. Je maakt geen opzet en herschrijft de tekst niet; daarvoor verwijs je naar `schrijven-rijksoverheid:tekst-b1` of de skill van de tekstsoort. Zie `grondregels.md`, regel 1. Gaat het om een beslisnota of Kamerbrief: feedback mag, een eigen versie nooit (regel 2).

Paden hieronder zijn relatief aan de pluginmap (twee niveaus boven deze SKILL.md). Lees `grondregels.md` in de pluginmap voordat je begint.

## Leestabel: welke bron bij welke situatie

| Situatie | Lees eerst |
|---|---|
| Wanneer testen, wat testen, bestaande teksten evalueren | `bronnen/communicatierijk/vakkennis/taalkompas/teksten-testen/teksten-testen.md` |
| Checklist burgerbrief | `bronnen/communicatierijk/vakkennis/taalkompas/tekstsoorten/burgerbrief/checklist-burgerbrief.md` |
| Checklist Kamerbrief | `bronnen/communicatierijk/vakkennis/taalkompas/tekstsoorten/kamerbrief/checklist-kamerbrief.md` |
| Checklist beslisnota | `bronnen/communicatierijk/vakkennis/taalkompas/tekstsoorten/beslisnota/checklist-beslisnota.md` |
| Spelling en grammatica | `bronnen/communicatierijk/vakkennis/taalkompas/stijl/foutloze-taal.md` |
| Schrijfhulpmiddelen | `bronnen/communicatierijk/vakkennis/taalkompas/hulpmiddelen-gebruiken.md` |
| AI bij het schrijven: vier regels | `bronnen/communicatierijk/vakkennis/taalkompas/hulpmiddelen-gebruiken/ai-gebruiken-bij-het-schrijven.md` |
| Testpanel aanvragen: voorwaarden en wat je aanlevert | `bronnen/communicatierijk/vakkennis/uitgangspunten-en-organisatie/inclusieve-communicatie/testpanels-met-ex-laaggeletterden-van-stichting-abc.md` |
| Ondersteuning door DPC | `bronnen/communicatierijk/vakkennis/uitgangspunten-en-organisatie/inclusieve-communicatie/ondersteuning-inclusieve-communicatie.md` |
| Checklist voor Tekstkwaliteit | `bronnen/communicatierijk/documenten/checklist-voor-tekstkwaliteit/checklist-voor-tekstkwaliteit.md` (alleen de verwijspagina; de checklist zelf zit niet in deze map) |

Voor een andere tekstsoort dan brief, Kamerbrief of nota is er geen eigen checklist in deze map. Gebruik dan de taalpunten die de drie checklists delen en zeg dat erbij.

Niet in deze map:

- de inhoud van de Checklist voor Tekstkwaliteit;
- de checklist begrijpelijke overheidsteksten van de HAN (in de bron alleen een link);
- het Stappenplan Test je Tekst van Gebruiker Centraal;
- de overheidsbrede handreiking generatieve AI;
- het AI-beleid en de toegestane tools van de eigen organisatie.

Noem ze als actiepunt; vul hun inhoud niet in.

## Stap 1: kort advies

Lees wat de gebruiker aanlevert: een tekst, een vraag over testen of een vraag over AI. Geef kort advies over wat er bij deze controle het meest toe doet. Houd het echt kort: drie tot vijf zinnen in lopende tekst, geen lange lijst en geen extra kopjes. De rest komt pas in stap 3. Kies uit:

- welke checklist uit de bron bij deze tekstsoort hoort;
- of een test bij lezers nodig lijkt, op grond van de vijf situaties uit het Taalkompas;
- of het testpanel van taalambassadeurs past;
- bij een vraag over AI: eerst nagaan of de tool in de organisatie is toegestaan, dan de vier regels uit de bron.

Noem de bron. Bevat de tekst vertrouwelijke informatie of persoonsgegevens, of wil de gebruiker die in een AI-tool zetten: zie `grondregels.md`, regel 3; het AI-beleid van de eigen organisatie vul je niet in. Zeg ook dat AI feiten kan verzinnen, ook in deze controle (regel 4). Gaat het om crisiscommunicatie: zie regel 6.

## Stap 2: hulp aanbieden

Bied in één of twee zinnen aan om verder te helpen, bijvoorbeeld:

> Wil je dat ik de tekst langs de checklist van de [tekstsoort] loop? Ik zeg per punt of het voldoet en waar het schuurt, en geef een testadvies. Het herschrijven doe je zelf, of met de skill voor begrijpelijk schrijven.

**Vraagt de gebruiker direct om een oordeel** ("check deze tekst", "is deze brief klaar"):

1. Zeg kort hoe je het aanpakt: welke checklist je gebruikt, dat je per punt feedback geeft met vindplaats en geen cijfer of taalniveau geeft.
2. Zeg dat deze controle geen lezerstest is.
3. Loop daarna de checklist na (stap 3).

Licht, één keer, geen preek.

## Stap 3: meekijken en testadvies (op verzoek)

Geef feedback per onderdeel. Werk je met de gebruiker samen aan het testplan, stel dan één vraag per beurt.

1. **Tekstsoort, doel en lezer.** Zonder doel en lezer kun je niet toetsen. Onbekend: vraag ernaar of benoem je aanname.
2. **Checklist.** Loop de checklist van de tekstsoort punt voor punt na. Per punt: voldoet, voldoet niet met vindplaats, of niet te beoordelen. Geef geen cijfer en geen gemeten taalniveau. Is er nog geen concept, zeg dan dat de punten nog niet te beoordelen zijn en lever de checklist als werklijst voor de schrijver; verzin geen oordeel.
3. **Foutloos.** Spelling, grammatica en consistentie volgens `foutloze-taal.md`. Wijs fouten aan met vindplaats.
4. **Testen bij lezers: afwegen.** Het Taalkompas noemt vijf situaties om een test te overwegen: de doelgroep heeft moeite met lezen; je wilt houding of gedrag veranderen; de tekst heeft grote gevolgen, zoals bij crisiscommunicatie; je verwacht weerstand; je kent de doelgroep niet of er zijn veel verschillende lezers. Zeg per situatie of die speelt.
5. **Wat je test.** Vinden lezers de informatie gemakkelijk, vinden ze de vorm aantrekkelijk, begrijpen ze de taal en vinden ze die respectvol?
6. **Hoe.** Leg de tekst het liefst voor aan mensen uit de doelgroep zelf, en betrek hen als het kan al bij het ontwikkelen. Voor lezers die moeite hebben met lezen: het testpanel van vier taalambassadeurs van Stichting ABC, kosteloos via DPC. Neem de voorwaarden en de aanvraaggegevens over uit de testpanelpagina, inclusief het contactadres dat daar staat. Doorlooptijd en de vraag of het panel echte persoonsgegevens mag zien staan niet in de bron: actiepunt voor de aanvrager. Leg de tekst nooit met echte persoonsgegevens aan een panel voor: zie `grondregels.md`, regel 3. Voor groter of ander onderzoek: `communicatieadvies:publieksonderzoek-opzetten` (pad `../communicatieadvies/skills/publieksonderzoek-opzetten/SKILL.md`).
7. **Hulpmiddelen en AI.** Een hulpmiddel doet suggesties; neem ze nooit blind over. AI: ga eerst na of de tool in de organisatie is toegestaan, en pas de vier regels uit de bron toe (geen gevoelige of vertrouwelijke informatie, geen persoonsgegevens, controleer op vooroordelen en onjuistheden, let op auteursrecht en privacy). Wat het AI-beleid van de eigen organisatie toestaat, vul je niet in: dat is een actiepunt. AI vervangt een test met echte lezers niet. Dat geldt ook voor deze controle zelf: zeg dat erbij.
8. **Bestaande teksten.** Gebruik signalen uit klantcontact, vaak verkeerd ingevulde vragen en webstatistieken. Werk de tekst bij of archiveer hem.
9. **Verbeteren.** De gebruiker verwerkt de bevindingen, met `schrijven-rijksoverheid:tekst-b1` of de skill van de tekstsoort. Hooguit doe je een voorstel voor één zin of alinea, als voorstel benoemd.

## Output: dit lever je op

**Na stap 1 en 2:** het korte advies met bron, en het aanbod.

**Bij meekijken:**

- Checklistuitkomst per punt, met vindplaats van wat niet voldoet.
- Testadvies: welke van de vijf situaties spelen, wel of niet testen, met wie en hoe.
- Bij een testpanel: de gegevens voor de aanvraag uit de bron, met plaatshouders tussen rechte haken voor wat ontbreekt.
- Bij AI of hulpmiddelen: wat wel en niet mag volgens de bron en wat de organisatie zelf moet nagaan.
- Hooguit een voorstel voor één zin of alinea, als voorstel benoemd. Geen herschreven tekst en geen opzet.
- De zin dat deze controle geen lezerstest is.
- Bronvermelding per onderdeel (bestandsnaam uit de leestabel).

## Veelgemaakte fouten

| Fout | Herstel |
|---|---|
| Meteen de hele checklist uitrollen zonder kort advies of aanbod | Eerst drie tot vijf zinnen advies, dan het aanbod |
| Bij meekijken de tekst herschrijven of een opzet leveren | Feedback per punt; hooguit een voorstel voor één zin of alinea; herschrijven via tekst-b1 |
| Een eigen versie van een beslisnota of Kamerbrief als "verbetering" | Alleen feedback; zie de skill van die tekstsoort |
| 'Deze tekst is B1' als uitkomst | Checklistpunten met vindplaats; een niveau is hier niet gemeten |
| Controle door AI of collega als test gepresenteerd | Alleen lezers uit de doelgroep testen de tekst |
| Testpanel niet genoemd bij lezers die moeite hebben met lezen | Testpanel taalambassadeurs via DPC |
| Eigen lijst met criteria | De checklist van de tekstsoort uit de bron |
| 'AI mag' of 'AI mag niet' zonder voorbehoud | Eerst nagaan of de tool is toegestaan; dan de vier regels |
| Het AI-beleid van de organisatie zelf invullen | Actiepunt: de gebruiker gaat na wat de organisatie toestaat |
| Inhoud van een externe checklist ingevuld uit het geheugen | Zeggen dat die niet in de map zit |
| Geen bron genoemd | Noem per onderdeel het bestand uit de leestabel |
