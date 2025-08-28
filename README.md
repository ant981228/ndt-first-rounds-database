# NDT First Rounds Database

An interactive web application for browsing and searching the National Debate Tournament (NDT) First Rounds historical data.

## Features

- **Search & Filter**: Search across all fields or filter by specific criteria
- **Smart Autocomplete**: Type-ahead suggestions for schools and debaters
- **Frequency Tracking**: See how many times each debater has won first round awards
- **Visual Highlights**: 4+ time winners are highlighted in yellow
- **Responsive Design**: Works on desktop and mobile devices

## How to Use

1. **Global Search**: Use the main search box to find anything across all fields
2. **Specific Filters**:
   - **School**: Type to search and select from autocomplete suggestions
   - **Year**: Select from the dropdown menu
   - **Debater**: Type to search for specific debaters
   - **Award Frequency**: Filter by number of times won (1-4+ times)
3. **Clear Filters**: Reset all filters with one click

## Data Source

The data is loaded from `data.csv` which contains historical NDT First Rounds information including:
- Bid Number
- School
- Debater 1
- Debater 2
- Year

## Technical Details

- Built with vanilla JavaScript, HTML, and CSS
- Uses DataTables for table functionality
- Papa Parse for CSV parsing
- No server required - runs entirely in the browser

## Updating the Data

To update the debate records:
1. Edit the `data.csv` file with new entries
2. Commit and push the changes to GitHub
3. The website will automatically reflect the updates

## Local Development

To run locally:
1. Clone this repository
2. Open `index.html` in a web browser
3. Note: Due to browser security restrictions, you may need to run a local server to load the CSV file

## Live Site

Visit the live site at: https://YOUR_USERNAME.github.io/ndt-first-rounds-database/

---

*This database celebrates the achievements of NDT debaters throughout the years.*