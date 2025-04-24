<div align="center">
  <img src="https://i.imgur.com/placeholder-logo.png" width="120" alt="TFT Assets Logo">
  
  # TFT-Assets
  
  <p align="center">
    <strong>A comprehensive collection of Teamfight Tactics resources</strong>
  </p>
  
  <p align="center">
    <a href="https://metaforge.lol">Website</a> •
    <a href="https://twitter.com/metaforgelol">Twitter</a> •
    <a href="#structure">Documentation</a>
  </p>
  
  <br>
</div>

## Overview

TFT-Assets provides a unified collection of high-quality assets and structured data for the Teamfight Tactics ecosystem. This repository contains icons, statistics, and metadata for all game entities, designed to support developers building TFT companion applications.

<div align="center">
  <table>
    <tr>
      <td align="center"><img src="https://i.imgur.com/placeholder-unit.png" width="60"/><br><small>Units</small></td>
      <td align="center"><img src="https://i.imgur.com/placeholder-trait.png" width="60"/><br><small>Traits</small></td>
      <td align="center"><img src="https://i.imgur.com/placeholder-item.png" width="60"/><br><small>Items</small></td>
    </tr>
  </table>
</div>

## <a name="structure"></a> Repository Structure

```
tft-assets/
├── assets/             # Visual elements
│   ├── units/          # 60 champion icons
│   ├── traits/         # 26 trait icons (all tiers)
│   └── items/          # 422 item icons
│
└── data/               # Structured information
    ├── entities/       # Game mechanics and stats
    └── content/        # News and guides
```

### Assets Directory

The assets directory contains optimized PNG files organized by entity type:

- **Units**: Champion icons in square format using apiName convention
- **Traits**: Complete set including bronze, silver, gold, and prismatic variants
- **Items**: Comprehensive collection of all equipment icons

### Data Directory

The data directory provides complete game information in structured JSON format:

- **Entities**: Detailed statistics, ability descriptions, and scaling information
- **Content**: Curated guides, news articles, and meta analysis

<blockquote>
  <p>This repository contains aggregated game data and visuals that are subject to Riot Games' Terms of Service.</p>
</blockquote>

## MetaForge Integration

This repository powers the [MetaForge](https://metaforge.lol) companion app, providing tacticians with:

<div align="center">
  <table>
    <tr>
      <td align="center"><img src="https://i.imgur.com/placeholder-icon1.png" width="32"/><br><small>Meta Analysis</small></td>
      <td align="center"><img src="https://i.imgur.com/placeholder-icon2.png" width="32"/><br><small>Team Builder</small></td>
      <td align="center"><img src="https://i.imgur.com/placeholder-icon3.png" width="32"/><br><small>Statistics</small></td>
      <td align="center"><img src="https://i.imgur.com/placeholder-icon4.png" width="32"/><br><small>Visual Gallery</small></td>
      <td align="center"><img src="https://i.imgur.com/placeholder-icon5.png" width="32"/><br><small>Competitive Tools</small></td>
    </tr>
  </table>
</div>

MetaForge transforms this data into an intuitive interface for optimal team composition and strategy development.

<div align="center">
  <img src="https://i.imgur.com/placeholder-screenshot.png" width="600" alt="MetaForge Screenshot">
</div>

## License

This project is available under the MIT License. Game assets and data are subject to Riot Games' intellectual property policies.
