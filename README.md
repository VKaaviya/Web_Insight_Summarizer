# Web Summarizer Chrome Extension

## Overview
The **Web Summarizer** is a Chrome extension that uses AI to generate concise summaries of web pages. With a single click, it extracts and summarizes the page content using Cohere's AI-powered API.

## Features
- Summarizes web pages instantly.
- Uses Cohere API for AI-based summarization.
- Simple UI with a "Summarize" button.
- Displays the summarized content directly in the popup.

## Installation
### 1. Clone the Repository
```sh
git clone https://github.com/your-username/web-summarizer.git
cd web-summarizer
```

### 2. Load the Extension in Chrome
1. Open **Google Chrome**.
2. Go to `chrome://extensions/`.
3. Enable **Developer Mode** (toggle in the top-right corner).
4. Click **Load Unpacked**.
5. Select the folder containing the extension files.

## Files Overview
- **manifest.json**: Configuration file defining extension properties and permissions.
- **popup.html**: HTML structure for the popup UI.
- **popup.js**: JavaScript logic for user interactions.
- **style.css**: Styling for the popup UI.
- **background.js**: Handles API calls for summarization.

## Usage
1. Click on the extension icon in the Chrome toolbar.
2. Click the **Summarize** button.
3. The AI-generated summary will appear below the button.

## API Configuration
To use this extension, replace `'YOUR_API_KEY'` in `background.js` with your actual API key from Cohere.

```js
const apiKey = 'YOUR_API_KEY';
```

## Contributing
Feel free to submit issues or pull requests to enhance the extension.

## License
This project is licensed under the MIT License.

