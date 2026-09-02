# Byte the Bullet — Live Quiz

## Deploy on GitHub Pages (one-time setup, ~2 minutes)

1. Go to [github.com](https://github.com) and create a new repository (e.g. `byte-the-bullet`). Public is fine.
2. Click **Add file → Upload files**, and upload `index.html` from this zip.
3. Commit the upload.
4. Go to the repo's **Settings → Pages**.
5. Under "Build and deployment", set **Source: Deploy from a branch**, **Branch: main / (root)**. Click **Save**.
6. Wait about a minute, then refresh — GitHub shows your live link, something like:
   `https://YOUR-USERNAME.github.io/byte-the-bullet/`

That link is your permanent quiz URL. Bookmark it.

## Running the event

1. On your hosting device (laptop/projector), open your GitHub Pages link and tap **Host a Game**.
2. It automatically creates a fresh room and shows a **QR code** + link right on screen.
3. Students open the same GitHub Pages link on their phones, or just scan the QR code — either way they land straight in your room.
4. They type a team name and tap **Join Room**.
5. Once your teams are all in, tap **Start Game**. Each question runs for 10 seconds, then reveals the answer and an animated live leaderboard, automatically advancing through all three rounds (SALT, PEPPER, SOUR) to a final celebration screen.

## Important: do a dry run first

This version uses a free, public, no-signup database (kvdb.io) so it works from GitHub Pages instead of only inside Claude. It has **not** been live-tested end to end — please test with 2–3 phones before your actual event:

- Open your GitHub Pages link, host a room, and join it from a second device.
- Answer a question and confirm the leaderboard updates.
- If something doesn't work, open your phone/laptop browser's developer console (or just note what happened) and share the details — it can be patched quickly.

## Files in this zip

- `index.html` — the whole app (upload this to GitHub)
- `Byte_the_Bullet_Code_Walkthrough.pdf` — a beginner's explanation of every HTML/CSS/JS piece used in `index.html`
- `README.md` — this file
