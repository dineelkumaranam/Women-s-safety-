# Women's Safety Campus Escort Request System

A beginner-friendly campus safety escort request prototype.

## Features
- Student submits name, student ID, phone, pickup/current location, destination, and requested pickup time.
- Request timestamp is automatically recorded by the server.
- Student can optionally use browser geolocation to fill latitude/longitude.
- Requests are saved in `data/requests.json`.
- Admin dashboard displays requests and allows status changes:
  Pending -> Accepted -> Escort Assigned -> Completed / Cancelled.
- No external database is required.

## Requirements
- Node.js 18+
- Modern browser

## Run
1. Open a terminal in this project folder.
2. Run:
   `npm install`
3. Run:
   `npm start`
4. Open:
   `http://localhost:3000`

## Important
This is an educational prototype, not a production emergency/safety system.
For real campus deployment, add authentication, HTTPS, role-based access control,
encrypted storage, audit logs, secure database storage, rate limiting, CSRF protection,
input validation, monitoring, and a real-time alert/notification system.
Do not rely on this app as a substitute for campus security or emergency services.
