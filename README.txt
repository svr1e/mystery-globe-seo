1. Replace https://mysteryglobe.com with your real domain in every file (Linux/Mac: grep -rl YOUR-DOMAIN.com . | xargs sed -i 's#https://mysteryglobe.com#https://yourdomain.com#g').
2. Deploy this folder to Vercel (Framework: Other, no build command, output directory: .). vercel.json turns on clean URLs (/places/stonehenge, not .html).
3. Submit /sitemap.xml in Google Search Console and Bing Webmaster Tools.
