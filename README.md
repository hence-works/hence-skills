# hence-skills

Agent skills maintained by **hence-works** — reusable `SKILL.md` packages for Claude Code, Codex, Cursor and other coding agents.

## What is a skill?

A skill is a folder with a `SKILL.md` file (YAML frontmatter with `name` and `description`, followed by instructions) plus any scripts, templates or reference files it needs. The agent reads the `description` to decide when to load the skill, then follows its instructions. See the [Agent Skills spec](https://github.com/anthropics/skills) for details.

```
skills/
  my-skill/
    SKILL.md
    scripts/
    references/
```

## Notable skills repositories on GitHub

The most-starred skills repositories as of November 2026 (star counts are approximate and taken from GitHub on 2026-11-17).

### Official / vendor collections

| Repository | Stars | What it is |
| --- | ---: | --- |
| [anthropics/skills](https://github.com/anthropics/skills) | ~196k | Anthropic's public repository and reference spec for Agent Skills |
| [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | ~47k | Anthropic-managed directory of Claude Code plugins (skills, agents, hooks) |
| [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins) | ~36k | Plugins and skills for knowledge workers in Claude Cowork |
| [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) | ~34k | Vercel's official agent skills collection |
| [openai/skills](https://github.com/openai/skills) | ~29k | Skills catalog for Codex |
| [huggingface/skills](https://github.com/huggingface/skills) | ~11k | Skills for working with the Hugging Face ecosystem |
| [microsoft/skills](https://github.com/microsoft/skills) | ~3k | Skills, MCP servers and agents for grounding coding agents in Microsoft SDKs |

### Frameworks and large skill libraries

| Repository | Stars | What it is |
| --- | ---: | --- |
| [obra/superpowers](https://github.com/obra/superpowers) | ~319k | Agentic skills framework and software-development methodology |
| [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | ~118k | Production-grade engineering skills for AI coding agents |
| [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | ~117k | Design "taste" skills: art direction, references, browser checks |
| [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | ~57k | Skills library for scientific research |
| [obsidianmd/obsidian-skills](https://github.com/obsidianmd/obsidian-skills) | ~53k | Skills for Obsidian CLI and its open formats |
| [sickn33/agentic-awesome-skills](https://github.com/sickn33/agentic-awesome-skills) | ~50k | 2,900+ reusable skills for Claude Code, Codex, Cursor and Gemini CLI |
| [wshobson/agents](https://github.com/wshobson/agents) | ~43k | Plugins, agents, skills and commands across many coding agents |
| [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) | ~30k | 400+ Claude Code skills, agents and commands |
| [Jeffallan/claude-skills](https://github.com/Jeffallan/claude-skills) | ~12k | 67 specialised skills for full-stack developers |

### Popular single-purpose skills

| Repository | Stars | What it is |
| --- | ---: | --- |
| [tt-a1i/archify](https://github.com/tt-a1i/archify) | ~97k | Turns ideas, plans or codebases into interactive diagrams |
| [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) | ~74k | Multi-phase security audits with verified, machine-readable findings |
| [blader/humanizer](https://github.com/blader/humanizer) | ~70k | Removes signs of AI-generated writing from text |
| [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) | ~68k | Researches a topic across Reddit, X, YouTube, HN and the web |
| [heydamir/unslop](https://github.com/heydamir/unslop) | ~17k | Turns generic AI-looking UI into a designed interface |
| [SawyerHood/dev-browser](https://github.com/SawyerHood/dev-browser) | ~7k | Gives an agent a web browser |

### Curated lists and directories

| Repository | Stars | What it is |
| --- | ---: | --- |
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | ~80k | Curated list of Claude Skills, resources and tools |
| [github/awesome-copilot](https://github.com/github/awesome-copilot) | ~41k | Community instructions, agents and skills for GitHub Copilot |
| [travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills) | ~16k | Curated list of Claude Skills, focused on Claude Code |
| [BehiSecc/awesome-claude-skills](https://github.com/BehiSecc/awesome-claude-skills) | ~10k | Curated list of Claude Skills |
| [davepoon/buildwithclaude](https://github.com/davepoon/buildwithclaude) | ~4k | Hub for skills, agents, commands, hooks and plugin marketplaces |

## License

TBD.
