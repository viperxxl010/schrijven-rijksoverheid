---
title: Portable Document Format (pdf) | CommunicatieRijk
bron: https://www.communicatierijk.nl/vakkennis/rijkswebsites/verplichte-richtlijnen/portable-document-format-pdf
site: communicatierijk
categorie: vakkennis/rijkswebsites
laatst_gewijzigd: 2024-01-15T15:33:53.877Z
rol_tags: ['online-social-media']
---

Er bestaat een grote verscheidenheid aan pdf-versies.

Op de verplichte pas-toe-of-leg-uit-lijst (PTOLU) van het Forum Standaardisatie staan er 3, maar de beste versie voor het web is PDF/Universal Accessibility-1 (ISO14289). Deze staat echter niet op de PTOLU-lijst.

## Formele basis en verplichting

Op de pas-toe-of-leg-uit-lijst (PTOLU) van het Forum Standaardisatie staan 3 verplichte Open Standaarden:

  1. PDF/1.7 (ISO 32000-1:2008);
  2. PDF/A-1 ( ISO 19005-1), bedoeld voor archivering (de A staat voor Archivable);
  3. PDF/A-2, PDF/A-2 slaat de brug tussen PDF/A-1 en PDF 1.7 waarbij PDF/A-2 een betere geschiktheid heeft voor langdurig archiveren van documenten waar “elementen” in zitten die niet door PDF/A-1 worden ondersteund en waarbij PDF 1.7 kan worden gebruikt voor “elementen” die niet door PDF/A-2 ondersteund worden.



De beste versie voor het web is echter **PDF/UA (ISO 14289-1:2014****)** : UA staat voor universally accessibility en is een subtype van PDF/1.7, bedoeld om consistent te zijn met de WCAG2-toegankelijkheidsrichtlijnen.  
WCAG 2.0 eist geen PDF/UA, maar voor het bereiken van toegankelijkheid in pdf-bestanden, moet je aan PDF/UA denken. 




## Praktisch gebruik van PDF UA

Hoewel PDF/UA toegankelijkheid voor online publicatie mogelijk maakt, blijft terughoudendheid in het gebruik van pdf geboden.

PDF/UA biedt een normatieve en uitgebreide manier om pdf-inhoud te testen op conformiteit met WCAG 2.0. Als onderdeel van de ontwikkeling van de PDF/UA-norm werkten de leden van het comité, zoals Adobe, Microsoft, Appligent, Crawford Technologies en vele anderen, samen met de WCAG-commissie om WCAG 2.0-richtlijnen in kaart te brengen in de specifieke secties van de PDF/UA-standaard en daarmee de naleving van WCAG te regelen door het volgen van de precieze specificaties binnen de ISO-standaard.

Een pdf die voldoet aan de ISO 14289-1 (ook bekend als PDF/UA) -specificatie, is een beperkte vorm van Adobe PDF 1.7 (zoals gedefinieerd in ISO 32000-1) bedoeld om toegankelijkheid en ondersteuning te waarborgen voor ondersteunende technologie die wordt gebruikt door een persoon met een handicap.

Vereisten voor PDF / UA-conformiteit zijn consistent met de Web Content Accessibility Guidelines (WCAG) 2.0, een W3C-aanbeveling van 11 december 2008. De beperkingen op een PDF 1.7, voor PDF / UA-compliance, zijn de volgende:

  * Alle echte inhoud zal worden getagd. Artefacten worden niet getagd.
  * Inhoud zal gemarkeerd worden in de structuurboom met semantisch gepaste tags in een logische leesvolgorde. De standaard legt gedetailleerde gebruikseisen op voor koppen, tabellen en lijsten om navigatie door ondersteunende technologie te ondersteunen.
  * Alle structuurtypen die worden gebruikt, moeten standaard zijn of worden toegewezen aan de standaard.
  * Grafische objecten (afbeeldingen) die echte inhoud zijn, moeten een figuurlabel krijgen met alternatieve of vervangende tekst; bijschriften bijbehorende figuren moeten worden getagd als bijschriften.
  * Informatie mag niet worden weergegeven door contrast, kleur, indeling of lay-out, tenzij de inhoud is getagd om alle bedoelde betekenis weer te geven.
  * Alle informatie die met geluid wordt overgebracht, moet ook zonder geluid beschikbaar zijn.
  * Lettertypen moeten zijn ingesloten.
  * Dynamische XFA-formulieren zijn niet toegestaan. Statische XFA-formulieren kunnen worden gebruikt.


