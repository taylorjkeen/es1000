# es1000

Spanish vocabulary trainer (Mexican Spanish focus). One self-contained `index.html` — no build step.

## Tabs

- **🏆 Top 1000** — the [1000 most common Spanish words](https://1000mostcommonwords.com/1000-most-common-spanish-words/) in four modes:
  Spanish → English and English → Spanish, each as *choose from a list* and *type it yourself*.
  A word only counts as **learned** (and stops appearing) once you've answered it correctly in all four.
  Filter by range (#1–100, …), drill a single mode or mix them, and tap 🔊 to hear the word in a Mexican Spanish voice.
  Typed answers ignore articles ("el", "to"), accept any listed meaning, and treat missing accents as correct with a reminder.
  If you typed a valid answer the list doesn't know, tap **I was right — count it**.
- **Cards / Quiz / List / Stats** — the RAE CREA / CORPES México frequency list.

Progress is saved in the browser (localStorage) on each device.

## Use it on your iPhone

1. Host it: repo **Settings → Pages → Deploy from a branch**, pick the branch and `/ (root)`.
2. Open the Pages URL in Safari → Share → **Add to Home Screen**.
3. To update, push changes and reopen the app (pull to refresh if needed).

Word list data: 1000mostcommonwords.com list, via the corrected copy in
[appinho/SALearnSpanish](https://github.com/appinho/SALearnSpanish) (`vocabs_1000.csv`).
