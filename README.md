# GitHub Copilot Presentation

A comprehensive presentation deck about using GitHub Copilot to supercharge coding in VS Code. This presentation was created using GitHub Copilot itself, demonstrating the tool's capabilities in action.

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
│   ├── Slides.md          # Main presentation content
│   ├── img/               # Presentation images
│   └── themes/            # Custom Marp themes
│       ├── custom-default.css
│       ├── custom-gaia.css
│       ├── custom-uncover.css
│       └── custom.css
├── .github/
│   └── workflows/         # GitHub Actions for deployment
├── .devcontainer/         # Dev container configuration
└── README.md
```

## 🎨 Getting Started

### View the Presentation

Visit the live presentation: [https://jmgress.github.io/githubcopilot/](https://jmgress.github.io/githubcopilot/)

### Local Development

1. Install [Visual Studio Code](https://code.visualstudio.com/)
2. Install the [Marp for VS Code extension](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)
3. Open `slides/Slides.md` in VS Code
4. Use the Marp preview to view and edit slides

### Export Options

The Marp extension allows you to export to:
- **PDF** - For sharing and printing
- **PowerPoint (PPTX)** - For further editing
- **HTML** - For web hosting
- **PNG/JPEG** - Individual slide images

## 🎨 Custom Themes

This presentation uses custom Marp themes located in `slides/themes/`:

- `custom-default.css` - Based on the built-in default theme
- `custom-gaia.css` - Based on the built-in gaia theme  
- `custom-uncover.css` - Based on the built-in uncover theme
- `custom.css` - Fully custom theme

The active theme is specified in the `Slides.md` frontmatter:

```yaml
---
marp: true
theme: custom-default
---
```

## 🚢 Publishing on GitHub Pages

This repository is configured to automatically build and publish to GitHub Pages:

1. Push changes to the `main` branch
2. GitHub Actions will automatically build the presentation
3. The site will be published to `https://jmgress.github.io/githubcopilot/`

To set up for your own repository:
1. Navigate to `Settings` > `Pages` > `Build and deployment`
2. Select `Source`: `GitHub Actions`
3. The workflow will run automatically on push

## 📚 Resources

### Marp Documentation
- [Marp Official Repository](https://github.com/marp-team/marp)
- [Marp Official Documentation](https://marpit.marp.app/markdown)
- [Marp for VS Code Documentation](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)
- [Custom Theme Documentation](https://marpit.marp.app/theme-css)

### GitHub Copilot
- [GitHub Copilot Documentation](https://docs.github.com/en/copilot)
- [GitHub Copilot CLI](https://docs.github.com/en/copilot/github-copilot-in-the-cli)
- [Model Context Protocol (MCP)](https://modelcontextprotocol.io/)

### Markdown
- [CommonMark Syntax Reference](https://commonmark.org/help/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)

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
