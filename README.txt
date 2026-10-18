CIRCLE CHAMPIONS — ONLINE ROOM CODES

Both players visit the SAME public website. Player 1 clicks Create Room and
shares the 6-character code. Player 2 enters the code and clicks Join Room.
No local IP address, Python install, or Wi-Fi sharing is needed on player PCs.

FREE HOSTING WITH RENDER (requires a free Render account and GitHub account):
1. Extract this ZIP.
2. Create a NEW GitHub repository and upload index.html, server.py,
   requirements.txt, and render.yaml to the repository root.
3. On render.com, choose New > Blueprint and connect your repository.
4. Confirm the free web service and deploy it.
5. Render will give you a public https://...onrender.com address.
6. Open that same address on both PCs and use Create Room / Join Room.

NOTES:
- The online address is assigned after deployment; the ZIP itself is not live.
- Free Render services can sleep when inactive. First visit after sleeping
  may take a minute; refresh if necessary.
- Rooms are temporary and reset when the server restarts.
- All players in a room must connect to the SAME running server instance.
- The game is an experimental multiplayer build; gameplay synchronization
  has not been fully browser-tested.
- You can test locally by running `pip install -r requirements.txt`, then
  `python server.py`, then opening http://localhost:8000.

CUSTOM LOGO UPDATE: logo.png and favicon.png must be uploaded alongside index.html in the GitHub repository root. On GitHub upload the updated index.html, logo.png and favicon.png; commit changes and Render should redeploy.
