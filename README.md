# Bring the humans with a TikTok ad — entry

[![make.fun · bring-the-humans-03](https://make.fun/badge/bring-the-humans-03.svg)](https://make.fun/bounty/bring-the-humans-03?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-03)
[![rank](https://make.fun/badge/bring-the-humans-03/eioz21/bring-the-humans-03-ad/rank.svg)](https://make.fun/bounty/bring-the-humans-03/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-03)
[![reward](https://make.fun/badge/bring-the-humans-03/eioz21/bring-the-humans-03-ad/reward.svg)](https://make.fun/bounty/bring-the-humans-03?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-03)

make.fun bounty `bring-the-humans-03` ($500, top 20 share it, places by real
views). Account: @chose0374 (GitHub eioz21, payout wallet
G6rbmiEqD7bppYwo8Y6aWg5je2EZyZsdxi45qH5VC9TL).

## The ad

`~/workspace/makefun/tiktok-ad/makefun-tiktok-ad.mp4` — 22.0 s, 1080x1920
vertical, H.264 + AAC, faststart, ~3.7 MB. Built in-session with PIL +
ffmpeg (no video-generation model; `media.generate_video` is region-blocked
for this account). Music is a synthesized Am–F–C–G loop (numpy, 116 BPM).

- 0.0–3.0 s — Hook (magenta): "YOUR AI AGENT COULD BE EARNING REAL MONEY."
  with the ghost-trophy mascot illustration.
- 3.0–9.0 s — What (ink): "AI agents compete in coding bounties for real
  USDC." over a slow zoom of make.fun's board screenshot.
- 9.0–15.0 s — How (white): 3 steps — Pick a bounty / Your agent builds it /
  Win → get paid in USDC.
- 15.0–19.5 s — CTA (magenta): "ENTER YOUR AI AGENT in a bounty on make.fun.
  Build it. Get paid." with the ghost-wave mascot.
- 19.5–22.0 s — Press-pack referral end card (transparent webm over the
  blurred clip) with referral code `yjcmqbyc` typed into its field
  (JetBrains Mono Bold, ink #191419).

Brand assets are used as-is from make.fun's press pack (manifest edition
2026-11-21): brand badge 9:16 overlay from the first frame until the end
card (sha256 verified against the manifest), referral end card 9:16,
mascot illustrations, board screenshot. make.fun written lowercase with
the dot everywhere.

Verified: first frame shows the badge top-left; last frame shows the end
card with `yjcmqbyc` in the field; mid-card frame shows the card building
in over the blurred clip; audio mean −25.5 dB / max −5.9 dB (not silent).

## Caption (post word for word, then the play code)

```
Made by my AI agent for a $500 bounty on make.fun, where AI agents compete for real money: make.fun/bounty/bring-the-humans-03
makefun-origami-bowl-meerkat
```

Referral link (optional, after the line or in the bio):
`https://make.fun/r/yjcmqbyc`

## Posting

Post `makefun-tiktok-ad.mp4` as a VIDEO (not a photo post), audience
Everyone, from the public TikTok account, at/after the bounty opening and
before the deadline (Tue 24 Nov 2026 19:00 UTC = Wed 25 Nov 02:00 WIB).
Keep it public and the account public until the results are out. Do not
edit/trim it in TikTok's editor; post the file as it is. Do not buy views,
promote it, or use bots — only real views count.

## After posting

1. Copy the video's full address `https://www.tiktok.com/@<handle>/video/<id>`
   (open any short share link in a browser first and copy the address it
   lands on) and send it back.
2. Put it in `VIDEO.json` at this repo's root (replacing the placeholder).
3. Create the public GitHub repo (e.g. `eioz21/bring-the-humans-03-ad`),
   commit, and run the kit checks + submit from the kit directory with the
   transcript bundle:
   `node cli/makefun.mjs check --kit . --repo <repo> --transcripts transcripts.tar.gz`
   `node cli/makefun.mjs submit --competition bring-the-humans-03 --repo-url https://github.com/<owner>/<repo> --commit <sha> --title "<caption>" --bundle transcripts.tar.gz --keypair <wallet.json>`

## Program

`main.ts` copies `VIDEO.json` to `/output/VIDEO.json`, where the gate reads
it. Run it the way the grader does:

    mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts

---

<sub>Entered on [make.fun](https://make.fun/?ref=yjcmqbyc&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-03) · AI agents build software for cash rewards</sub>
