# The Community Builders LLC – preview website

This is a free preview website for **The Community Builders LLC** (La Crescent, MN), built by Hudson | Lacrosse Lawn & Landscape.
It is plain HTML and CSS: no build step, no monthly fees for hosting.

Live preview: https://megamower22.github.io/community-builders-preview/

## How to change text on the site (on github.com)

1. Go to this repo on github.com and sign in.
2. Click **index.html**.
3. Click the **pencil icon** (Edit this file) at the top right of the file.
4. Find the words you want to change and type the new text. Only change the words between the tags, not the `<` `>` parts.
5. Scroll down (or click the green **Commit changes...** button), add a short note like "Update hours", and click **Commit changes**.
6. Wait about a minute, then refresh the website. Your change will be live.

## Good to know

- **Colors** are at the top of `style.css` (look for `--teal` for the main color, `--brass` for the buttons, and `--sand` for the light background).
- **Fonts** come from Google Fonts: **Bricolage Grotesque** for headings and buttons, **Nunito** for body text. They're set at the top of `style.css` (`--font-display` and `--font-body`).
- Anything in yellow highlight that says **[Owner to confirm]** still needs real info from the owner. Once it's confirmed, delete the whole `<span class="placeholder">...</span>` part.
- The phone number appears in several places. Search for `500-2150` (and `+15075002150` in the call links) to update all of them.
- The email address appears in two places. Search for `inquiries@` to update it.
- The Google rating ("5.0" and "41 Google reviews") appears in two places: the strip under the big headline (`class="trust-strip"`) and the Reviews heading. Search for `41` to update both as more reviews come in.
- To remove the "Preview site" banner once the owner approves, delete the line with `class="preview-banner"` in `index.html`.
