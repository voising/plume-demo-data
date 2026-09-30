# Plume demo data

Sample journal used by Plume's hidden Creator Demo (Settings > About, tap the version seven times).

- `demo-en.json`: English sample journal. Add `demo-<lang>.json` (for example `demo-fr.json`) and the app picks it up for that language, falling back to English.
- Dates are relative: `daysAgo: 0` is the day the app is opened, so the journal always ends today.

Format:

```json
{
  "goal": { "mantra": "...", "details": "...", "icon": "sf.symbol.name" },
  "entries": [
    {
      "daysAgo": 0,
      "gratitudes": ["..."],
      "memories": ["..."],
      "dreams": ["..."],
      "accomplishments": ["..."],
      "journal": "...",
      "todos": [{ "title": "...", "completed": false }]
    }
  ]
}
```

Everything here is fictional.
