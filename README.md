# ScreenShelf — Semantic, Accessible Layout

A responsive static movie-discovery page built to demonstrate the project requirements:
- Semantic HTML5: `header`, `nav`, `main`, `section`, `article`, and `footer`
- Tailwind CSS responsive utility classes
- Accessible labels for search, descriptive labels for illustrative poster artwork, and a skip link
- Visible keyboard focus and reduced-motion support
- Responsive card grid for mobile, tablet, and desktop layouts

## Project structure

```text
my-frontend/
├── index.html
├── src/
│   └── styles.css
└── README.md
```

## Run locally

1. Extract this folder.
2. Open `index.html` in a browser with an internet connection. Tailwind CSS is loaded from its Play CDN for this simple static demo.
3. For a local server, open the folder in VS Code and use the Live Server extension, or run `python -m http.server 8000` from the project folder and visit `http://localhost:8000`.

## Accessibility checks

- Use `Tab` and `Shift+Tab` to navigate.
- Confirm the visible focus indicator appears.
- Test the page with the [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/).
- Check the page at mobile and desktop widths.

## Deploy

### GitHub
1. Create a new repository on GitHub.
2. Upload `index.html`, `src/styles.css`, and `README.md` (keep the `src` folder).
3. Copy the repository URL for submission.

### Netlify
1. Sign in to Netlify and choose to deploy a site manually.
2. Drag the extracted `my-frontend` folder into the deploy area, or connect the GitHub repository.
3. Copy the published URL.

### Vercel
1. Import the GitHub repository into Vercel.
2. For this plain static site, no build command is needed; use the project root as the output directory if prompted.
3. Deploy and copy the published URL.

## Notes

This is a static layout demo. Search does not filter cards, the watchlist is illustrative, and the movie names/ratings are fictional sample content. No backend is included.
