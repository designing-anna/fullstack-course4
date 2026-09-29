# Tech Help for Seniors

A one-page static site for Anna Bitters, The Tech Untangler. Plain HTML and CSS, a few lines of JavaScript for the "Larger text" button, no build step.

## Placeholders to fill in

Search `index.html` for `PLACEHOLDER` to find each one.

1. **Phone number** (Book section). Change the visible text and the `href="tel:+10000000000"`.
2. **Email address** (Book section). Change the visible text and the `href="mailto:you@example.com"`.
3. **Photo of Anna** (About section). Replace `images/anna-placeholder.svg` with a real photo, for example `images/anna.jpg`, and update the `src`. Keep the size roughly 320 x 380 or any portrait shape. Update the `alt` text if you want it more descriptive.
4. **Testimonial** (under About). Replace the quote and the "[Client first name, town]" line with a real quote, used with permission.
5. **How do I pay?** (FAQ). Replace the bracketed text with how clients pay.

Also worth a read before launch: the FAQ answer about passwords and privacy, so it matches exactly how you work.

Optional: once you have a phone number and web address, add `"telephone"` and `"url"` to the LocalBusiness schema at the top of `index.html`.

## Preview locally

From this folder:

    python3 -m http.server 8000

Then open http://localhost:8000

## Deploy to Netlify

Either drag this `tech-help-seniors` folder onto https://app.netlify.com/drop, or connect the repo and set the **base directory** to `tech-help-seniors`. There is no build command. `netlify.toml` publishes the folder as is.
