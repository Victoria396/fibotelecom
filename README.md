# Fibotelecom frontend

## Current state

The root page is based on the HTML capture of the live Fibotelecom homepage supplied for this task. It preserves the captured page markup and embedded initial page data, rather than the earlier approximate demo homepage.

## Run locally

```bash
npm install
npm run dev
```

Vite starts at `http://127.0.0.1:5173`.

## Known limitations

- This is a captured homepage, not a fully self-contained mirror of every page on `fibotelecom.ru`.
- The original CSS, JavaScript bundle, fonts, and product images are still referenced from `https://fibotelecom.ru` and related public asset hosts. Internet access is required, and those remote files can change.
- The HTML contains captured navigation paths and page data, but other routes have not yet been independently captured and checked.
- Third-party analytics and tracking scripts were removed from the saved page. The live site's application bundle remains an external dependency.

## Next steps

1. Capture and transfer the styles, scripts, fonts, and images into the repository.
2. Capture the required internal pages and verify navigation and responsive behavior.
3. Move the page into the project's local frontend implementation and remove runtime dependencies on the live site.
