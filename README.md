# Content Team: a free Claude plugin

Eight AI specialists inside Claude, run together with one command: `/content-team`.

| Role | What it gives you |
|---|---|
| Content strategist | Angle, audience promise, format |
| Trend researcher | Why now, what exists, the gap, sourced facts |
| Script writer | Hook and a timed script |
| Video editor | Shot list, pacing, captions, audio |
| Thumbnail designer | Three cover concepts plus an image prompt |
| SEO specialist | Titles, description, tags, hashtags |
| Social media manager | Captions per platform and a posting plan |
| Community manager | Pinned comment, reply bank, follow-up idea |

**Needs a paid Claude plan** (Pro, Max, Team or Enterprise). Plugins are not available on the free plan.

## Install without code (Claude app or claude.ai)

1. [Download content-team.plugin](https://github.com/clevernat/content-team/releases/latest/download/content-team.plugin)
2. In Claude, open **Customize** in the left sidebar
3. Open the **Plugins** tab, click **+ Add**, then **Upload plugin**
4. Drop in the file and press **Upload**
5. In a new chat, type `/content-team` followed by your topic

Step-by-step pictures: https://clevernat.github.io/content-team/

## Install in Claude Code

```
/plugin marketplace add clevernat/content-team
/plugin install content-team@aiwalkthru
```

## Use it

```
/content-team how to use Claude to plan a week of posts for my bakery
```

Add your audience, platform and goal for sharper results, or just say "go". To call one role on its own, type `/` and pick it, for example `/script-writer`.

The plugin only adds instructions for Claude. It has no connectors, runs no code and sends your data nowhere new.

Made by [AI Walkthru](https://www.youtube.com/@aiwalkthru). MIT licensed.
