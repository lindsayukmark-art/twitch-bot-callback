SETUP WITH GITHUB PAGES
1. Create a PUBLIC GitHub repository named twitch-bot-callback.
2. Upload index.html and the callback folder.
3. Open repository Settings > Pages.
4. Choose Deploy from a branch, main, /(root), then Save.
5. Your URL will normally be:
   https://YOUR-GITHUB-NAME.github.io/twitch-bot-callback/callback/
6. Put that exact HTTPS URL in Twitch Developer Console > OAuth Redirect URLs.
7. Set Client Type to Public.
8. Save/create the Twitch app and copy its Client ID into Twitch Stream Control Bot v1.23.

The Device Code login itself does not use this callback for authentication.
Never publish Client Secrets, access tokens, or refresh tokens.
