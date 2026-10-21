# Massachusetts Schools of Recognition, 2026

Interactive map of the 56 Massachusetts schools named 2026 Schools of Recognition. Pins are placed from each school's street address. Color shows school level, and the outlined filters narrow by district, charter or vocational.

- `index.html` is the whole map, with its data embedded, so it works from GitHub Pages or by opening the file locally.
- `data/schools.csv` and `data/schools.json` hold the same 56 records: school, district, town, level, grades, governance, street address and latitude and longitude.

## Data notes

- Grade spans for elementary schools, charters and Rumney Marsh come from school and directory pages. Most high schools and junior/senior highs, and Boston Latin School, are classified by name because no page stated a span, so their grades column is empty. None of the 56 is a K-8.
- Coordinates come from TomTom street-level geocoding of the addresses, except Berkshire Arts and Technology, Francis J McGrath and Mary D Altavesta, whose coordinates were set by hand.
- Map boundaries are US Census cartographic data via the us-atlas package.
