# Volunteer Schedule

The shared web page for department volunteer schedules.

This project holds **page code only**. Each department keeps its own schedule and contact sheets in its own
Google account, with its own Apps Script web app. A personal link looks like:

```
https://volunteer-schedule.github.io/?app=THEIR-APP-ID&code=THEIR-ACCESS-CODE
```

The page reads the department's app ID from the link and talks straight to that department's Apps Script.
No schedule data, names, phone numbers, or access codes are stored here.

`index.html` is generated from the Apps Script project's `Index.html` by `build_page.py`; edit it there, not here.
