# Destiny 2 Raid Twitter Dashboard

## Overview

This project is a simple static webpage that aggregates live embedded Twitter timelines from a curated list of Destiny 2 World’s First raid racers and content creators. It serves as a raid intel dashboard displaying real-time tweets for quick team intel during raid races.

## Features

- Embeds 23 individual Twitter timelines using official Twitter Widgets.
- Dark theme UI optimized for readability during gameplay.
- Responsive flexbox layout for multi-column viewing on desktop.
- No backend or API keys required — purely client-side.
- Easy to deploy as a static site (e.g., GitHub Pages, Netlify).

## Files

- `index.html`: Main dashboard page with embedded timelines.
- `README.md`: Project documentation (this file).

## Usage

1. Open `index.html` directly in a modern web browser for local testing.
2. Deploy `index.html` on any static web hosting platform to share live.

## Deployment

Recommended free hosts:
- [GitHub Pages](https://pages.github.com/)
- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)

## Customization

- Modify the list of Twitter usernames inside the HTML `<a>` tags.
- Adjust styling inside `<style>` for size, colors, or layout.
- Add JavaScript for advanced features like collapsing feeds or filtering.

## Limitations

- Tweets are displayed via Twitter’s embedded timelines; no custom data aggregation.
- Embeds depend on Twitter’s platform availability and script loading.
- Not optimized for mobile devices currently.

## Next Steps / Ideas

- Add search/filter functionality for specific raid-related keywords.
- Integrate other social media or Discord feeds for comprehensive intel.
- Build a backend to aggregate and parse tweets if API limits can be managed.
- Implement a compact mode for overlay use in stream or team communication tools.

---

*This project was created to assist Destiny 2 raid teams in gathering timely Twitter intel during competitive raid races.*
