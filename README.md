# WineScout

A modern, interactive wine recommendation and exploration web app built on real-world wine review data.

> Find your next favourite bottle — no sommelier required.

---

## Features

### Wine Recommender
- Filter wines by:
  - Budget
  - Country
  - Variety
- Returns top 5 wines ranked by rating and relevance
- Balances **quality (points)** and **affordability**

### Palate Matcher
- Select up to 3 taste preferences:
  - Fruity, Smoky, Spicy, Earthy, Floral, etc.
- Uses keyword-based scoring on wine descriptions
- Recommends wines that match your flavour profile

### Data Explorer (EDA)
- Interactive charts:
  - Top countries by average rating
  - Price vs rating correlation
  - Most common varieties
  - Average price per country
- Search across wines, regions, and varieties

### Insights Section
- Extracted patterns from dataset:
  - Price vs rating correlation (r ≈ 0.42)
  - Top-performing countries
  - Best-performing wine varieties

---

## How It Works

- Dataset: Kaggle Wine Reviews (~130,000 entries)
- Filtering logic:
  - Budget + metadata filters
  - Sorted by rating (points)
- Taste matching:
  - Keyword scoring from wine descriptions
  - Each flavour maps to multiple descriptors (e.g., "fruity" → cherry, berry, plum)
- Ranking:
  - Combines:
    - Description relevance
    - Wine rating
    - Price constraints

---

## UI Highlights

- Glassmorphism cards
- Custom wine-themed color palette
- Smooth animations and transitions
- Fully responsive layout
- SVG-based icons and decorative elements

---

## Tech Stack

- HTML5
- CSS3 (custom variables, animations, gradients)
- Vanilla JavaScript
- Chart.js (for data visualizations)

---

## Dataset

- Source: Kaggle Wine Reviews Dataset
- ~130,000 wine reviews
- Features include:
  - Country
  - Price
  - Variety
  - Description
  - Rating (points)

---

## License

MIT

---

## Author

Dhyeya Aneesh
