# Skills

Skills převzaté z oficiálního repozitáře [anthropics/skills](https://github.com/anthropics/skills)
(commit `e4bb5d960d87126ff3b3a8af1a104b7db67560ba`).

Skills jsou uložené zde ve složce `_AI Skills/`. Claude Code hledá skills ve složce
`.claude/skills/`, proto je `.claude/skills` odkaz (symlink) na `_AI Skills` –
**tento odkaz nemazat**, jinak se skills přestanou načítat.

Stačí v tomto repozitáři spustit Claude Code a skill se použije sám, když se hodí,
nebo ho zavoláš ručně přes `/<název>` (např. `/pdf`, `/xlsx`, `/skill-creator`).

| Skill | K čemu slouží |
|---|---|
| academy-guide | Doporučuje kurzy a návody z Claude Academy |
| algorithmic-art | Generativní umění v p5.js |
| brand-guidelines | Barvy a typografie Anthropic |
| canvas-design | Plakáty a vizuální návrhy do .png / .pdf |
| claude-api | Reference pro Claude API / Anthropic SDK |
| discernment-nudge | Kontrolní otázky k vytvořeným návrhům a radám |
| doc-coauthoring | Strukturované společné psaní dokumentace |
| docx | Práce s Word dokumenty |
| frontend-design | Vizuální návrh UI |
| internal-comms | Interní komunikace (reporty, newslettery, FAQ) |
| mcp-builder | Tvorba MCP serverů |
| pdf | Práce s PDF (čtení, slučování, formuláře, …) |
| pptx | Práce s PowerPoint prezentacemi |
| skill-creator | Tvorba a ladění vlastních skills |
| slack-gif-creator | Animované GIFy pro Slack |
| theme-factory | Hotová barevná / typografická témata |
| web-artifacts-builder | Složitější HTML artefakty (React, Tailwind, shadcn/ui) |
| webapp-testing | Testování webových aplikací přes Playwright |
| xlsx | Práce s tabulkami (.xlsx, .csv, …) |

Licence: Apache 2.0 (viz `LICENSE.txt` v každé složce a `THIRD_PARTY_NOTICES.md`).

Aktualizace na nejnovější verzi:

```bash
git clone --depth 1 https://github.com/anthropics/skills.git /tmp/anthropic-skills
cp -r /tmp/anthropic-skills/skills/* "_AI Skills/"
```
