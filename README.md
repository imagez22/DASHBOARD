# Carifika Dashboard

A responsive organizational dashboard built with plain HTML, CSS, and JavaScript — no frameworks, no build step. It covers a home overview, an events schedule, an upcoming-meetings list, and a change-password flow, with light/dark theming and a collapsible sidebar on mobile.

**[Deploy your own copy to Vercel](https://vercel.com/new/clone?repository-url=https://github.com/imagez22/DASHBOARD)**

## Features

- **Home** — profile card, project progress cards, announcements, and active-collaborator list
- **Events** — day-by-day schedule with next/previous navigation
- **Meetings** — upcoming meeting list
- **Change Password** — client-side validated password form (current/new/confirm checks, success/error feedback)
- **Logout** — confirmation prompt with a logged-out state screen
- Light/dark theme toggle
- Responsive layout with a mobile slide-in sidebar

## Tech stack

Vanilla HTML5, CSS3, and JavaScript (ES6). No dependencies, no bundler — open it directly or serve it with any static file server.

## Project structure

```
.
├── index.html      # Home page
├── event.html      # Events schedule
├── meeting.html    # Upcoming meetings
├── password.html   # Change password form
├── app.js          # Shared behavior: theme toggle, sidebar, logout, password form
├── event.js        # Sample weekly schedule data
├── style.css       # Global styles, theme variables, responsive layout
└── images/         # Logo and profile photos
```

## Getting started

Clone the repo and open `index.html` in a browser:

```bash
git clone https://github.com/imagez22/DASHBOARD.git
cd DASHBOARD
open index.html   # or just double-click it
```

Or serve it locally (recommended, since some browsers restrict local file access):

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Deployment

This is a static site, so it deploys to [Vercel](https://vercel.com) with zero configuration — import the repo in the Vercel dashboard, or click the deploy button above.

## License

[MIT](LICENSE)
