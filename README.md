# Strong & Lean Journal

A 20-week training and meal journal that runs as an installable web app (PWA). Entries are stored on the device; nothing is sent anywhere.

Live app: https://mambac1ph3r.github.io/strong-lean/

## Install on your phone

- **iPhone:** open the link in Safari → Share → **Add to Home Screen**.
- **Android:** open the link in Chrome and accept the **Install app** prompt.

The installed app and the Safari tab keep separate copies of your data. If you logged anything in Safari first, use **Plan → Copy backup** there and **Paste backup** in the installed app.

## Using it

- **Today** — weight, sleep, energy, meals on plan, and the day's lift or run. On lift days, tap **↻ Repeat** to copy last week's sets in and then beat them.
- **Week** — the week at a glance, weekly average vs target, Sunday wrap-up.
- **Meals** — today's meals, this week's family dinners, tap-to-tick grocery list.
- **Progress** — weight vs the 1 lb/week target line, tempo paces, lift history.
- **Plan** — the program, and the export buttons below.

### Working with Claude

- **0600 check-in** (bottom bar) copies a short daily status to paste into your Claude chat.
- **Weekly review** (bottom bar, or Plan tab) copies a full summary of every logged week plus a request for next week's training adjustments, a new family dinner rotation, your own meal options, and a grocery list. Paste it into Claude on Sunday.

### Backup and export

- **Copy backup / Paste backup** — move your data between devices, or keep a copy somewhere safe.
- **Copy CSV** — one row per logged day, ready to paste into Numbers, Sheets or Excel.

## Deploying your own copy

1. Fork or upload these files to a public GitHub repository.
2. Go to **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, click **Save**.
3. After about a minute the app is live at `https://<your-username>.github.io/<repo>/`.

When you change `index.html`, also bump the cache name in `sw.js` (`sl-v2` → `sl-v3` and so on) so installed copies pick up the update.
