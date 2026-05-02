# Favorite Restaurants

A simple static website for Corey and Gladys' favorite restaurants and cafes.

## Files

- `index.html` displays the searchable, filterable table.
- `restaurants.json` stores the restaurant data.
- `README.md` explains the project.

## Data schema

Each restaurant entry uses this shape:

```json
{
  "name": "Restaurant Name",
  "city": "Houston",
  "area": "Neighborhood or area",
  "address": "Street address",
  "mapUrl": "Map or directions URL",
  "websiteUrl": "Restaurant website or menu URL",
  "notes": "Optional notes"
}
```

## How to add a restaurant

Edit `restaurants.json` and add a new object inside the array.

Make sure every object except the last one ends with a comma.

## GitHub Pages

Recommended settings:

1. Go to the repo on GitHub.
2. Open Settings.
3. Open Pages.
4. Under Build and deployment, choose:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / root
5. Save.

Your site should be available at:

`https://coreyprator.github.io/favorite-restaurants/`
