# Schrijven bij de Rijksoverheid

Plugins met skills voor communicatieprofessionals bij de Nederlandse overheid, gebouwd op de
openbare vakkennis van [communicatiekompas.nl](https://www.communicatiekompas.nl) en
[communicatierijk.nl](https://www.communicatierijk.nl). Werkt in **Codex / ChatGPT** en in **Claude Code**.

Geen plugins beschikbaar in je account? In `losse-skills/` staat elke skill als losse ZIP, met de
bronteksten die de skill gebruikt. Die kun je bijvoorbeeld in Claude uploaden via **Customize > Skills**.

Dit is een onafhankelijk project van [Aigenwijs](https://aigenwijs.com). Het is geen uitgave van de
Rijksoverheid, de Dienst Publiek en Communicatie of het Communicatiekompas.

## Plugins

### Schrijven bij de Rijksoverheid (`schrijven-rijksoverheid`, versie 0.4.0)

Schrijven zoals de Rijksoverheid het afspreekt (Taalkompas): tekst opzetten en structureren, begrijpelijke taal op B1, burgerbrief, Kamerbrief, beslisnota, inclusief schrijven, eenvoudige taal op A2 en teksten testen bij lezers, gebaseerd op communicatierijk.nl en communicatiekompas.nl.

Skills:

- `tekst-a2`: Eenvoudig schrijven op A2
- `tekst-b1`: Begrijpelijk schrijven op B1
- `tekst-beslisnota`: Beslisnota schrijven
- `tekst-burgerbrief`: Burgerbrief schrijven
- `tekst-inclusief`: Inclusief schrijven
- `tekst-kamerbrief`: Kamerbrief schrijven
- `tekst-opzetten`: Tekst opzetten en structureren
- `tekst-testen`: Tekst testen en controleren

Elke skill bevat een leestabel die verwijst naar de meegeleverde bronteksten in `bronnen/`.
De agent leest die teksten bij gebruik; de skill geeft werkwijze, output en veelgemaakte fouten.

In Claude Code geeft deze plugin bij de start van elke sessie (SessionStart-hook) een korte
instructie mee: welke skills er zijn en welke grondregels gelden. De hook voert alleen
een `echo` uit en verstuurt niets.

## Installeren in de Codex-app (ChatGPT)

Open **Instellingen → Plug-ins → Plug-in-marktplaats toevoegen** en vul in:

| Veld | Waarde |
|---|---|
| Bron | `viperxxl010/schrijven-rijksoverheid` (of `git@github.com:viperxxl010/schrijven-rijksoverheid.git`) |
| Git-referentie | `main` |
| Sparse-paden | leeg laten, of `plugins/<naam>` (bijvoorbeeld `plugins/schrijven-rijksoverheid`) voor alleen die plugin |

Daarna verschijnt de marktplaats **schrijven-rijksoverheid** met de plugins hierboven; klik op *Installeren*.

Via de Codex-CLI:

```bash
codex plugin marketplace add viperxxl010/schrijven-rijksoverheid --ref main
```

## Installeren in Claude Code

```
/plugin marketplace add viperxxl010/schrijven-rijksoverheid
/plugin install schrijven-rijksoverheid@schrijven-rijksoverheid
```

## Kosten

De plugins zijn gratis en vrij te gebruiken (CC0). Je hebt wel een werkende Codex-, ChatGPT- of
Claude Code-omgeving nodig; daarvoor gelden de voorwaarden en eventuele abonnementskosten van die aanbieder.

## Bronnen en rechten

De teksten in `bronnen/` zijn kopieën van pagina's van communicatiekompas.nl en communicatierijk.nl,
waarvan de tekst onder een CC0-verklaring is gepubliceerd, plus tekstversies van PDF-publicaties
van die sites die hergebruik met bronvermelding toestaan. Elke kopie vermeldt de bron-URL in de
frontmatter. Vier publicaties met een beperkende rechtenvermelding (*Monitor Ontwikkeling
Mediagebruik 2025*, *Moet dat nou zo?!*, *Leidraad Communicatieonderzoek 2017* en *Blijf bevragen*)
zijn **niet** opgenomen; de meegeleverde paginateksten noemen ze wel, met de bron-URL in de frontmatter.

De plugin `factorc-hulpmiddelen` bevat naast de tekstversies ook de originele PDF's (blanco
invulformulieren en CASI-publicaties). **Uitzondering op CC0:** de *Handleiding CASI*
(`plugins/factorc-hulpmiddelen/bronnen/communicatierijk/documenten/handleiding-casi/`) valt niet onder CC0.
Volgens het colofon mogen delen ervan met vermelding van auteur en bron worden gebruikt voor
niet-commerciële doeleinden; voor ander gebruik is toestemming nodig van de Dienst Publiek en
Communicatie (Ministerie van Algemene Zaken). Zie `bronnen/OVERZICHT.md` in die plugin.

De plugin `beeld-rijksoverheid` bevat teksten van beeldkompas.nl. Die tekst is vrijgegeven onder CC0,
**de beelden van Beeldkompas niet**: die zitten niet in de plugin, en verwijzingen ernaar en
makersvermeldingen zijn uit de teksten gehaald. Bekijk voorbeeldbeelden op beeldkompas.nl zelf.

Alles in deze repository (skills, manifesten, README) is, met uitzondering van de hierboven genoemde
Handleiding CASI, vrijgegeven onder
[CC0 1.0 Universal](LICENSE): doe ermee wat je wilt, zonder bronvermelding of toestemming.
Aigenwijs geeft geen garanties; controleer feiten en cijfers altijd in de aangewezen bron.

## Zelf bouwen

Deze repository wordt gegenereerd uit een werkrepository met `scripts/build_release.py`;
wijzigingen graag als issue melden, niet als pull request op de gegenereerde bestanden.
