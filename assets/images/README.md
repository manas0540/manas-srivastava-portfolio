# Images

Drop your image files in this folder using the **exact filenames** below. The
site is already wired to look for them — as soon as a file lands here with
the right name, it will automatically appear on the live site. No code
changes needed.

| Filename                              | Where it shows up                        | Notes |
|----------------------------------------|-------------------------------------------|-------|
| `sih.jpg`                              | Achievements → Smart India Hackathon row  | A photo from the SIH pitch / event |
| `genius-olympiad-certificate.jpg`      | Achievements → Genius Science Olympiad row| Scan or photo of your Physics certificate |

## Adding more images later

Want to show a screenshot for a project, or swap the profile photo?

1. Add the file here, e.g. `assets/images/job-market-dashboard.png`.
2. In `index.html`, find the relevant project card / section and add:
   ```html
   <img src="assets/images/job-market-dashboard.png" alt="Job Market Dashboard screenshot" onerror="this.remove()">
   ```
   The `onerror="this.remove()"` bit means the site never breaks even if an
   image is missing — it just quietly hides that image until you add it.

## Tips

- Keep images reasonably sized (under ~500KB each) so the site loads fast.
- `.jpg` / `.jpeg` for photos, `.png` for screenshots/certificates with text, `.svg` for logos/icons.
- Recommended crop for achievement thumbnails: square (e.g. 300×300px).
