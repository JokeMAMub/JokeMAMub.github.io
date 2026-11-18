PERSONAL DRIVE SYNC - GITHUB PAGES

1. Sign in to GitHub. Note your exact username.
2. Create a PUBLIC repository named YOURUSERNAME.github.io
   (replace YOURUSERNAME with your real GitHub username).
3. Upload index.html, privacy.html and terms.html to the root of main.
4. Open repository Settings > Pages > Deploy from a branch > main > /(root) > Save.
5. Open these URLs, replacing YOURUSERNAME:
   Home: https://YOURUSERNAME.github.io/
   Privacy: https://YOURUSERNAME.github.io/privacy.html
   Terms: https://YOURUSERNAME.github.io/terms.html
6. On Google Auth Platform > Branding, use the exact URLs above.
   App name: Personal Drive Sync
   Support email: your email address
   Authorized domain: try YOURUSERNAME.github.io (if accepted by Google)
   Developer contact: your email address
7. On Audience, try Publish app. Google may require verification of domain ownership.
8. On Windows 8.1, reconnect rclone using the SAME config file as automation:
   C:\rclone\rclone.exe --config "C:\DelugeAuto\rclone.conf" config reconnect gdrive:
   C:\rclone\rclone.exe --config "C:\DelugeAuto\rclone.conf" lsd gdrive:

IMPORTANT:
- Never upload rclone.conf, client_id, client_secret, access/refresh tokens,
  Deluge auth files, personal Google Drive metadata, or logs to this public repository.
- GitHub Pages URLs can serve as informational pages. Google OAuth verification
  may still reject shared github.io domains or demand a verified owned domain.
- Review the privacy policy and edit any statement that is not true for your setup.
