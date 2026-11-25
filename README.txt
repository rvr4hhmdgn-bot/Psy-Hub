Psy Hub: the psychology study hub as an iPhone app
==================================================

This folder is a web app that works offline once it has been opened.

1. Put it on GitHub Pages
   - Sign in at github.com and create a new repository, for example "psy-hub".
     It can be public. (Private repositories need a paid plan for Pages.)
   - Click "Add file" > "Upload files". Upload everything INSIDE this folder
     (index.html, sw.js, manifest.webmanifest, README.txt and the folders
     fonts and icons). index.html must sit at the top level of the repository.
   - Click "Commit changes".
   - Go to Settings > Pages. Under "Build and deployment" choose
     "Deploy from a branch", branch "main", folder "/ (root)", and Save.
   - After a minute the address appears there, for example
     https://yourname.github.io/psy-hub/

2. Add it to the iPhone
   - Open that address in Safari (not another browser).
   - Tap the Share button, then "Add to Home Screen", then "Add".
   - Open "Psy Hub" from the Home Screen once while you are online and wait
     a few seconds. Everything is then stored on the phone and works without
     internet.

3. Updates
   - Run make.py on the new hub file, then upload the new folder contents to
     the same repository (replace the old files) and commit.
   - Open the app on the phone while online. It notices the new version,
     downloads it and reloads itself once. If it does not, close the app
     fully and open it again.

4. Your notes and flashcard progress
   - They are saved on the phone, inside this app only. They are not uploaded
     anywhere and do not sync to other devices or to Safari.
   - Deleting the app from the Home Screen deletes them too. Export your notes
     first: My notes > "Download .md" (opens the share sheet, choose "Save to
     Files") or "Copy as Markdown".
   - The web address must stay the same, otherwise the phone sees a new app
     with empty notes.

5. Printing
   - One-page sheets have "Print or save as PDF". On the iPhone this opens the
     print screen; to get a PDF, pinch outwards on the preview and share it.
