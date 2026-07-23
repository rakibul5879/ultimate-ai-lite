# Ultimate AI Lite

<p align="center">
  <img src="https://img.shields.io/github/license/rakibul5879/ultimate-ai-lite?style=for-the-badge" />
  <img src="https://img.shields.io/github/repo-size/rakibul5879/ultimate-ai-lite?style=for-the-badge" />
  <img src="https://img.shields.io/github/last-commit/rakibul5879/ultimate-ai-lite?style=for-the-badge" />
  <img src="https://img.shields.io/github/issues/rakibul5879/ultimate-ai-lite?style=for-the-badge" />
  <img src="https://img.shields.io/github/stars/rakibul5879/ultimate-ai-lite?style=for-the-badge" />
  <img src="https://img.shields.io/github/forks/rakibul5879/ultimate-ai-lite?style=for-the-badge" />
</p>

---

## Overview

Ultimate AI Lite is a lightweight, single-file AI chat client built for compatibility, performance, and simplicity.

The application communicates with AI models through a Cloudflare Worker proxy backed by OpenRouter, allowing secure API access without exposing credentials to the client.

Designed using only HTML, CSS, and Vanilla JavaScript, Ultimate AI Lite runs efficiently on modern computers, older hardware, and mobile devices while remaining easy to deploy through GitHub Pages or any static hosting service.

---

## Features

- Single-file application
- Modern responsive interface
- Multi-chat support
- Local chat history
- Search conversations
- Rename and delete chats
- Import and export chats
- File attachment support
- Image preview support
- Markdown rendering
- Code block formatting
- Syntax highlighting
- Light theme
- Dark theme
- System theme
- Local profile management
- Configurable AI model
- Configurable Cloudflare Worker endpoint
- OpenRouter compatible
- Local settings storage
- Responsive mobile layout
- Legacy browser friendly
- MIT Licensed

---

## Architecture

```
Browser
      │
      ▼
Ultimate AI Lite
      │
      ▼
Cloudflare Worker
      │
      ▼
OpenRouter
      │
      ▼
AI Model
```

---

## Project Structure

```
.
├── index.html
├── worker.js
├── README.md
├── CONTRIBUTING.md
└── LICENSE
```

---

## Getting Started

### Clone

```bash
git clone https://github.com/rakibul5879/ultimate-ai-lite.git
```

### Deploy

Upload the project to:

- GitHub Pages
- Cloudflare Pages
- Netlify
- Vercel
- Any static web server

Deploy the included Cloudflare Worker and configure your OpenRouter API key.

Update the Worker endpoint inside the application settings.

---

## Configuration

Configure the following values:

- Worker Endpoint
- OpenRouter Model
- Temperature
- Top P
- Maximum Tokens

All settings are stored locally in the browser.

---

## Requirements

- Modern web browser
- JavaScript enabled
- Cloudflare Worker
- OpenRouter API Key

---

## Security

Ultimate AI Lite never stores API keys inside the frontend.

All requests are routed through your Cloudflare Worker, where secrets remain protected.

Chats, preferences, and settings remain stored locally unless exported by the user.

---

## Browser Support

- Chrome
- Chromium
- Microsoft Edge
- Firefox
- Brave
- Opera
- Android Browser
- Older Chromium-based browsers

---

## Roadmap

- Streaming responses
- Multiple providers
- Plugin system
- Voice input
- Image generation
- Conversation folders
- Prompt library
- Offline mode
- PWA support

---

## Contributing

Contributions are welcome.

Please read the project's CONTRIBUTING.md before opening an issue or submitting a pull request.

---

## License

Released under the MIT License.

See the LICENSE file for details.

---

## Author

[Rakibul Islam](https://github.com/rakibul5879/)

[GitHub](https://github.com/)

[Cloudflare](https://cloudflare.com/)
