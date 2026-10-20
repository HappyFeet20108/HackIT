# Ripple

Ripple is a small, single-page app that helps people discover how they like to give and find volunteer activities that fit. Take a short quiz to get a giving type and style, then explore a personalized feed and track the time you give.

## Run it

There is no build step or package installation. Open `Ripple_ what kind of giver are you_ (2).html` in a browser. You can also serve the folder locally, for example with Python:

```powershell
python -m http.server 8000
```

Then open <http://localhost:8000> and select the HTML file.

## Features

- A 12-question quiz with results across eight causes and four giving styles.
- A volunteer activity feed with matching, sorting, cause, time, and first-timer filters.
- Optional preferences for communities, age, experience, and available time.
- Saved activities, activities you plan to attend, and links to external sign-up pages.
- A personal journey log with hours, streaks, reflections, badges, levels, and a shareable progress card.
- A class and school leaderboard interface for the demo.

## Data and event information

Quiz results, preferences, saved activities, and journey entries are stored in your browser's local storage. There is no account or server sync, so the data is specific to that browser. Use **Clear everything** in the Journey section to remove it.

The leaderboard uses sample class and school totals; it does not collect or combine data from other users. Volunteer listings, dates, availability, eligibility, and estimated time commitments can change. Confirm details on the linked organizer page before making plans.

The page loads the Bricolage Grotesque font from Google Fonts when available and falls back to system fonts otherwise.

## Project files

- `Ripple_ what kind of giver are you_ (2).html` contains the app, styles, and client-side logic.
- `README.md` contains these project notes.

