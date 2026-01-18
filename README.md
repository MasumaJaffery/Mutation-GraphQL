## Install the Firebase Data Connect Extension

Run this PowerShell command (in the same folder as your project):

IEX (New-Object Net.WebClient).DownloadString('https://firebase.tools/init/dataconnect.ps1')


This will:

Set up Firebase Data Connect

Install ext:connect:studio

Configure your .firebaserc and firebase.json files

2. Then Try Again:

After installation is complete:

firebase ext:connect:studio


It should open Firebase Studio in your browser.

🛠 If It Still Doesn’t Work:

Check your Firebase CLI version:

firebase --version


If it’s below 13.0.0, update it:

npm install -g firebase-tools


Let me know if you want to skip all this and just use a Python script to send GraphQL mutations instead.
