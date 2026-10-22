# Handoff: where we stopped (22 Oct 2026)

**Goal:** the owner films; Claude edits the videos, writes captions and hashtags, schedules the posts and tracks results. The owner approves each video and gives feedback.

## Already in this repo
- `prompolu-content-strategy.md`: niche analysis, competitors, 25 ideas, 30-day plan
- `tiktok-reels-ideas.md`: 20 TikTok/Reels ideas
- `viral-video-playbook.md`: detailed brief for each of the 20 ideas, six-week calendar
- `prompolu-social-media-workbook.xlsx`: everything above in Excel, plus a calendar and a results tracker
- `data/niche-tiktok-videos.csv`: 479 niche videos with stats

## What we found about connecting accounts
- No connector in the directory posts organic videos to TikTok or Instagram (the ones found are for ads or analytics).
- **Metricool** is the realistic route. Free plan: €0, 1 brand, all networks except LinkedIn and X, up to 20 scheduled posts a month, 30 days of analytics. Its MCP connector works on every plan, free included.
- **Not confirmed:** whether the connector can schedule TikTok videos and Reels, and whether a video sent to both platforms counts as one post or two toward the 20.
- Videos must be given to Metricool as a link: a public URL, or a file in a linked Google Drive or Dropbox. Drive and Dropbox connectors exist; whether they handle full-size video files is untested.
- Not available through the connector: reading or answering comments and DMs.
- Paid Starter plan, if the cap blocks us: about €16–20 a month ($20–25).

## Editing tools tested
- ffmpeg with libass, harfbuzz and fribidi works. An Arabic (Darija) hook rendered correctly, joined and right-to-left, on a real clip. Auto-fit the text size to the frame width and keep it clear of the phone number burned into the upper third of the footage.
- No speech-to-text installed, so there are no automatic subtitles yet. Try installing one; fall back to the owner typing what is said.

## Next steps
**Owner:** switch Instagram to a Professional account; sign up for Metricool's free plan; link @prompolu on TikTok and Instagram; add the Metricool connector and the Google Drive or Dropbox connector at claude.ai/customize/connectors; start a **new** session (connectors only load at session start); send the first video.

**Claude:** edit the first video, write its post pack (caption, 3–5 hashtags, hook text, pinned comment, Reels caption), get the owner's approval, then try to schedule one TikTok and one Reel. Report whether TikTok/Reels scheduling works, how posts are counted, and whether video files transfer. Then recommend free or paid.

## Working rules
- Never schedule or post anything before the owner approves it.
- Never ask for passwords; connect through the official sign-in flows.
- Every video: 9:16, hook text in the first second, phone number on the video (not in the caption), 3–5 hashtags (a city, a category, one Arabic tag), original sound.
- Check technical claims (weights, sizes, finishes) against the STRUGAL sheets before publishing.

## Open items
- prompolu.com links to `@fesal.aluminium` on TikTok and Instagram, but the accounts are `@prompolu`. The owner should check and fix the links.
- Instagram posts could not be read, so nothing in the research about Instagram content is measured. Ask for Insights screenshots.
