# Chicago Nightlife Map 🗺️

A minimalist map visualizing nightlife venue density across Chicago using OpenStreetMap data and Python.

![Chicago Nightlife Map](Chicago%20Nightlife%20Map.png)

---

## What It Shows

Thousands of nightlife-related venues across the urban core of Chicago including bars, pubs, breweries, restaurants with alcohol, and nightclubs rendered as blue dots.

---

## How It Works

This project was built entirely in [Google Colab](https://colab.research.google.com/) and published via GitHub.

**Steps:**

1. Queried OpenStreetMap using `osmnx` for nightlife tags  
2. Filtered and cleaned location data  
3. Plotted over 2,700 venues with `matplotlib`  
4. Labeled key cultural neighborhoods  
5. Exported a high-resolution PNG

---

## Tech Stack

- Python  
- `osmnx` + `shapely` (geospatial)  
- `pandas` (data wrangling)  
- `matplotlib` (visualization)

---

## Geographic Scope

Bounding box used:
- **North:** W Peterson Ave  
- **South:** W 63rd St  
- **East:** Jackson Park  
- **West:** N Pulaski Rd

---

## Files

| File | Description |
|------|-------------|
| `Chicago_Nightlife_Map.ipynb` | Full Google Colab notebook |
| `Chicago Nightlife Map.png`  | Final visual map output |

---

## License

MIT License — free for personal or commercial reuse with attribution.
