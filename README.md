# PrepPilot — Smart Exam Preparation & Weakness Detection

A responsive front-end prototype for competitive-exam preparation. It includes practice quizzes across five topics, topic-wise accuracy, mistake review, a simple study planner, and local browser storage.

## Run locally
Open `index.html` in a modern browser. No build tools are required.

## Deploy with GitHub Pages
1. Create or sign in to a GitHub account.
2. Create a **public** repository named `preppilot`.
3. Upload `index.html`, `style.css`, and `script.js` to the repository root.
4. Open repository **Settings → Pages**.
5. Under build/deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish and open the URL shown on the Pages settings screen.

## Current scope and limitations
- This version is a front-end prototype; it has no server-side backend, real user accounts, or shared cloud database.
- Progress is stored in the browser's localStorage on the device/browser used. It will not automatically sync across devices.
- Quiz questions are practice examples. Verify facts and answer keys against current official exam sources before using them for exam preparation.
- Do not enter sensitive personal information.
- For a full-stack internship submission, add a backend API, database, authentication, server-side validation, and tests if required by your mentor.

## Suggested next steps
1. Ask your mentor which backend/database stack is required.
2. Add server-side question storage and result history.
3. Add authentication and authorization securely.
4. Add automated tests and deployment documentation.
