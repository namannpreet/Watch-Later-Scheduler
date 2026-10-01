# Watch-Later-Scheduler


# Watch Later Scheduler

**Live demo:** [your GitHub Pages link]

A simple tool that turns your "Watch Later" backlog into scheduled time on your Google Calendar, so saved videos actually get watched.

## The problem

Saving a video for later is easy, but nothing reminds you to come back to it. Most people's Watch Later lists keep growing and rarely get watched. I had this problem myself, and when I asked friends, most of them did too.

## How it works

1. Add the videos you want to watch, with their length.
2. Connect your Google Calendar.
3. The tool finds free slots in your schedule and books each video in as a calendar event, with the link included.

## How I built it

- **Validated the idea first:** Before writing code, I tested a no-code prototype (Glide + Make) to see if people would actually use scheduled watch time.
- **Planned it:** Wrote a short PRD and designed the database schema.
- **Built the MVP:** Python and SQL backend, with Google Calendar integration through OAuth2, including handling for edge cases like overlapping events and videos longer than any free slot.

## Tech stack

Python, SQL, Google Calendar API (OAuth2), HTML

## What I'd do differently

I focused on getting videos onto the calendar, but the real goal is getting them watched. Next time, I'd track "scheduled videos actually watched" from day one, and test with more users earlier, since a calendar block is easy to ignore.

## Note

This is a prototype built as a personal project. [If the live demo doesn't connect to Google Calendar, mention that here, e.g. "The live demo shows the interface; calendar sync runs locally."]
