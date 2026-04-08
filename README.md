# WA 70/720 Club Rankings

A GitHub Pages site that fetches and ranks WA 70/720 scores from Archers Diary.

## Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `club-rankings`)
2. Upload `index.html` to the repo root
3. Go to **Settings → Pages → Source → Deploy from branch → main**
4. Your site will be live at `https://yourusername.github.io/club-rankings`

## Usage

### Automatic fetch
Type an archer's name exactly as it appears on Archers Diary and click **Fetch scores**.
The site tries two methods to get the data — direct fetch and via a CORS proxy.

### Manual import (if fetch is blocked)
1. Go to [archersdiary.com/MyEvents.aspx](https://archersdiary.com/MyEvents.aspx)
2. Search for the archer's name and let the results load
3. Press `Ctrl+U` to view page source
4. Select all (`Ctrl+A`), copy, and paste into the Manual Import panel
5. Enter the archer's name and click **Import scores**

Scores are saved in your browser's localStorage — they persist between visits.

## Features

- Best score / best in last 12 months / all scores views
- Filter by division (Recurve, Compound, Barebow)
- Sortable columns
- Export to CSV
- Clickable links to scoresheets on Archers Diary
- Score progress bar for quick visual comparison
