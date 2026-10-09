# Encore music league prototype

A dependency-free, responsive web prototype based on the attached product requirements.

## Open it

Open `index.html` in a modern browser. No build step or account is required.

## Included in this first build

- Global home with realistic seeded leagues, deadlines, round status, and contextual actions
- League reordering with accessible up/down controls
- League home with voting, submission, and between-round states
- Prior round podium and future round schedule
- Prior-song search interaction
- In-league navigation for Home, Standings, Round Results, Stats, and Chat
- Three next-round methods: an admin-set schedule, a league vote with an optional minimum-voter threshold, or a rotating player picker
- Separate league-creation pages for the date-based schedule and round themes, with an editable theme and description per round
- Round prompt choices for rotating pickers, plus a submission and voting calendar preview for every round
- Optional rotating round-theme picker, including a prompt library, custom prompts, and picker attribution in results
- League chat with admin announcements, pin/unpin controls, and a pinned-announcements panel
- Chat reactions for thumbs up, laughter, questions, and thumbs down
- Larger league navigation island at the top of league pages that docks to the bottom while scrolling
- Voting flow with vote allocation, own-submission protection, guesses, comments, autosave, and confirmation
- Apple catalog artwork and streamed song previews when an exact catalog match is available
- Separate Guess Who review page with editable picks and an optional lock action
- Full round results list and details, including voters and comments
- League-wide standings and stats, with a working CSV download
- Profile/preferences, league information, and settings entry points
- Responsive layout designed for phone and desktop widths

## Prototype boundaries

This is still a frontend prototype. League data and scores are sample data; vote/comment/guess progress, chat, suggestions, and next-round voting are saved in this browser only, so they are not shared across players yet. Preview artwork and clips use exact matches from Apple's public catalog search when available, with an Apple Music link beside the song. Authentication, shared persistence, Spotify search, submission validation, canonical playlist generation, and server-side scoring still need backend/service implementations.
