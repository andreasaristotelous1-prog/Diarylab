DIARYLAB - HOSTING FILES

Put the whole "diarylab" folder (all 6 files) in the same repository you use for
lessonlab.uk. Do not rename the files or take them out of the folder.

  index.html          the app
  manifest.webmanifest, icon-192.png, icon-512.png, favicon.ico   install-as-app details
  sw.js               lets it open with no internet after the first visit

UPLOAD (GitHub website)
1. Open the repository, then Add file > Upload files.
2. Drag the contents of the "diarylab" folder in. To keep it in its own folder, first
   click Add file > Create new file, type  diarylab/placeholder.txt  as the name,
   commit it, then upload the six files into that folder.
3. Wait about a minute. The app is then at  lessonlab.uk/diarylab/

TO KEEP IT AWAY FROM THE PUBLIC
- The page asks search engines not to list it, and nothing links to it.
- For real protection use Cloudflare Access (Zero Trust > Access > Applications >
  Add application > Self-hosted). Domain: lessonlab.uk, path: diarylab. Add a policy
  "Allow" with the email addresses that may open it. Visitors get a one-time code by email.
  Free for up to 50 people.

INSTALL AS AN APP
Open the address in Chrome or Edge and use the Install button in the address bar.
On a phone use Share > Add to Home Screen (iPhone) or the browser menu > Install app.

DATA
Everything each person enters is saved in their own browser on their own device. Use
Profile > Export backup now and then.
