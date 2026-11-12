# rex skills

SEO skills for your AI agent, powered by [rex](https://www.rexmetrics.com).

rex gives your agent real SEO data. These skills guide it through complete jobs, like a site audit or keyword research, so you get a clear answer instead of generic advice.

You need a rex account. The first time your agent uses rex, it asks you to sign in.

## Install

The easiest way: open **Agent setup** in rex, copy the setup prompt, and paste it into your agent. It does the steps below for you.

### Claude Code

```
/plugin marketplace add rmznovali/rex-skills
/plugin install rex@rex
```

### Claude desktop app and Cowork

Open **Customize** → **Plugins** → **+** → **Add marketplace** → **Add from a repository**, enter `https://github.com/rmznovali/rex-skills`, then install **rex**.

### Codex

```bash
codex plugin marketplace add rmznovali/rex-skills
codex plugin add rex@rex
codex mcp login rex
```

### Other agents

Add the rex server `https://app.rexmetrics.com/mcp` to your agent, then install the skills:

```bash
npx skills add https://github.com/rmznovali/rex-skills/tree/main/plugins/rex/skills
```

## Update

- **Claude Code:** `/plugin marketplace update rex`, then `/plugin update rex@rex`.
- **Codex:** `codex plugin marketplace upgrade rex`.
- **Other agents:** `npx skills update`.

## Skills

| Skill | What it does |
| --- | --- |
| `seo-coach` | Explains where you stand and picks your next step. |
| `seo-project-setup` | Saves your goals, competitors, and key pages as shared context. |
| `seo-audit` | One-page site audit built around a single do-this-week action. |
| `ai-visibility-audit` | Finds the few changes most likely to get you cited in AI answers. |
| `ai-prompt-research` | Finds what people ask ChatGPT about your market and who gets cited. |
| `keyword-research` | Finds keyword opportunities from a few seed topics. |
| `keyword-clustering` | Groups keywords by intent and maps them to pages. |
| `competitive-landscape` | Maps who wins in your market and why. |
| `competitor-analysis` | Studies one competitor's keywords, content, and backlinks. |
| `link-prospecting` | Finds link prospects and drafts outreach. |
| `local-seo` | Audits a Google Business Profile and Maps visibility. |
| `seo-report` | Saves any of the above as a report on your Reports page. |

## Support

Email [hello@gomia.ai](mailto:hello@gomia.ai).

## License

MIT. See [LICENSE](./LICENSE).
