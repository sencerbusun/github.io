# Library: articles & documents

The "Library" section on may21.org lists every entry in `documents.json`
(in the main folder of this repo). Newest dates appear first.

## To publish something

1. **If it's a file** (PDF, Word, image): upload it into this `documents` folder.
   On github.com: open the folder → **Add file → Upload files** → commit.
   Use a simple file name without spaces, e.g. `statement-2026-05-21.pdf`.
2. **Open `documents.json`**, click the pencil icon, and add an entry:

```json
[
  {
    "title": "Statement on May 21, 2026",
    "date": "2026-05-21",
    "type": "Statement",
    "lang": "EN",
    "description": "One or two sentences about the document.",
    "url": "documents/statement-2026-05-21.pdf"
  }
]
```

- `title` and `url` are required; the rest is optional.
- `url` is either a file in this folder (`documents/…`) or a full link to an
  article elsewhere (`https://…`).
- Separate entries with a comma. The whole list stays inside `[` `]`.
- `date` uses the format `YYYY-MM-DD`.

3. Commit. The site updates within a minute or two.
