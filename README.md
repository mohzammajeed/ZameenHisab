# ZameenHisab website

Static site, no build step.

1. Build the app: push the project to GitHub, open Actions -> "Build APK", download the `ZameenHisab-APK` artifact and unzip it.
2. Rename the APK to `ZameenHisab.apk` and put it in this folder (next to `index.html`). The Download buttons point to it.
3. Deploy on Vercel: import this folder (or a GitHub repo containing it), set the project name to `ZameenHisab`,
   Framework preset "Other", no build command, no output directory. The address becomes ZameenHisab.vercel.app
   (Vercel gives the name only if nobody else has taken it).

When you release a new version, replace `ZameenHisab.apk` and change the version text in `index.html` (search "Version 1.0").
