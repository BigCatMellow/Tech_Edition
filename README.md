# Tech Edition

A daily personal technology newspaper for discovering interesting mechanisms, projects, tools, experiments, revivals, and technical rabbit holes beyond mainstream technology news.

## Editorial goal

Every edition asks:

> What interesting things are people building, discovering, experimenting with, reviving, or figuring out?

The paper emphasizes discovery, mechanisms, practical experimentation, intellectual curiosity, and useful tools. It is deliberately broader than an AI newsletter.

## Data layout

- `data/latest.json` — current edition used by the web interface
- `data/archive/YYYY-MM-DD.json` — permanent structured archive
- `data/readers/YYYY-MM-DD.json` — optional expanded reader material
- `editions/YYYY-MM-DD.md` — readable Markdown edition
- `EDITORIAL_GUIDE.md` — canonical editorial specification
- `NEW_CHAT_HANDOFF.md` — operational handoff for future ChatGPT runs

## Publication model

Daily research and publication are performed by a scheduled ChatGPT task. A successful run publishes the edition here first, then updates `BigCatMellow/Notes/data/tech-edition-trigger.txt` to trigger the existing SMTP delivery system.

The email trigger must never be updated if the edition failed to publish or `data/latest.json` is incomplete.
