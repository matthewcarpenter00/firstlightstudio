# First Light Media

Static site for firstlight.media. No build step.

## Add or change a project
1. Put a 480x640 (3:4) JPG in `assets/work/`.
2. In `index.html`, copy one `<li class="row">` block in the Selected work list and change the link, name, services and `data-img` name.
3. Add the same name to the image list in the script near the bottom (`const IMGS`).

## Deploy
Import this repo in Vercel (Framework preset: Other). Every push to `main` redeploys.
