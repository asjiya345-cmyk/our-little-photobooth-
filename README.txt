OUR LITTLE PHOTOBOOTH — UPDATED STARTER
======================================

This version includes:
- Welcome screen with PRELOADED MEMORIES first and a LIVE PHOTOBOOTH option.
- Vintage beige paper texture, navy stars and a retro printer.
- Preloaded photo strip with a print animation.
- Live phone-camera mode with a 3-second countdown before each of four photos.
- Save the live strip as one combined JPG image.
- Save each live photo separately.
- Save the preloaded memory strip and its photos.
- Responsive design for mobile and desktop.

BEFORE PUBLISHING: ADD YOUR FOUR MEMORY PHOTOS
----------------------------------------------
1. Pick four photos you want to preload.
2. Rename them exactly:
   photo1.jpg
   photo2.jpg
   photo3.jpg
   photo4.jpg
3. Put all four files in the same folder as index.html.
4. Test by opening index.html in your browser. The preloaded images will show once the files are present.

EDIT THE WORDING
----------------
Open index.html in a code editor such as the free Visual Studio Code
(https://code.visualstudio.com/). You can change:
- The title: "A Little Corner of Us"
- The introductory sentence
- The memory-strip caption
- The final text and button labels

Try to change only text between HTML tags, not the surrounding code.

PUBLISH FOR FREE WITH GITHUB PAGES
----------------------------------
The live camera requires the website to be served securely over HTTPS.
GitHub Pages provides HTTPS.

1. Sign in or create an account at https://github.com/
2. Create a NEW PUBLIC repository, for example: our-little-photobooth
3. Upload index.html and photo1.jpg through photo4.jpg to the repository's top level.
   You may also upload this README, but it is not needed for the website.
4. Click Settings > Pages.
5. Under Build and deployment, select "Deploy from a branch".
6. Select branch "main" and folder "/(root)", then Save.
7. Wait for the published URL. It usually resembles:
   https://YOUR-USERNAME.github.io/our-little-photobooth/
8. Open the URL on your phone. Test both the memories screen and live camera.
9. When asked, allow camera access. If camera access is blocked, check the browser's site permissions and make sure the URL starts with https://.

LINK TO NFC TAG
---------------
1. Install an NFC-writing app (for example, NFC Tools) on a phone that supports NFC.
2. Choose Write > Add a record > URL/URI or Website.
3. Paste the complete published HTTPS URL.
4. Tap Write and hold the phone near the NFC tag until it confirms completion.
5. Scan the tag with a phone and test the site.

IMPORTANT NOTES
---------------
- Live camera photos are processed in the browser; this template does not upload them to a server.
- The browser must allow camera access. The live camera works on the published HTTPS site, not reliably from a local file opened as file://.
- Saving/downloading behaves differently across phone browsers. If a phone opens a saved image instead of downloading it, use the browser Share menu to save it.
- The preloaded memory photos are part of the public website. Anyone with the URL can view them. Only publish photos you have permission to share.
- The four individual downloads may trigger multiple download prompts depending on the browser.
