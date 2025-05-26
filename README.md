# New Tab Chrome Extension
A minimalistic Chrome/Edge extension that replaces the default new tab page with a custom design featuring bookmarks, quotes, and the current date.

Features

- Clean and responsive layout
- Current date and time
- Quick access search form for popular websites
- Quick-access bookmarks to popular websites
- Random quote every time you open a new tab or refresh the page

## Requirements
- Chrome or Edge browser

## Setup
```
git clone https://github.com/mariosevripidou/new-tab-chrome-extension
cd new-tab-chrome-extension
```

## Installation

Google Chrome
1. Open Google Chrome and go to chrome://extensions/.
2. Enable Developer mode using the toggle in the top right corner.
3. Click "Load unpacked".
4. Select the folder where you cloned this repository.

Microsoft Edge
1. Open Microsoft Edge and go to edge://extensions/.
2. Enable Developer mode using the toggle in the bottom-left corner.
3. Click "Load unpacked".
4. Select the folder where you cloned this repository.

The custom new tab page should now be active.

## Files
- index.html – Main layout of the new tab
- css/main.css – Styling for the tab
- js/quotes.js – Script to show random quotes
- js/showdate.js – Script to show date and time
- img/main.jpg – Background image
- icons/ – Bookmark icons
- manifest.json – Extension configuration
- icon.png – Extension icon

## Notes
- You can personalize the icons or links in index.html.
- Quotes can be modified in js/quotes.js.
