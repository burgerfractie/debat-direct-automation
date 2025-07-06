# Project: Debat Direct Automatisering

![Status](https://img.shields.io/badge/status-in_ontwikkeling-yellow)

Welkom bij het open-source project voor het automatiseren van de verwerking van debatten van de Tweede Kamer! Dit project is gestart om de toegankelijkheid van politieke debatten te vergroten door het proces van downloaden, transcriberen en publiceren te automatiseren.

## Doel van het Project

Het hoofddoel is het creëren van een geautomatiseerde workflow die de volgende taken uitvoert:

1.  **Downloaden:** Automatisch videofragmenten van [Debat Direct](https://debatdirect.tweedekamer.nl/) downloaden, intelligent opgesplitst op basis van schorsingen om te voldoen aan verwerkingslimieten.
2.  **Transcberen:** De gedownloade fragmenten uploaden naar Google Pinpoint voor automatische transcriptie.
3.  **Verwerken:** De gegenereerde transcripties opschonen (o.a. sprekersnamen corrigeren) en samenvoegen tot één coherent en doorzoekbaar document per debat.
4.  **Publiceren:** Het eindresultaat publiceren naar dit GitHub-account om de debatten voor iedereen toegankelijk te maken.

## Huidige Status

Dit project is momenteel in de initiële **ontwikkel- en opbouwfase**. De architectuur is gedefinieerd en de eerste stappen voor het opzetten van de serverinfrastructuur worden gezet.

➡️ **Bekijk onze live projectplanning op het [GitHub Project Board](/burgerfractie/debat-direct-automation/projects)**.

## Architectuur & Technologie

Dit project maakt gebruik van een moderne, hybride architectuur om een robuuste en schaalbare oplossing te garanderen.

* **Orkestratie:** [n8n](https://n8n.io/)
* **Browser Automatisering:** [Playwright](https://playwright.dev/) (aangestuurd door Python)
* **Programmeertaal:** Python
* **Server Infrastructuur:** [DigitalOcean](https://www.digitalocean.com/) Droplet met [Docker](https://www.docker.com/)
* **Ontwikkelomgeving:** [GitHub Codespaces](https://github.com/features/codespaces)

Voor een gedetailleerde uitleg van de architectuur, zie de documentatie in onze Wiki.

## Project Documentatie

Alle strategische en technische documenten worden bijgehouden in de Wiki van dit project.

* **[Architectuur & Technisch Plan](https://github.com/burgerfractie/debat-direct-automation/wiki/Project-%22Debat-Direct-Automatisering%22:-Definitieve-Architectuur-&-Technisch-Plan)**
* **[Installatiegids voor de Server](https://github.com/burgerfractie/debat-direct-automation/wiki/Definitieve-Geconsolideerde-Installatiegids:-Server-Setup)**

## Hoe je kunt bijdragen (Contributing)

Dit is een open-source project en hulp is altijd welkom! De beste manier om te beginnen is door de documentatie in de [Wiki](https://github.com/burgerfractie/debat-direct-automation/wiki) te lezen.

Als je een bug vindt of een idee hebt voor een verbetering, maak dan gerust een [Issue](https://github.com/burgerfractie/debat-direct-automation/issues) aan.

## Licentie

Dit project is uitgebracht onder de [MIT License](LICENSE).
