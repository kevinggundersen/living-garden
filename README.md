
# Living Garden

<div align="center">



</div>

An interactive web visualization that transforms GitHub repositories into a living, breathing botanical garden. Each repo becomes a plant that grows, blooms, and sways based on real project data.

## How It Works

Plants grow from your GitHub repos. Commit count determines height, language determines color, and stars spawn fireflies that orbit around them. The garden shifts through seasons, a day/night cycle follows your system clock, and butterflies drift through the scene.

- **Seeds** — tiny budding ideas
- **Saplings** — growing projects with closed buds
- **Mature plants** — full flowers, leaves, and roots with contributor avatars

Hover a plant to see repo details. Click to open it on GitHub. Scroll down to explore contributor roots.

## Features

- Language-based color coding (18+ languages)
- Animated flowers, leaves, and particle effects (pollen, petals, snow)
- Day/night cycle with sun, moon, and stars
- Seasonal visuals (spring pastels, summer greens, autumn oranges, winter blues)
- Contributor roots with avatars via GitHub API
- Ambient audio generation

## Setup

Serve `index.html` with any static file server. Configure repos in `projects.json`:

```json
[
  {
    "url": "https://github.com/user/repo",
    "status": "mature"
  }
]
```

Or enter a GitHub username in the search bar to load repos dynamically.