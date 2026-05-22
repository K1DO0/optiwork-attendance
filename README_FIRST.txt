OPTI-WORK SOLUTIONS ATTENDANCE - READY FILES

FILES TO PASTE/REPLACE IN VS CODE:
1. index.html
2. script.js
3. style.css
4. manifest.json
5. service-worker.js

GOOGLE APPS SCRIPT BACKEND:
1. Open Google Sheets.
2. Create a blank spreadsheet.
3. Copy the spreadsheet ID from the URL.
4. Go to Extensions > Apps Script.
5. Paste code.gs there.
6. In code.gs, replace:
   SPREADSHEET_ID = 'PASTE_YOUR_GOOGLE_SHEET_ID_HERE'
   ADMIN_PIN = 'CHANGE_THIS_ADMIN_PIN'
7. Deploy > New deployment > Web app.
   Execute as: Me
   Who has access: Anyone
8. Copy the Web App URL.
9. In script.js, replace:
   GOOGLE_SCRIPT_URL = 'PASTE_YOUR_GOOGLE_APPS_SCRIPT_WEB_APP_URL_HERE'

HOW IT WORKS:
- Agent registers.
- Agent status becomes Pending.
- Admin logs in.
- Admin approves the agent.
- Agent can login and Check In / Check Out.
- Admin can Disable fired agents.
- Disabled agents cannot login or check in/out.
- Admin can view both website dashboard and Google Sheets.

DEFAULT TIMEZONE:
America/Chicago (US Central Time)

IMPORTANT SECURITY NOTE:
Do not upload code.gs to a public GitHub repo because it contains your admin PIN.
Only upload the website files to GitHub Pages.
