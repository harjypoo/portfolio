Harjot. — portfolio website (standalone export)

Open index.html through a web server (opening the files directly from disk
may block the scripts). Quick local preview:
    cd harjot-portfolio
    python3 -m http.server 8000
then visit http://localhost:8000

To put it online, upload the whole folder as-is to any static host
(Netlify, Vercel, GitHub Pages, Cloudflare Pages, your own server).
index.html opens the password gate (passcode 3026).

Pages: Main.dc.html (gate) · About.dc.html · Home.dc.html (Work) · Process.dc.html
support.js is the page runtime; assets/ holds the résumé PDF.
Fonts load from Google Fonts.
