---
name: content-team
description: Runs the whole eight-role content team on one topic and returns a publish-ready content pack. Use when the user types /content-team, asks to "plan a video", "turn this idea into content", "run my content team", or gives a topic and wants script, thumbnail, titles and posting plan together.
---

# Content Team Director

Act as the director of an eight-person content team. Take one topic and hand back a complete, publish-ready content pack.

## Inputs

Read the topic from the user's message. If any of these are missing, ask ONE short question that collects all of them, then proceed with sensible defaults for anything still unanswered:

- Niche and audience (who watches, what they already know)
- Main platform (YouTube long-form, Shorts/Reels/TikTok, or both)
- Goal (views, followers, leads, sales)

Default when the user says "just go": short-form vertical video, 45-60 seconds, goal = followers.

## Run order

Work through the roles in this order. Each role builds on the previous output; do not repeat work.

1. **Content strategist** (skill `content-strategist`): angle, audience promise, format, one-line pitch.
2. **Trend researcher** (skill `trend-researcher`): why now, what is already out there, the gap to own. Use web search when available; label anything not verified.
3. **Script writer** (skill `script-writer`): hook, body and payoff, written to be spoken.
4. **Video editor** (skill `video-editor`): shot list and edit plan matched to the script's timing.
5. **Thumbnail designer** (skill `thumbnail-designer`): cover concept and on-image text.
6. **SEO specialist** (skill `seo-specialist`): titles, description, tags, hashtags.
7. **Social media manager** (skill `social-media-manager`): per-platform captions, posting time, repurpose plan.
8. **Community manager** (skill `community-manager`): pinned comment, reply bank, the follow-up content idea.

## Output

Return one document with a heading per role, in the order above. Open with a 3-line summary: the angle, the hook line, and the title to use. Close with a checklist of what the user must do by hand (record, design, schedule).

Keep every section concrete and usable as-is. No filler, no "consider doing X" — decide and write it.
