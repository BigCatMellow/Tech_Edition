# Tech Edition — Fresh Chat Handoff

Use this file to continue Tech Edition work in a fresh ChatGPT conversation without relying on the original build chat.

## Start here

Repository: `BigCatMellow/Tech_Edition`

Read these before publishing or changing behavior:

1. `EDITORIAL_GUIDE.md` — canonical editorial rules, discovery model, sections, quality controls, and data contract.
2. `index.html` — GitHub Pages reader UI.
3. `data/latest.json` — current live data shape.
4. `README.md` — project overview and file layout.

Email delivery lives in `BigCatMellow/Notes`:

- `scripts/send_tech_edition.py`
- `.github/workflows/daily-tech-edition.yml`
- `data/tech-edition-trigger.txt`

Do not expose or modify SMTP secrets.

## Daily publication workflow

1. Research broadly on the current web and GitHub.
2. Follow `EDITORIAL_GUIDE.md` as the canonical specification.
3. Search known interests **and** deliberately branch into adjacent mechanisms the reader may not know to search for.
4. Use New, Emerging, and Unearthed discovery horizons.
5. Inspect original project pages, code/repository activity, papers, issues, releases, or demonstrations where practical.
6. Be explicit about uncertainty, maturity, limitations, and hype.
7. Produce `lead_stories`, the editorial sections, and a `rabbit_hole` item when a strong candidate exists.
8. Write substantial `reader` synthesis for items that benefit from a mechanism-level explanation. Do not copy source articles.
9. Publish the completed edition to:
   - `data/latest.json`
   - `data/archive/YYYY-MM-DD.json`
   - `editions/YYYY-MM-DD.md`
10. Only after publication succeeds, update `BigCatMellow/Notes/data/tech-edition-trigger.txt` with the Eastern Time date and the edition's `generated_at` timestamp.
11. Never update the email trigger if publication failed or the edition is incomplete.

## Editorial behavior that must survive future changes

- This is **not** a mainstream tech-news digest.
- GitHub is a major source, not the only source.
- Stars are not a quality ranking.
- AI agents receive sustained attention without turning the paper into an AI newsletter.
- Old discoveries remain eligible.
- The `You Probably Didn't Know You Were Interested In This` section is a core feature, not filler.
- `Mechanisms Worth Studying for MAPS` asks what is worth understanding, not what should be copied into MAPS.
- Corporate funding news, wrapper projects, trivial releases, AI-generated repo spam, and generic lists are normally excluded.
- The paper should create the reaction: **“I didn't know people were doing that.”**

## Website behavior

`index.html` is data-driven. New editions should not require hard-coded article changes.

The design follows Morning Edition's restrained newspaper approach but uses a slightly more technical visual vocabulary: warm paper, serif editorial display type, compact monospace metadata, subtle alternating article surfaces, and a dark rabbit-hole block. Do not turn it into a neon “hacker” dashboard or generic card grid.

The archive drawer reads `data/archive/*.json` directly from GitHub. Expanded reader material may be embedded in the edition or loaded from `data/readers/YYYY-MM-DD.json`.

## GitHub editing rules

- Fetch before overwriting existing files.
- `update_file` requires the current blob SHA.
- Do not use stale SHAs.
- Do not parallel-write the same path.
- Preserve working behavior unless the requested change requires changing it.
- Do not claim a paper or email is published until the relevant GitHub writes succeed.

## Fresh-chat prompt

> Continue my Tech Edition project from GitHub. Use `BigCatMellow/Tech_Edition/NEW_CHAT_HANDOFF.md` as the handoff, then read `EDITORIAL_GUIDE.md`, `index.html`, and `data/latest.json` before making changes. Treat the repository as the source of truth. Use current web research and connected GitHub data for daily discovery. Preserve the publish → archive → email-trigger workflow.

For a manual edition run, add:

> Run a fresh Tech Edition now, publish it according to the handoff and editorial guide, then update the existing email trigger only after publication succeeds.
