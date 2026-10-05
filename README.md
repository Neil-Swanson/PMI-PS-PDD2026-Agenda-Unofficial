# PDD 2026 Planner

An unofficial, single-page schedule planner for Professional Development Days 2026, the PMI Puget Sound Chapter conference on October 9 and 10, 2026 at Seattle University (Pigott Building).

Attendees choose one Primary session per time block and any number of Alternates, filter the agenda by their picks, check their plan for overlaps, share it with a link, and add it to their calendar. Everything runs in the browser. There is no server, no account, and no tracking.

The official agenda is the source of truth. This planner is unofficial and built from the agenda as published on October 5, 2026. Rooms, times, and speakers can change, so always check the official PDD 2026 agenda from PMI Puget Sound Chapter for the latest.

Live site: https://neil-swanson.github.io/PMI-PS-PDD2026-Agenda-Unofficial/

## Features
 
- **Pick sessions:** each session card has **Primary** and **Alternate** buttons. Choosing a new Primary in a time block moves the old one to Alternate, so each block has exactly one Primary. Alternates are unlimited.
- **Two views:** **Full agenda** shows every listing. **My schedule** shows only your picks, with a note on blocks where you have not chosen anything yet.
- **Filters:** filter by track (PM & CAPM Foundations, AI & Digital Transformation, Leadership & Career Development, PMO & Portfolio, Agile & Project Execution, Change Management, Military Outreach, College PM Bowl, and keynotes, panels, and events). In the Full agenda you can also show All, Primary, Alternate, or Unselected.
- **Always-visible items:** keynotes (blocks with only one session) have no Primary or Alternate buttons and are always shown. Non-session items such as registration, welcomes, meals, and the Career Fair open and close times are always shown too.
- **Schedule check:** flags overlapping Primary picks, tight room changes (5 minutes or less between different rooms), and sessions that run into lunch.
- **Share:** a share link or short code lets someone else load the same schedule. Opening a link when you already have picks asks whether to replace them.
- **Calendar download:** an `.ics` file with your Primary picks, the three keynotes, and the Friday evening reception. Alternates can be included as tentative events.
- **Light and dark themes:** follows the device setting.
- **Phone friendly:** a single responsive layout that works on phones and laptops.
## How to use it
 
1. Browse the agenda. Use the track chips and the **Show** filter to narrow what you see.
2. On any session card, select **Primary** for your first choice in that time block, or **Alternate** for a backup.
3. Switch to **My schedule** to see just your plan.
4. Review the **Schedule check** panel for overlaps or tight transitions.
5. Use **Share link** to send your plan to someone, or **Add to calendar** to download an `.ics` file and open it in your calendar app.
6. Use **Import picks** to load a share link or code, and **Clear all picks** to start over. **Load an example plan** fills in a sample plan if you want to see how it works.
Your picks are saved in your browser on the device you are using. To move them to another device or browser, use a share link or code.

## Known limitations
 
- **Picks stay on one device.** They are stored in the browser. Use a share link or code to move them.
- **End times are incomplete.** The agenda lists end times for only some sessions, so overlap checks and calendar durations are approximate.
- **Some rooms were unconfirmed.** Several Military Outreach sessions were still showing "coming soon" or pending rooms when the agenda was read.
- **The agenda can change.** Update the data in `index.html` when the chapter changes it, and tell users to confirm against the official agenda.
- **Some embedded viewers block downloads and links.** The calendar download and share link work in a normal browser tab, but may not work inside a preview pane or an embedded frame.
- **Fonts need internet access.** Without it, the page falls back to system fonts.

## Credits and disclaimer
 
Planner built by [Neil Swanson](https://www.linkedin.com/in/neil-p-swanson). Feedback and connections are welcome on LinkedIn.
 
This is an unofficial project. The agenda content, session titles, and speaker names belong to PMI Puget Sound Chapter and the speakers. The official agenda is available at [pugetsoundpmi.starchapter.com](https://pugetsoundpmi.starchapter.com/meetinginfo.php?id=1011) and is the source of truth.
 
## License

The code in this repository is released under the [MIT License](LICENSE).

The agenda content, including session titles, speaker names, and descriptions, is not covered by this license. It belongs to PMI Puget Sound Chapter and the speakers, and the [official agenda](https://pugetsoundpmi.starchapter.com/meetinginfo.php?id=1011) is the source of truth.
