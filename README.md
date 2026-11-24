# Life Management — phone-first PWA

This is the first installable web-app prototype. It is designed for Android phones and can be hosted free on GitHub Pages.

## Included
- Home dashboard and bottom navigation
- Daily task list with completion toggles
- Habit tracker with daily check-off
- Simple goals
- Pomodoro timer (25, 50 and 15 minutes)
- Personal and Business income/expense entries
- Notes
- Light / dark / system appearance
- Local-device data storage and JSON export
- Service worker cache for offline app shell

## Install on Android
1. Upload all files in this folder to a GitHub repository.
2. In repository Settings → Pages, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
3. Wait for the Pages URL to appear. Open that HTTPS URL in Chrome on Android.
4. Chrome menu ⋮ → Add to Home screen (or Install app).
5. Open once while online so the app shell is cached. Then test airplane mode.

## Important data note
User entries are saved in browser localStorage on this device. Clearing Chrome site data, uninstalling/resetting the browser, or changing browsers can remove them. Use More → Export my data regularly. This first prototype does not yet include database encryption, lending/borrowing workflows, asset valuation, recurring reminders, or cloud sync.
