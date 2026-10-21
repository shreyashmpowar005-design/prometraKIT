# Synthetic Promoter Strength Predictor

Static website deployment package for the mini-project.

## Files
- `index.html` — website page
- `render.yaml` — Render configuration
- `.gitignore` — common files to ignore in Git
- `README.md` — deployment instructions

## Deploy with GitHub and Render
1. Create a new GitHub repository.
2. Upload all four files to the repository's root folder.
3. In Render, choose **New +** → **Static Site**.
4. Connect your GitHub repository.
5. Set the publish directory to `.` and leave the build command blank.
6. Click **Deploy Static Site**.

If Render reads `render.yaml`, check that it is configuring a **Static Site** with `.` as the publish directory.

## Important
This is a static HTML site. Any login/profile interface implemented only in the page is not secure server-side authentication and does not create a database or real user accounts.
