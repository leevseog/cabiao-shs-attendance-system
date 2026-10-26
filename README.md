# Cabiao SHS Attendance Monitoring Demo

A browser-based attendance dashboard concept with QR/LRN scanning UI, student roster,
attendance views, QR badge printing, and notification-log UI.

## Run locally
Open `index.html` in a browser. Camera-based QR scanning generally requires HTTPS
or localhost and permission to use the camera.

## Publish with GitHub Pages
1. Create a new repository on GitHub (for example, `cabiao-shs-attendance-demo`).
2. Upload `index.html` and this `README.md` to the repository's root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to provide the public website URL.

## Important limitations and privacy
- This is a front-end demo. Browser-local arrays are not a secure, shared database and
  may reset when the page reloads. A real multi-user system needs a backend and access control.
- Facebook/Messenger notification screens in this file should not be treated as proof that
  messages are actually sent. Real dispatch requires an authorized server-side integration
  and valid Meta permissions/tokens.
- Do not upload real student names, Learner Reference Numbers (LRNs), phone numbers,
  or social-media account links to a public repository or public website. These are sensitive
  student data. Use synthetic test records and obtain school authorization before deployment.
- This is not verified as an official Cabiao Senior High School or DepEd system. Do not
  present it as an official portal without authorization.
- The page loads third-party libraries from CDNs and uses a browser camera API for scanning.
