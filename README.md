# Bahi - Static Billing & Inventory Demo

This is a static, browser-only demonstration rebuilt from the supplied PHP project theme and module concepts. It does not run PHP and does not connect to MySQL or any other database.

## Run locally

Open `index.html` in a browser, or publish this folder with GitHub Pages.

## Demo login
- Username: `admin`
- Password: `demo123`

## Included demo areas
- Dashboard
- Sales and purchase entry
- Product catalogue (add, edit, delete)
- Stock overview
- Reports and CSV export
- Demo users/roles view
- Local demo settings

## Important limitations
- Login is only a client-side demo gate; it is not secure authentication.
- Records are stored in browser `localStorage` and do not sync between users or devices.
- Browser storage can be cleared. This is not suitable for real billing, customer data, inventory operations, or production use.
- The original PHP source is not included in this static deployment package.

## Publish with GitHub Pages
1. Create a new repository or use a separate branch/folder for this static build.
2. Upload `index.html`, `style.css`, `app.js`, and this README.
3. In GitHub, open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Select the branch and `/ (root)` folder, then Save.
6. Wait for GitHub Pages to provide the public URL.

No Render service or Dockerfile is required for this static version.
