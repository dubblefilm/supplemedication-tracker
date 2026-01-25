# 💊 Supplemedication Tracker

A simple, beautiful PWA for tracking daily supplements and medications.

## Features

- ✅ Track supplements by time of day (morning, afternoon, evening)
- 📅 Support for different frequencies (daily, twice daily, every other day, weekly, as needed)
- 🔥 Track your streak of completed days
- 📊 View statistics and completion percentages
- 👤 Optional account system with PIN-based login
- 🔔 Generate calendar reminders (.ics files)
- 💾 Cloud sync with Supabase (when logged in)
- 📱 Works offline as a Progressive Web App
- 🌙 Beautiful gradient UI

## Setup

1. Upload all files to your web server or GitHub Pages
2. If using account features, configure Supabase:
   - Create a Supabase project
   - Create tables: `users`, `supplements`, `history`
   - Update the Supabase URL and Key in index.html

## Usage

- **Add supplements**: Click "Manage" tab, then "+ Add Supplement"
- **Track daily**: Check off supplements as you take them
- **View stats**: See your streak and completion percentage
- **Set reminders**: Click "Reminder Settings" to generate calendar files
- **Create account**: Optional - sync your data across devices

## Technologies

- Vanilla JavaScript (no frameworks!)
- Supabase for backend
- Service Workers for offline support
- PWA for mobile app-like experience

## License

MIT

---

Built by [dubblefilm](https://github.com/dubblefilm) • Powered by [noneed.dev](https://noneed.dev)
