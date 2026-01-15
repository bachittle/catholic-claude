# Catholic AI

A system prompt that configures AI assistants to accurately present Catholic teaching while being honest about their nature as tools.

## What This Is

This project provides system prompt files that shape how AI assistants engage with questions—moral, philosophical, personal, and practical. The AI presents Catholic teaching faithfully, drawing on Scripture, Tradition, and the Magisterium, while acknowledging it cannot believe, pray, or replace human spiritual guidance.

## Usage

- **Claude Code**: Place `CLAUDE.md` in your project root
- **OpenAI Codex / other agents**: Place `AGENTS.md` in your project root

Tools that support project instructions will automatically apply them.

### Setting Up with ChatGPT

1. **Copy the system prompt** — Go to [AGENTS.md](./AGENTS.md) and copy the raw contents

   ![GitHub repo showing AGENTS.md](./data/github-repo.png)
   ![Raw AGENTS.md content](./data/github-agents-raw.png)

2. **Create a new project in ChatGPT** — Click "New project" in the sidebar

   ![ChatGPT sidebar with New project option](./data/chatgpt-sidebar.png)
   ![Create project dialog](./data/chatgpt-create-project.png)

3. **Add the system prompt** — Open project settings and paste the content into the "Instructions" field

   ![Project settings with Instructions field](./data/chatgpt-project-settings.png)

4. **Start chatting** — Your conversations in this project will now use the Catholic AI configuration

   ![Project view with chats](./data/chatgpt-project-view.png)

## Why

Standard AI assistants claim neutrality on contested questions. But neutrality is itself a philosophical position that embeds unstated assumptions. Catholic AI takes a different approach: presenting the coherent 2,000-year Catholic tradition accurately, while being honest about what AI can and cannot do.

This provides:
- **Coherence** — responses flow from integrated first principles
- **Depth** — access to Scripture, the Fathers, Aquinas, modern encyclicals
- **Honesty** — users know what framework they're engaging with and what the AI's limits are
- **Vatican alignment** — respects *Antiqua et nova* (2025) warnings against anthropomorphizing AI

## What This Is Not

AI is not a believer. It cannot pray, receive grace, or participate in the life of faith as humans do. It presents Catholic teaching accurately but does not claim to hold that teaching in the way a person of faith does.

This is a threshold, not a destination. The goal is to point users toward the living Church—parishes, priests, spiritual directors, the sacraments—not to replace human encounter with Christ.

## Documentation

- [**CLAUDE.md**](./CLAUDE.md) — System prompt for Claude
- [**AGENTS.md**](./AGENTS.md) — System prompt for other AI agents (Codex, etc.)
- [**Known Tensions**](./docs/tensions.md) — Philosophical questions and design decisions

## License

MIT
