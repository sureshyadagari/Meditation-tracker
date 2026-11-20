# Meditation Tracker

A single-file offline web app for an Amritvela log (wake-up time, minutes, a 1–5 rating, a Murli read counter, and a note), a Yes/No for “Did you churn or practice a point?”, Aaj ka checking (“Aaj kuch prapthi huaa?” and “Purity bada?”), and traffic control at 5:45, 7:00, 10:30, 12:30, 17:30, 19:30, and 21:30. The Amritvela wake target is 3:30 AM, and Progress shows a wake-by-3:30 streak and simple charts. Everything runs in the browser: inline CSS and JavaScript, no network calls.

Yaad ka chart records the day’s total remembrance time in hours and minutes, and Progress charts that time.

Before sleep records three Yes/No checks: pothamel to Baba, at least 10 minutes of meditation, and no phone.

“Did you wake up for Amritvela?” is a Yes/No gate: No hides wake-up time, minutes, and rating, and saves those as 0.

Open it at [https://sureshyadagari.github.io/Meditation-tracker/](https://sureshyadagari.github.io/Meditation-tracker/). On a phone, use the browser’s Add to Home Screen so it opens full screen.

Entries stay only in that phone’s browser storage. They are not saved on GitHub or any server. Use **Backup** and **Export** to download a JSON copy and keep that file somewhere safe. Clearing site data, or opening the app in another browser, starts empty unless you import that export.
