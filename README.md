# Omni Solutions Sales Hub

An internal microsite for Omni Solutions consultants and sales agents. The hub centralizes service offerings, combo packages, sales playbooks, and inspirational content to streamline pitches and deal execution.

## Getting Started

1. Open `index.html` in your browser to explore the hub locally.
2. Each service card links to a dedicated detail page for Web Development, Photography, Videography, and Social Media offerings.
3. Combo packages and enablement resources are accessible via the navigation links.

### Local Preview

```powershell
# From the repository root
Start-Process index.html
```

For a lightweight static server (optional), install [serve](https://www.npmjs.com/package/serve) and run:

```powershell
npm install -g serve
serve .
```

## Assets

The `assets/` directory includes placeholder PDFs referenced throughout the hub. Replace each placeholder with its production-ready document while keeping filenames consistent, or update the HTML links accordingly.

## Customization Tips

- Update hero metrics and quotes regularly to keep momentum high.
- Swap in fresh win stories and decks with every major launch.
- Tailwind CSS is loaded via CDN; add custom styles in the `<style>` block or create a dedicated stylesheet if needed.

## Roadmap Ideas

- Add authentication or access control if the hub goes beyond internal hosting.
- Layer in analytics (e.g., Plausible) to understand resource usage.
- Embed Loom or YouTube videos for onboarding and pitch highlights.
