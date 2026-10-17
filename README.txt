SIMMI & DHEERAJ WEDDING INVITATION WEBSITE

Files:
- index.html: the complete responsive invitation website
- assets/wedding-artwork.png: decorative wedding artwork used in the hero background

PREVIEW:
Open index.html in a browser. Internet is needed for Google Fonts and the Google Maps/WhatsApp links.

FREE HOSTING WITH GITHUB PAGES:
1. Sign in at https://github.com/ or create a free account.
2. Create a new PUBLIC repository, e.g. simmi-dheeraj-wedding.
3. Upload index.html and the assets folder (including wedding-artwork.png) to the repository root.
4. Open repository Settings -> Pages.
5. Under Build and deployment, choose Deploy from a branch; select main and /(root), then Save.
6. Wait for the published URL shown in Settings -> Pages. It will look like https://YOUR-USERNAME.github.io/simmi-dheeraj-wedding/

BEFORE SHARING:
- Add the exact groom's residence address in index.html where it says "Home functions are at Maa Girija Vihar, Kamaluwaganja, Haldwani."
- Confirm exact clock times if you want them shown; current labels use the timing descriptions you provided.
- The WhatsApp button currently opens a pre-filled wishes message. For a real RSVP flow, a contact number or form service needs to be configured.
- This is a static website and does not require a paid server. A custom domain is optional and normally costs extra.


VIDEO SECTION:
- The website now includes two embedded wedding-themed YouTube videos.
- Playback requires internet access. They are background/invitation visuals, not personal footage of the couple.
- To use your own wedding/pre-wedding video later, upload it to YouTube as Unlisted or place an optimized MP4 in assets and replace an iframe with a <video controls> element.

SHARED GUESTBOOK: See SETUP-GUESTBOOK.txt to connect Supabase for shared text wishes and audio greetings. Backend configuration is required before guest submissions are saved online.
