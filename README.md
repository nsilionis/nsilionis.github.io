# Personal Academic Website

This is the source code for Nicholas E. Silionis's personal academic website, hosted on GitHub Pages.

## Deployment Instructions

1. **Clone your existing repository** (if you haven't already):
   ```bash
   git clone https://github.com/nsilionis/nsilionis.github.io.git
   cd nsilionis.github.io
   ```

2. **Copy these files into your repository**:
   - `index.html`
   - `publications.html`
   - `code.html`
   - `contact.html`
   - `style.css`

3. **Update the placeholder links** in the HTML files:
   - Google Scholar URL (in `index.html` and `contact.html`)
   - ORCID ID (in `index.html`, `contact.html`, and your CV)
   - LinkedIn username (in `index.html` and `contact.html`)
   - ResearchGate profile (in `index.html` and `contact.html`)

4. **Commit and push to GitHub**:
   ```bash
   git add .
   git commit -m "Initial website setup"
   git push origin main
   ```

5. **Enable GitHub Pages** (if not already enabled):
   - Go to your repository on GitHub
   - Click "Settings"
   - Scroll to "Pages" section
   - Under "Source", select "main" branch
   - Click "Save"

6. **Your site will be live at**: `https://nsilionis.github.io`

## Customisation Tips

### Adding Content
- **New publications**: Add to `publications.html` following the existing format
- **New projects**: Add to `code.html` following the existing format
- **Update bio**: Edit the bio section in `index.html`

### Styling
- All styling is in `style.css`
- The design uses a minimal, academic-focused aesthetic
- Colours and fonts can be adjusted in the CSS file

### Adding a Profile Photo
If you'd like to add a photo (like the reference site), add this to `index.html` before the closing `</main>` tag:

```html
<section class="profile-photo">
    <img src="images/profile.jpg" alt="Nicholas E. Silionis" style="max-width: 200px; border-radius: 5px;">
</section>
```

Then create an `images` folder and add your photo as `profile.jpg`.

## File Structure

```
nsilionis.github.io/
├── index.html           # Homepage with timeline and bio
├── publications.html    # Full publications list
├── code.html           # Projects and code repositories
├── contact.html        # Contact information
├── style.css           # Stylesheet for all pages
└── README.md           # This file
```

## Maintenance

- Update publications as papers are published
- Add new projects as they develop
- Keep contact information current
- Consider adding a blog section if you want to share research updates

## Technical Details

- Pure HTML/CSS (no JavaScript required)
- Responsive design works on mobile and desktop
- Clean, academic-focused aesthetic
- Fast loading times
- Accessible and SEO-friendly
