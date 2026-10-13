# Developer Portfolio — Persona-inspired redesign

This is a personalized starter based on the uploaded `porto-persona3` template. It keeps the interactive blue, angular, game-menu-inspired visual style while changing the content toward Software Engineering, AI, and Data.

## Run locally

This is a static HTML/CSS/JavaScript site. No Node.js build is required.

1. Extract the ZIP.
2. Open the project folder in VS Code.
3. Start it with the VS Code **Live Server** extension, or run a local server from the project root:

   ```powershell
   python -m http.server 8000
   ```

4. Open `http://localhost:8000` in your browser.

Opening `index.html` directly may work, but a local server is recommended because browsers can restrict some media/audio behavior for `file://` pages.

## Personalize before publishing

Search the project for these placeholders and replace them:

- `YOUR NAME` — your preferred public name.
- `YOUR_EMAIL@example.com` — your professional email.
- `YOUR_GITHUB_USERNAME` — your GitHub username.
- `YOUR_LINKEDIN_URL` — your LinkedIn profile URL.
- `#` values in `js/main.js` inside `slinkData` — replace with actual repository/demo URLs.

Also review all skill meter values in `js/main.js`. They are starter, self-assessed visual values, not independently verified proficiency scores. Adjust them to reflect your real abilities or change them to non-numeric labels.

The project descriptions are drafted from the user's previously discussed academic and internship experience. Review each description and link it only to work you can accurately explain in an interview.

## Deploy

### Vercel
1. Push this folder to a new repository in your own GitHub account.
2. Import that repository at https://vercel.com/new.
3. Select **Other** / static site if prompted.
4. Leave the build command empty and set the output directory to `.` (the folder containing `index.html`).
5. Deploy.

### Cloudflare Pages
Create a Pages project connected to your GitHub repository. Since this is a static site, leave the build command empty and set the build output directory to `.`.

## Important before public deployment

- This starter does not include a verified license for all files inherited from the original template. Review the original repository and the license/usage rights of video clips, fonts, sound effects, and other third-party assets. Replace any assets you are not authorized to publish.
- The design was originally desktop-focused. Responsive CSS fallbacks have been added, but test the experience on multiple phones/tablets and browsers before sharing it with recruiters.
- No real contact details, project URLs, or personal photo have been inserted. The profile image is a generic placeholder.
- Do not add secrets, passwords, API keys, or private information to this static website.
