# Visa Service Workspace (independent demo)

A mobile-friendly independent demo for organizing visa-related application records. It is not a German government website, does not submit applications to authorities, and does not provide official appointments or decisions.

## Run locally
- Node.js 18+
- `npm install`
- `npm start`
- Open `http://localhost:3000`

## Render deployment
Create a Render Web Service from this repository/archive after uploading the files. Build: `npm install`; Start: `npm start`. Set `JWT_SECRET` to a long random secret. Optional admin login requires both `ADMIN_EMAIL` and `ADMIN_PASSWORD` environment variables.

## Demo limitations
This starter stores JSON and uploaded files on the local filesystem. On Render's free ephemeral filesystem, records/uploads can be lost on restart or redeploy. Do not collect real passport, identity, or sensitive visa documents until a secure persistent database/storage, access controls, privacy notice, and production security review are implemented.
