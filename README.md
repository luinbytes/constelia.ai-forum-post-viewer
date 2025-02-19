# Constelia.ai Forum Quick View

A lightweight, single-file HTML viewer for constelia.ai forum posts. View recent forum activity without leaving your development environment.

## Features

- 🚀 Real-time post fetching
- 🎨 Clean, responsive dark theme
- 🔒 Secure API key management
- 📝 Full BBCode support including:
  - Images and attachments
  - Code blocks with syntax highlighting
  - Tables
  - Quotes
  - User mentions
- ⚡ Rate limiting to prevent API abuse
- 🖼️ Lazy loading for images
- 📱 Mobile-friendly design

## Setup

1. Download `quick-view.html` to your preferred location
2. Create a `key.txt` file in the same directory
3. Add your API key to `key.txt` in the format: `ABCD-EFGH-IJKL-MNOP`
4. Open `quick-view.html` in your browser

## Usage

- Click the "Refresh" button to fetch the latest 15 forum posts
- Posts are displayed with their title, author, and elapsed time
- Click post titles to open them in the main forum
- Images and attachments are loaded on demand
- 10-second cooldown between refreshes to prevent API spam

## Development

The entire application is contained in a single HTML file for simplicity. The structure is:

- HTML5 document structure
- CSS variables for theming
- Responsive styling
- Vanilla JavaScript for functionality
- No external dependencies

## Author

Created by 6c75

## License

MIT License
