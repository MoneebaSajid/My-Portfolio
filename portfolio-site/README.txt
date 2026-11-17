Portfolio site (static, no build step)

1. Open index.html in a text editor and find this line near the bottom:
     var FIVERR_URL = "https://www.fiverr.com/YOUR_USERNAME";
   Replace it with your Fiverr profile or gig link. Every "Order on Fiverr" button uses it.

2. Put the site online with Vercel (free plan):
   Option A (GitHub): create a GitHub repository, upload everything in this folder,
     then in Vercel choose Add New > Project, import the repository, and deploy.
     No build command is needed; the framework preset can stay on "Other".
   Option B (command line): in this folder run  npx vercel  and follow the prompts.

3. To change samples, replace the files in the assets folder (keep the same names)
   or edit the image and PDF links in index.html.

Fonts load from Google Fonts when the site is online.
