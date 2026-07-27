# NL Football Booster Club Website

This folder is ready to upload to GitHub Pages.

## Files

- `index.html` — the webpage
- `styles.css` — colors and layout
- `config.js` — payment and social-media links
- `assets/` — Viking logo and team photo
- `.nojekyll` — tells GitHub Pages to serve the site as-is

## Add or update links

Open `config.js` and paste each web address between the quotation marks:

```javascript
const SITE_LINKS = {
  moov: "PASTE-MOOV-LINK-HERE",
  venmo: "https://venmo.com/u/NL_football_boosters",
  facebook: "PASTE-FACEBOOK-LINK-HERE",
  instagram: "PASTE-INSTAGRAM-LINK-HERE"
};
```

The Moov button stays disabled until a Moov link is added.

## Publish with GitHub Pages

1. Create a new public GitHub repository.
2. Upload every file and folder from this package.
3. Open the repository's **Settings**.
4. Select **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose the **main** branch and **/(root)** folder.
7. Click **Save**.

GitHub will display the public website address after it publishes.

## Contact information already included

NL Football Booster Club  
PO Box 73  
Fredericksburg, PA 17026  
nlvikingsfootballboosters@yahoo.com
