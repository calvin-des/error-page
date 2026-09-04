# Bootstrap Error Page

This is the Bootstrap-friendly version of Yoav Kadosh's CodePen: https://codepen.io/ykadosh/pen/wvPOdmb

## Files

- `index.html` is a complete local preview page.
- `fragment.html` is the drop-in markup for an existing Bootstrap layout.
- `assets/css/error-page.css` is fully scoped under `.site-error-page`.
- `assets/js/error-page.js` recreates the original React parallax behavior in vanilla JavaScript.

## Integration Notes

1. Keep the `site-error-page` wrapper around the fragment.
2. Include the stylesheet after Bootstrap so the scoped error-page styles win.
3. Include `assets/js/error-page.js` near the end of the page.
4. Update the two links in the copy to match the site's real home and support/contact routes.
5. Keep the Google Fonts link if the page should match the original look.

The large background code is controlled with `data-error-code="404"`.
