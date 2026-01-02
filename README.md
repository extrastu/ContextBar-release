# ContextBar

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.7-green.svg)
![Tech](https://img.shields.io/badge/tech-React%20%7C%20TypeScript%20%7C%20Vite-blueviolet.svg)

A powerful Chrome extension that provides quick access to search engines, AI assistants, and productivity tools through a floating toolbar when you select text on any webpage.

## Features

- 🎯 **Quick Access**: Select text and instantly access 24+ tools
- 🔧 **Highly Configurable**: Enable/disable tools and customize settings
- 🌐 **Remote Updates**: Tool configurations update automatically from GitHub
- 🎨 **Modern UI**: Clean, responsive interface with dark mode support
- ⚡ **Smart Caching**: 24-hour cache for optimal performance
- 🔒 **Privacy First**: All data stored locally in your browser

## Tool Categories

### Search Engines

- Google, Bing, DuckDuckGo, Baidu, Google Images

### AI Assistants

- ChatGPT, Gemini, Claude

### Social Media

- Twitter, X, Weibo

### Books & Media

- NeoDB, Douban, YouTube

### Reference & Docs

- Wikipedia, MDN, Merriam-Webster

### Development

- GitHub, StackOverflow, NPM

### Translation

- Google Translate (configurable target language)
- Google Translate API

### Tools & Services

- Flomo (note-taking)

## Installation


### Load Extension in Chrome

1. Open Chrome and navigate to `chrome://extensions/`
2. Enable "Developer mode" in the top right
3. Click "Load unpacked"
4. Select the `dist` folder from this project

## Usage

1. **Select Text**: Highlight any text on a webpage
2. **Choose Tool**: Click a tool icon from the floating toolbar
3. **Configure**: Click the settings icon (⚙️) on tools to customize options

### Configuring Tools

1. Click the extension icon in Chrome toolbar
2. Find the tool you want to configure
3. Click the settings button (⚙️)
4. Adjust settings (e.g., select target language for Google Translate)
5. Save configuration

## Configuration & Customization

### Remote Configuration

Tool configurations are loaded from GitHub and cached for 24 hours. This allows for dynamic updates without re-installing the extension.

- **Storage**: Configurations are cached in `chrome.storage.local` with a 24-hour TTL.
- **Updates**: The extension checks for version updates automatically.

### Manual Update

You can force an update by clicking the refresh button in the popup menu.


## Privacy Policy

This extension respects your privacy:

- **No Tracking**: We do not collect any personal usage data.
- **Local Storage**: All settings are stored locally on your device using `chrome.storage`.
- **Direct Connection**: Tools interact directly with their respective services (e.g., opening a Google Search tab) without passing through any third-party servers.

## License

[MIT License](LICENSE)

## Author

**extrastu**
