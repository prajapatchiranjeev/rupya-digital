Static HTML export for Rupya Digital (single-page).

Files:
- index.html : Main landing page. Uses Tailwind CDN and simple styles.

To use:
1. Download the zipped package and extract.
2. Open index.html in a browser to preview.
3. To receive form submissions, replace the `action` attribute of the contact <form> with your Formspree endpoint:
   - Example: action="https://formspree.io/f/your_form_id"
4. For deployment: upload the files to Netlify, Vercel (static), GitHub Pages, or any static hosting.