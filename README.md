# Deadlines bij de documenten — welzijnswetgeving

Eén afdrukbare overzichtspagina met de wettelijke termijnen bij de verplichte
documenten uit de Belgische welzijnsregelgeving (Codex over het welzijn op het
werk): hoe vaak een document moet worden opgesteld of bijgewerkt, tegen welke
deadline, hoelang het moet worden bewaard, en binnen welke termijn iets moet
worden gemeld. Per document: de termijn, het wetsartikel en een link naar de
officiële wettekst (FOD WASO / Justel).

Welkomstcadeau voor de LinkedIn-groep
**Welzijnswetgeving | Législation sur le bien-être au travail**
(https://www.linkedin.com/groups/42836426/).

> Volgens onze telling, stand november 2026. De officiële en bindende tekst is
> altijd die van de wetgever.

## Inhoud van deze repository

```
index.html      de pagina zelf (alles staat erin: tekst, data, zoek/filter)
favicon.svg     neutraal klok-icoontje
robots.txt      indexeerbaar
netlify.toml    publicatie-instellingen (hoofdmap, geen build)
```

Er is geen build-stap en er zijn geen afhankelijkheden: het is één bestand dat
overal werkt. De pagina is afdrukbaar (Ctrl/Cmd+P) en werkt licht én donker.

## Online zetten via GitHub + Netlify

1. Maak een **nieuwe, aparte GitHub-repository** (bv. `deadlines-documenten`)
   en upload de inhoud van deze map (met `index.html` in de hoofdmap).
2. Ga op Netlify naar **Add new site → Import an existing project** en kies deze
   repository. Publish directory: `.` (hoofdmap), build command: leeg.
3. Netlify geeft de site een eigen adres (bv.
   `deadlines-documenten.netlify.app`); dat kun je in de site-instellingen
   hernoemen. Elke push naar `main` publiceert automatisch opnieuw.

Alternatief zonder GitHub: sleep deze map op **app.netlify.com/drop** voor een
eenmalige publicatie.

## Bijwerken

De documenten en termijnen komen uit de Checklist welzijnsregelgeving (laag 1)
en de Bibliotheek termijnen (TRM-) van de Digitale Preventieadviseur. Werk daar
bij en genereer deze pagina opnieuw.
