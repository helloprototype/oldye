# oldye
OldYe - Kanye West Soundwave Animation
This repository contains a web-based animation inspired by Kanye West, featuring soundwaves, mandalas, a rotating image, random quote displays, and an audio play/pause button. The project is built using p5.js and deployed as a static site on GitHub Pages.

Deployment
The project is a single index.html file hosted on GitHub Pages. Follow these steps to deploy or update it using GitHub Codespaces.

Prerequisites
A GitHub account.
The oldye repository (https://github.com/your-username/oldye).
index.html in the repository root.

Steps
Verify the Code:
Ensure index.html is in the root of https://github.com/your-username/oldye.
Check that it contains the p5.js code with Kanye quotes and animations.


Set Up Codespaces:
Go to the repository and click Code → Codespaces → Create codespace on main.
Wait for the cloud-based VS Code environment to load.


Add/Update Files:
If index.html is missing or incorrect, create/edit it in the Codespace file explorer and paste the project code.
Add this README.md by creating a new file named README.md and pasting this content.
Save all files.


Commit and Push:
In the Codespace terminal, run:git add index.html README.md
git commit -m "Add index.html and README.md for Kanye soundwave animation"
git push origin main


Enable GitHub Pages:
In the repository, go to Settings → Pages.
Set Source to Deploy from a branch, branch to main, folder to / (root).
Save and wait 1–2 minutes for deployment.
Find the URL (e.g., https://your-username.github.io/oldye/) in Settings → Pages.


Test the Site:

Visit the GitHub Pages URL.
Verify soundwaves, mandalas, quotes, image, audio, and responsiveness.
Check the browser console (F12 → Console) for errors.


Troubleshooting

Deployment Fails: Check Actions tab for errors; ensure index.html is in the root.
Page Not Loading: Verify the URL; clear browser cache.
Assets Not Loading: Ensure internet access for CDNs (cdnjs.cloudflare.com, static.wixstatic.com).
Console Warnings: Rare warnings like “Could not find valid quote position” are normal.

Usage

Access the site at https://your-username.github.io/oldye/.
Click the play/pause button to control audio.
Interact with the animation by clicking to increase soundwave complexity.

Credits

Built with p5.js.
Image and audio hosted on Wixstatic.
Inspired by Kanye West’s creative legacy.

