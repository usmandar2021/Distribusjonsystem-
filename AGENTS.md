# Distribusjonsystem- – overlevering til agenter og utviklere

Enkel nettside som regner varmetap i distribusjonsnettet for romoppvarming (forenklet metode, basert på NS-EN 15316-3).
Eier: Usman (GitHub usmandar2021). Skriv og svar på norsk bokmål.

**Dette repoet er OFFENTLIG.** Skriv bare teknisk, ikke-sensitivt innhold. Ingen lisensiert standardtekst eller tabeller,
ingen hemmeligheter, ingen personopplysninger, ingen prosjektdata.

Denne fila leses automatisk av Claude Code, Codex, Cursor og liknende verktøy. Den holdes oppdatert hver natt av en
skyrutine som går gjennom endringene siste døgn.

## Hva repoet er

Én fil, `index.html`, med innebygd CSS og JavaScript (ingen byggetrinn, ingen avhengigheter utenom en skrifttype fra
Google Fonts). Brukeren oppgir bygningsgeometri (lengde, bredde, etasjehøyde, antall etasjer), velger forhåndsinnstilling
for rørlengdekoeffisienter og isolasjonsklasse, og siden regner rørlengder for fordelings-, stigeledninger og
tilkoblinger, varmetap i W og kWh/år. Funksjonen `calc()` gjør beregningen; `PRESETS` og `PSI` holder tallgrunnlaget.
Støtter lys og mørk modus og mobil.

## Kjøre

Åpne `index.html` i en nettleser, eller server mappen (`python3 -m http.server`). Ingen tester finnes.

## Arbeidsregler

- Hold løsningen som én statisk fil, med mindre Usman ber om noe annet.
- Tallgrunnlag fra lisensierte standarder skal ikke legges inn i dette offentlige repoet; bruk egne eller åpne kilder og merk dem.
- Se `docs/kontekst/beslutninger.md` og `docs/kontekst/status.md`.

## Nattrutine

- 04:00: denne dokumentasjonen oppdateres (`AGENTS.md`, `docs/kontekst/`).
