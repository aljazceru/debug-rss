# RSS/Atom Feed Debugger 🔧

A simple, powerful web-based tool for debugging and analyzing RSS and Atom feeds. Your RSS Army Knife!

## Features

- **Universal Feed Support**: Works with both RSS and Atom feeds
- **Comprehensive Analysis**: Displays all feed metadata and structure
- **Item Inspector**: Shows the last 10 items with all available fields
- **Raw XML Viewer**: View the complete XML structure of the feed
- **CORS Proxy**: Fetches feeds from any domain without CORS issues
- **Responsive Design**: Works on desktop and mobile devices
- **Zero Dependencies**: Pure HTML, CSS, and JavaScript

## Usage

1. Open the website in your browser
2. Paste an RSS or Atom feed URL into the input field
3. Click "Analyze Feed" or press Enter
4. View the detailed breakdown of your feed

### Try the Example Feeds

The tool includes quick-access buttons for popular feeds:
- Hacker News RSS
- Reddit Programming
- GitHub Blog

## What You'll See

### Feed Information
- Feed type (RSS version or Atom)
- Title, description, and link
- Publication dates
- Language and other metadata
- Image URLs
- Generator information

### Latest 10 Items
For each item, you'll see:
- All available fields (title, link, description, etc.)
- Publication dates
- Authors and categories
- Custom fields and namespaces
- Clickable links

### Raw XML Structure
- Formatted XML view of the entire feed
- Easy to copy and inspect

## Technical Details

- **Language**: Pure JavaScript (ES6+)
- **Hosting**: GitHub Pages compatible
- **CORS Solution**: Uses `allorigins.win` as a proxy
- **Parsing**: Native DOMParser API
- **Styling**: Gradient design with responsive layout

## Local Development

Simply open `index.html` in your browser. No build process or server required!

## GitHub Pages Deployment

1. Push this repository to GitHub
2. Go to repository Settings > Pages
3. Select the branch (usually `main` or `master`)
4. Select the root folder
5. Click Save
6. Your site will be live at `https://yourusername.github.io/repository-name/`

## Browser Support

Works in all modern browsers that support:
- ES6 JavaScript
- Fetch API
- DOMParser
- CSS Grid and Flexbox

## License

MIT License - Feel free to use and modify as needed!
