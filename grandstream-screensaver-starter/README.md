# Grandstream GRP2612 Screensaver on GitHub Pages

This starter contains a working `screensaver.xml` and four 320×240 PNG placeholders.
Replace the placeholder images with your own and update the URLs in `screensaver.xml`.

## What you need
- A GitHub account
- Your four images sized 320×240 px as PNG or JPG

## Folder structure
```
grandstream-screensaver/
├─ screensaver.xml
└─ images/
   ├─ img1.png
   ├─ img2.png
   ├─ img3.png
   └─ img4.png
```

## Step-by-step
1. Create a new public repository on GitHub named `grandstream-screensaver`.
2. Upload all files from this folder to the repository, keeping the same structure.
3. Enable GitHub Pages: open the repository → Settings → Pages → Build and deployment → Source = Deploy from a branch → Branch = main, folder = /root → Save.
4. After a minute, your site will be live at:
   `https://USERNAME.github.io/grandstream-screensaver/`
5. Edit `screensaver.xml`. Replace `USERNAME` with your GitHub username and `REPO` with your repository name. If you used `grandstream-screensaver`, the full URLs will look like:
   - `https://USERNAME.github.io/grandstream-screensaver/images/img1.png`
   - `https://USERNAME.github.io/grandstream-screensaver/images/img2.png`
   - `https://USERNAME.github.io/grandstream-screensaver/images/img3.png`
   - `https://USERNAME.github.io/grandstream-screensaver/images/img4.png`
6. Commit and push the change. Wait a minute for Pages to redeploy.
7. Open `https://USERNAME.github.io/grandstream-screensaver/screensaver.xml` in a browser to confirm it loads and the image URLs are correct.

## Configure your Grandstream GRP2612
1. Find the phone IP address on the handset menu then open it in a browser.
2. Login to the Web GUI.
3. Go to Preferences and locate the Screensaver Server Path.
4. Paste the URL to your XML, for example:
   `https://USERNAME.github.io/grandstream-screensaver/screensaver.xml`
5. Set the Screensaver XML Download Interval to a positive value so updates are fetched.
6. Save and reboot the phone if required.

## Tips
- Keep images at 320×240 px. PNG or JPG both work.
- File and path names are case-sensitive on the web. Match exactly.
- If you later rename files, remember to update `screensaver.xml`.
- GitHub Pages is public. Do not upload confidential images.

## Troubleshooting
- 404 Not Found: check repository is public and Pages is enabled, then verify the URL path.
- Nothing changes on the phone: increase the XML Download Interval or reboot the device.
- Slow or blocked: Pages is globally cached. Wait a minute and refresh.
