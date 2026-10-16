# ACE Field Evidence: deploy the demo

This folder is a static site. The whole app is in index.html, so it needs no build step and no server.

## Option A: Vercel (quickest, gives a public link)
1. Install Node.js from nodejs.org (LTS version).
2. Open Terminal, go into this folder, and run:
       npx vercel
3. Log in when asked, accept the defaults, and choose a project name such as ace-field-evidence.
4. Vercel prints a link like https://ace-field-evidence.vercel.app. Run `npx vercel --prod` to make it the live address.
5. Open the link on your phone to show the mobile version.

## Option B: GitHub Pages (free, lives in your GitHub account)
1. On github.com, create a new public repository, e.g. ace-field-evidence.
2. Upload index.html and .nojekyll to the repository (Add file > Upload files).
3. Go to Settings > Pages. Under Source, choose "Deploy from a branch", branch main, folder /(root). Save.
4. After about a minute the site is at https://YOUR-USERNAME.github.io/ace-field-evidence/

## Before sharing the link
- Sign-in is a demo. Any password works, and the Demo role menu switches between Admin, Verifier and Field Team.
- Data is sample data and resets on refresh.
- The splash plays for 7 seconds on every page load.
