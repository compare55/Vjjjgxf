# Render deployment (Hinglish)

## Render Static Site settings
- Build Command: `npm install && npm run build`
- Publish Directory: `dist`

`render.yaml` is included with these settings for Render Blueprint deployments.

## Important limitation
This project is a frontend visual clone. `src/main.js` connects to the external Socket.IO endpoint `https://mw.artwear.ge` and loads plane artwork from `https://aviator-demo.spribegaming.com`. Hosting this ZIP on Render does not host or control those external services. The game may not work if those services are unavailable, block the connection, or change. This ZIP does not include the backend/game-round server.

The existing game source, visual assets, sounds, and animations have not been intentionally changed for this Render setup.
