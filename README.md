# Recipe Finder App

A single-file recipe search web app. Type an ingredient or dish name and browse recipe cards with photos — powered by the free [TheMealDB](https://www.themealdb.com) public API.

## Features

- Search recipes by name or ingredient
- Recipe cards with meal photos, category, and area
- Category filter (e.g. Breakfast) with initial results on page load
- Responsive Tailwind CSS layout, no build step

## Tech stack

- Single HTML file (`index.html`) — HTML5, CSS3, vanilla JavaScript
- Tailwind CSS via CDN
- Data from TheMealDB public API (`https://www.themealdb.com/api/json/v1/1/`)

## Quick start

Just open `index.html` in a browser (needs internet for the Tailwind CDN and the recipe API):

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Project structure

```
Recipe-Finde-App/
├── index.html            # the whole app (single file)
├── "Recipe Finder App"   # original uploaded copy of the same file
├── README.md
└── LICENSE
```

## Deploy notes

Static file — deployed to GitHub Pages. No build, no environment variables.

## License

Free to use.

---

Built by Girish Lade — [ladestack.in](https://ladestack.in)
