# Myfirstad Attendance v1

Browser-based attendance dashboard for the Myfirstad team.

## Included
- Employee and admin login
- Check in / check out
- Present / Late / Absent status
- Attendance history
- Leave applications and admin approval
- Leave balances
- Holiday calendar
- Employee management
- Monthly report
- CSV export
- Responsive employee interface

## Demo accounts
Admin: admin@myfirstad.in / admin123

Employee: rahul@myfirstad.in / 123456

## Run
Open index.html in a browser, or serve the repository with any static web server.

## Important
This v1 stores data in browser localStorage. It is a functional prototype, not yet a shared production attendance system. For office-wide use, the next version should move authentication and attendance data to Supabase/PostgreSQL and add server-side authorization, audit logs, backups and optional office GPS/Wi-Fi verification.
