# YouTubeLite

A lightweight, SmartTube-inspired iPhone PWA proof of concept.

## Goal
Test YouTube playback and background audio inside a standalone iOS PWA before building a larger interface. This version uses YouTube's official embedded player. It does not reproduce Brave Shields or guarantee background audio.

## Deploy
In GitHub repository Settings → Pages, choose Deploy from a branch, main, /(root), and Save. Once published, open https://reskalis.github.io/YouTubeLite/ in Safari and choose Share → Add to Home Screen with Open as Web App enabled.

## Test
Paste a YouTube video link, tap Load video, press Play in the embedded player, lock the iPhone, and see whether audio continues or can be resumed via Control Center.

## Limitations
YouTube embeds may show ads and may prevent background playback on iOS. AdGuard Safari extensions do not automatically apply to standalone PWAs. This is a feasibility test, not a SmartTube port.