# GitHub Profile - inventory69

Terminal-style GitHub profile with a riced aesthetic inspired by modern Linux setups.

## Features

- 🎨 Custom SVG header and footer with terminal window design
- 🐍 Contribution snake animation with custom colors
- 📊 Automated GitHub statistics and metrics
- 🌈 Color scheme matching dettmer.dev
- 🔄 Auto-updates every 6 hours via GitHub Actions

## Tech Stack

- GitHub Actions for automation
- lowlighter/metrics for statistics
- Platane/snk for contribution snake
- Custom SVG assets

## Design

Color palette based on Catppuccin/dettmer.dev:
- Background: `#1e1e2e`
- Primary Accent: `#78c2ad`
- Secondary Accent: `#375a7f`
- Badge: `#584966`
- Text: `#eff1f5`

## Documentation

Full project documentation available at: [inventory69/project-docs/github-profile](https://github.com/inventory69/project-docs/tree/main/github-profile)

## Setup

1. Create Personal Access Token with `repo` and `user` permissions
2. Add token as repository secret: `METRICS_TOKEN`
3. Push to trigger GitHub Actions
4. Profile will auto-update every 6 hours

## License

MIT
