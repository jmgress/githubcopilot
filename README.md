# GitHub Copilot Presentation

A comprehensive presentation deck about using GitHub Copilot to supercharge coding in VS Code. This presentation was created using GitHub Copilot itself, demonstrating the tool's capabilities in action.

The deck is a self-contained HTML file ([slides/index.html](slides/index.html)) with no external/CDN dependencies — all styles and the slide engine live inline, and images are local PNGs in `slides/img/`, so it runs offline in any browser.

**Presented by:** James Gress, AI Director @ Accenture  
**GitHub Pages:** [https://jmgress.github.io/githubcopilot/](https://jmgress.github.io/githubcopilot/)

## 🎯 Presentation Overview

This slide deck covers:

- **AI-Generated Code Trends** - CEO insights and industry statistics (2025)
- **Copilot Fundamentals** - Strengths, weaknesses, and best practices
- **Prompt Engineering** - Creating effective prompts for better results
- **Working Modes** - Ask, Edit, Agent, and Plan modes explained
- **Advanced Features** - MCP servers, custom instructions, and prompt files
- **GitHub Copilot CLI** - AI assistance in your terminal
- **Coding Agent** - Autonomous development workflows
- **Privacy & Security** - Understanding Blackbird indexing and data handling

## 🚀 Key Topics Covered

### Core Concepts
- Ghost text and code completion
- Context management (avoiding context creep and confusion)
- Keyboard shortcuts and productivity tips
- Chat history navigation

### Advanced Features
- Model Context Protocol (MCP) servers for GitHub and Jira integration
- Custom chat modes and prompt files
- AI-readable documentation with Mermaid diagrams
- Copilot instructions file (`.github/copilot-instructions.md`)
- Sparkles and AI indicators

### Development Workflows
- Ask vs Edit vs Agent vs Plan modes comparison
- Multi-file task management with `@workspace`
- Strategic development planning with Plan Mode
- GitHub Copilot Coding Agent for autonomous development

## 📁 Project Structure

```
githubcopilot/
├── slides/
│   ├── index.html         # The presentation (inline CSS + slide engine)
│   └── img/               # PNG images referenced by index.html
├── .github/
│   └── workflows/         # GitHub Actions for deployment
├── .devcontainer/         # Dev container configuration
└── README.md
```

## 🎨 Getting Started

### View the Presentation

Visit the live presentation: [https://jmgress.github.io/githubcopilot/](https://jmgress.github.io/githubcopilot/)

### Local Development

1. Open `slides/index.html` directly in any web browser (double-click it, or use a local server / VS Code Live Preview).
2. Edit the markup, styles, or slide engine in `slides/index.html` — everything lives in that one file.
3. Refresh the browser to see changes.

### Navigating the Deck

| Key | Action |
|-----|--------|
| `→` / `Space` / `PgDn` | Next slide |
| `←` / `PgUp` | Previous slide |
| `Home` / `End` | First / last slide |
| `S` | Toggle speaker notes |
| `F` | Toggle fullscreen |
| `?` | Show keyboard help |

The deck also supports click-to-advance, touch swipe, and deep-linking to a slide via the URL hash (e.g. `index.html#12`).

### Export to PDF

Open the deck in a Chromium-based browser and use **Print → Save as PDF** (landscape). The print stylesheet renders one slide per page.

### Updating Images

Images live in `slides/img/` as PNG files and are referenced from `index.html` by relative path (e.g. `img/name.png`). To change an image, replace the PNG in that folder (or add a new one and update the matching `src` / `background-image`). Keep `index.html` and the `img/` folder together when deploying or sharing.

## 🚢 Publishing on GitHub Pages

This repository is configured to automatically publish to GitHub Pages:

1. Push changes to the `main` branch
2. GitHub Actions copies `slides/index.html` to the site root
3. The site is published to `https://jmgress.github.io/githubcopilot/`

To set up for your own repository:
1. Navigate to `Settings` > `Pages` > `Build and deployment`
2. Select `Source`: `GitHub Actions`
3. The workflow will run automatically on push

## 📚 Resources

### GitHub Copilot
- [GitHub Copilot Documentation](https://docs.github.com/en/copilot)
- [GitHub Copilot CLI](https://docs.github.com/en/copilot/concepts/agents/copilot-cli/about-copilot-cli)
- [Model Context Protocol (MCP)](https://modelcontextprotocol.io/)

### Web & Deployment
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Printing to PDF from the browser](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/print)

## 📄 License

This repository is licensed under the [MIT License](LICENSE). Feel free to reuse or extend the code as you wish, but include the original license.

## 👤 About the Author

**James Gress**  
AI Director @ Accenture  
Advanced Technology Center AI Lead

- LinkedIn: [jamesgress](https://linkedin.com/in/jamesgress/)
- GitHub: [jmgress](https://github.com/jmgress)
- X.com: [@jmgress](https://x.com/jmgress)
- Meetup: [Tampa Bay Generative AI Meetup](https://www.meetup.com/tampa-bay-generative-ai-meetup/)

---

**Note:** This entire slide deck was created using GitHub Copilot, demonstrating its capabilities in content creation and documentation.
