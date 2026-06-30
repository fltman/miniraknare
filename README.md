# Miniräknare

[![Support me on Patreon](https://img.shields.io/badge/Patreon-Support%20my%20work-FF424D?style=flat&logo=patreon&logoColor=white)](https://www.patreon.com/AndersBjarby)

En enkel miniräknare i ren HTML/CSS/JavaScript – en enda `index.html`-fil utan beroenden. Projektet byggdes som demo för **GitHub Buddy**, ett nybörjarvänligt Claude Code-paket som hjälper dig komma igång med git utan teknisk jargong.

## Innehåll

- **`index.html`** – miniräknaren: grundräknesätten, decimaler, procent, teckenbyte och rensa, i mörkt tema.
- **GitHub Buddy-paketet** – Claude Code-tillägg som gör Claude proaktiv kring versionshantering och förklarar git-begrepp på vanlig svenska:
  - `agents/project-starter.md` – föreslår versionshantering innan du börjar koda
  - `skills/github-buddy/` – kunskap om git/GitHub plus referensguider och hjälpskript
  - `commands/nytt-projekt.md` – slash-kommandot `/nytt-projekt` för en guidad projektstart
  - `CLAUDE.md` – projektinstruktioner som Claude Code läser automatiskt

## Använda miniräknaren

Öppna `index.html` direkt i webbläsaren – inget bygge eller installation krävs.

## Installera GitHub Buddy i Claude Code

```bash
cp agents/project-starter.md ~/.claude/agents/
cp -r skills/github-buddy ~/.claude/skills/
cp commands/nytt-projekt.md ~/.claude/commands/
```

Starta sedan om Claude Code. Mer detaljer finns i `INSTALLERA.md`.

## Tech

Ren HTML, CSS och JavaScript (miniräknaren). Markdown-baserade Claude Code-agenter, skills och kommandon (GitHub Buddy).
