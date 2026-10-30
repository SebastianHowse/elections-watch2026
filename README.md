# Collegedale Election Results (NYT-style)

A simple, self-contained web page for tracking and displaying City of Collegedale municipal election results in a clean, New York Times–inspired format.

## Features
- Live-updating candidate totals with colored percentage bars
- Interactive map of approximate precinct areas (colored by leading candidate; click for details)
- Precinct-level breakdown table that updates automatically
- Admin panel to manually enter results as they come in (saved in browser localStorage)
- Designed for the November 3, 2026 Collegedale Commission race (vote for 2)

## Candidates (2026)
- Bryan Barrett
- Jessica Fields
- Volker Henning
- Tonya Sadler
- Christopher Twombley

## Precincts
- Collegedale A
- Collegedale B
- Apison B
- Ooltewah

(Adjust these lists in the JavaScript at the top of `index.html` if needed.)

## How to Use on Election Night

1. **Open the file**  
   Double-click `index.html` or open it in any modern browser.

2. **Enter results**  
   Click “Enter / Update Results”, type the vote counts for each candidate in each precinct as they are reported, then click “Update Display”.

3. **Share with friends**
   - **Easiest for local viewing**: Share your screen or the file itself.
   - **For remote friends**:  
     - Host the folder for free on [Netlify Drop](https://app.netlify.com/drop) (drag the folder), [GitHub Pages](https://pages.github.com/), or similar.  
     - After you update results, they can refresh the page.  
     - Or copy the JSON from the export box and paste it into their local copy.

4. **Customize**  
   Edit the `CANDIDATES` and `PRECINCTS` arrays near the top of the `<script>` section to change names, colors, or add/remove precincts.

## Notes
- Results are unofficial until certified.
- Data lives only in the browser that enters it (localStorage). For true multi-user live updates, host the page and coordinate refreshes, or extend it with a shared backend (Google Sheets, Firebase, etc.).
- Colors are assigned for visual distinction only (race is nonpartisan).

Built for clear, readable election-night tracking.
