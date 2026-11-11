# Campus Pulse

> **See what's happening on campus this week, pick what you'll attend, and spot schedule clashes before they happen.**

A responsive single-page web app for students to browse weekly campus events, build a personal schedule, and get warned when two events overlap. No frameworks, no build step: just one `index.html`.

## 🚀 Features

- **Weekly Event Explorer**: Filter by day (Mon to Sun), category (Talks, Clubs, Sports, Music, Workshops, Wellness), or search by title and venue.
- **One-Click Scheduling**: Press **Add** to put an event in *My schedule*, grouped by day and sorted by time.
- **Clash Detection**: Overlapping events are highlighted in orange so you can fix them early.
- **Copy Schedule**: Copy your week as plain text to share in a group chat.
- **Local Persistence**: Your schedule is saved in your browser's LocalStorage.

## ✏️ Customize

Open `index.html` and edit the `EVENTS` array near the bottom. Each event looks like this:

```js
{id:15, title:"Chess Club", venue:"Library Room 2", cat:"Clubs", day:2, s:17, e:18.5}
```

- `day`: 0 = Mon … 6 = Sun
- `s` / `e`: start and end time in 24-hour decimals (`18.5` = 6:30 PM)
- Use a unique `id` for every event.

---

## 🛠️ Publish on GitHub Pages

### Step 1: Create a repository
1. Log in to [GitHub](https://github.com/).
2. Click **+** (top right) → **New repository**.
3. Name it (e.g., `campus-pulse`), set it to **Public**, and click **Create repository**.

### Step 2: Upload files
1. Click **uploading an existing file**.
2. Drag in `index.html` and `README.md`.
3. Click **Commit changes**.

### Step 3: Turn on GitHub Pages
1. Go to **Settings** → **Pages**.
2. Under **Build and deployment**, choose your `main` branch and the `/ (root)` folder, then **Save**.
3. After 1 to 2 minutes your site is live at:
   `https://<your-username>.github.io/campus-pulse/`

## 💻 Run locally

Download the files and double-click `index.html` to open it in any browser.
