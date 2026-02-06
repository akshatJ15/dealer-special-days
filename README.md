# Dealer Special Days Manager

A modern, responsive web application for managing dealer birthdays and anniversaries with add, edit, delete, search, filter, and export capabilities.

## Features

✨ **Core Features:**
- 📅 View all dealer special days (birthdays & anniversaries)
- ➕ Add new entries
- ✏️ Edit existing entries
- 🗑️ Delete entries
- 🔍 Search by name or firm
- 🗓️ Filter by month
- 🎂 Filter by occasion (Birthday/Anniversary)
- ⬇️ Export to CSV
- 🔄 Reset to original data

## Technical Features

- **Modern UI** - Clean, gradient-based design with smooth animations
- **Responsive Design** - Works on desktop, tablet, and mobile
- **Data Persistence** - Uses browser localStorage to save all changes
- **No Backend Required** - Fully client-side application
- **Beautiful Interactions** - Hover effects, transitions, and smooth animations

## Data

Contains **133 dealer entries** with:
- Dealer/Firm names
- Contact person names
- Birthday and Anniversary dates
- Comprehensive coverage of major dealers

## How to Use

1. **Open** `index.html` in a web browser
2. **View** - All entries are displayed in the table
3. **Search** - Type in the search box to find entries
4. **Filter** - Use month and occasion dropdowns to filter
5. **Add** - Click "➕ Add New" to add an entry
6. **Edit** - Click ✏️ to edit an entry
7. **Delete** - Click 🗑️ to delete an entry
8. **Export** - Click "⬇️ CSV" to download filtered data
9. **Reset** - Click 🔄 to restore original data

## Browser Compatibility

- Chrome/Chromium ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- Any modern browser with ES6 support

## Storage

- **localStorage** - All changes are automatically saved to browser storage
- **Persistence** - Changes remain even after closing the browser
- **Reset Option** - Restore original data anytime with the reset button

## Installation

No installation needed! Just open `index.html` in your browser.

For local development server:
```bash
python -m http.server 8000
```

Then visit: `http://localhost:8000`

## File Structure

```
├── index.html       # Complete application (HTML + CSS + JavaScript)
└── README.md        # This file
```

## Development

The entire application is contained in a single `index.html` file with:
- Embedded CSS for styling
- Vanilla JavaScript (no dependencies)
- 133 pre-loaded dealer entries
- Full CRUD operations support

## Author

Created for managing dealer special days efficiently.

## License

Free to use and modify.
