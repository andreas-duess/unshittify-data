# unshittify data

Every entry from [unshittify.dev](https://unshittify.dev): people making hardware they own useful again with AI-assisted development and open source. Smart TVs without the ads, devices brought back after their cloud shut down, printers and scanners with new drivers, old computers on a new OS.

- `data/projects.json`: all entries, same fields as the site
- `data/projects.csv`: the same, one row per entry, for spreadsheets

Live GitHub star counts for each `repo`, refreshed hourly, are at <https://unshittify.dev/stars.json>. They change too often to belong in this dataset.

Updated automatically each time the site is published. The live versions are always at <https://unshittify.dev/projects.json> and <https://unshittify.dev/projects.csv>.

## Fields

| Field | What it is |
|---|---|
| `id` | Entry number, in the order entries were added |
| `slug`, `url` | The entry's page on unshittify.dev |
| `title` | Project name |
| `device` | The hardware it works on |
| `category` | `tv`, `make`, `home`, `audio`, `computer` or `vehicle` |
| `ai` | Which AI tool the builder credits, if any (`none documented` when none) |
| `evidence` | `public` (code or detailed materials are published), `report` (the builder describes their result, not reproduced) or `experimental` (still unsettled) |
| `aiRole` | What the AI did, in the builder's account |
| `caveats` | What doesn't work, or what to know before trying it |
| `evidenceNote` | What the evidence label is based on |
| `repo` | The project's own GitHub repo (`owner/name`), when it has one |
| `added` | Date the entry was first added to unshittify |
| `links` | Sources: the project's repo or site, write-ups, discussion |
| `reviewed` | Date unshittify last checked the entry |
| `submittedBy` | `unshittify` for editorial entries, otherwise the contributor |
| `summary` | One-paragraph description |

None of the evidence labels mean "tested by unshittify". We haven't tested any of it. Read each project's own documentation before you buy hardware or flash anything.

## Licence

The data is published under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0). Use it for anything, including commercially, as long as you credit **unshittify.dev** with a link.

The projects themselves belong to their builders, under their own licences. This dataset only describes them and links to them.

## Corrections and new entries

Spotted a mistake, or built something that belongs here? Use the form at <https://unshittify.dev/#submit>. Pull requests to this repo aren't merged, because it's overwritten from the site on each update.
