# Sessions

# On startup

At start of a session ALWAYS read
 1. The most recent `sessions/*-user.md` file
 2. A few recent `sessions/*.md` files, excluding `sessions/*-user.md`

These will show you what we were just talking about

# When chatting

Read further back as needed


# On shutdown

Write a session file to include what we talked about in this session
    The file should be named like `sessions/<date>-<app>.md` 
    Include any older context that is still relevant

## Filename

Where 
 - `<date>` is the current date and time
   - using YYYY-MM-DD-mm-hh
 - `<app>` is the name of the app hosting `Claude`, which is one of
   - `web` when Claude is being accessed via the web
   - `app` when Claude is being accessed via the Mac App
   - `cli` when Claude is being accessed via the command line (aka "Claude Code"
   - `ios` when Claude is being accessed via the iPhone

For example:
  - `sessions/2025-03-31-03-30-cli.md` was written early on the 31st of March, from Claude Clode
  - `sessions/2025-04-01-12-00-web.md` was written at noon on April Fool's Day, from the WWW UI
  - `sessions/2025-04-02-22-22-app.md` was written late at night on the 2nd of April, from the Mac App

## Contents

A session file should have some of these headings

If it has any more headings, they should appear after these

- Project Understanding
- Investigations
- Implementation Details
- Next Steps
- Questions Raised
