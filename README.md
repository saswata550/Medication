# Medication

A small reminder web app for two daily doses, after breakfast and after lunch.

- **Gets more insistent** the longer a dose isn't marked as taken. You can choose how persistent it is: gentle, normal or annoying.
- **Snooze** for 10, 30 or 60 minutes.
- **"Hab gerade gegessen"** reminds you a set number of minutes after a meal, whatever the clock says.
- **"Heute ist anders"** moves or skips a dose for today only.
- **Music link** (Spotify/YouTube) appears with the reminder.
- **7-day history.** All data stays in the browser on that device (localStorage).

Reminders only fire while the page is open (a background tab or the home-screen app counts). This app is not a medical device; keep a calendar or alarm as a backup.

## Run

Static files only. Enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / root) and open
`https://<user>.github.io/Medication/`. On a phone: Share → *Add to Home Screen*.
