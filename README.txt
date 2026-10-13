SHOUNEN DEN — STATIC SHIRT DATA + GOOGLE FORM CTAS

FIXES
- Shirt designs live in static/shirts/
- Product cards read from static/products.js, so they also work when index.html is opened directly in Chrome using file://
- static/products.json is kept as a human-readable catalogue reference
- A fourth clearly labelled SAMPLE shirt mockup is included
- “Count me in” opens Google Forms in a new tab
- “Send feedback” opens Google Forms in a new tab
- Social contact icons are included for Instagram, Facebook, YouTube and WhatsApp

IMPORTANT: GOOGLE FORMS LINKS
The current buttons use https://forms.google.com/ as a placeholder. Replace that URL in index.html with your actual Google Form share URL for the newsletter/signup form and your feedback form. If you use two different forms, each button should have its own URL.

CHANGE SHIRT ARTWORK
1. Put a PNG, JPG, WEBP, or SVG in static/shirts/.
2. Open static/products.js.
3. Add/edit an object in window.SHOUNEN_DEN_PRODUCTS. Example:
   {
     "id": "horizon-black",
     "name": "Horizon Black Tee",
     "subtitle": "Black / Sunset graphic",
     "number": "05",
     "tag": "NEW DROP",
     "image": "static/shirts/horizon-black.png",
     "alt": "Black shirt with original sunset artwork"
   }
4. Save and refresh index.html.
Use simple filenames and exact path capitalization. A fallback sample shirt appears if an image path fails.

PREVIEW
You can open index.html directly in Chrome; products are loaded from static/products.js without fetch().
For deployment, upload the entire folder, keeping index.html, static/, and assets/ together.

CONTACT LINKS
Replace YOUR_EMAIL@example.com, YOUR_HANDLE, YOUR_PAGE, YOUR_CHANNEL, and YOUR_NUMBER in index.html. WhatsApp URL number should include country code but no +, spaces, or hyphens.

SAMPLE ART
The “Signal Tee (Sample)” is placeholder/demo artwork. Replace it with your own final product design before launch.
