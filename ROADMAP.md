# Vidora roadmap

What we are working on, what comes next, and what we are exploring. The order follows your votes: add a 👍 to [Ideas](https://github.com/romainGouraud/vidora/discussions/categories/ideas) and to [site requests](https://github.com/romainGouraud/vidora/issues?q=is%3Aopen+label%3Asite-request+sort%3Areactions-%2B1-desc).

*Last updated: October 16, 2026.*

## In progress

- **Two new free online tools**: MKV to MP4, and video to GIF, both working in your browser without upload.
- **Microsoft Edge Add-ons listing**: developer account verified, version 1.0.77 submitted to Microsoft for review (October 12, 2026).

## Next

- **More course platforms**, starting with Teachable, Kajabi and Patreon, with the same "whole course" card as on Skool where the platform allows it.
- **Online tools in more languages.**
- **Resume after a browser crash for streams with a separate audio track in MPEG-TS** (1.0.79 covers single-track MPEG-TS and fMP4 streams).

## Exploring

- **Firefox version.**
- **Instagram videos** (separate picture and sound tracks to pair reliably).
- **Subscriber-only Twitch VODs** (public clips and VODs already work).

Ideas move from Exploring to Next when they get votes and are technically possible.

## Recently shipped

**1.0.79 (October 16, 2026)**: Google Drive videos downloaded as the original file, with sound; resume after a browser crash for the most common stream format (MPEG-TS), with a check that the server still sends the same video; steadier Vimeo messages; save retry also without notifications.

**1.0.78 (October 15, 2026)**: downloads continue on their own after a quick browser restart; faster Skool lessons; quality choice on more servers; a clear message instead of silence on unreadable Vimeo videos; one automatic retry when Chrome briefly fails to save a finished file.

**1.0.77 (October 12, 2026)**: a stream whose server briefly returns errors (502, 503) no longer fails the whole download; rating and sharing links open the store you installed from.

**1.0.76 (October 11, 2026)**: long downloads that survive interruptions and slow servers; quality lists loading on more sites; placeholder files no longer saved as a success; better course platform support; "Retry save" when the disk is full; capture while playing from the button on the video.

**1.0.75 (October 10, 2026)**: live streams recorded until you press Stop; capture while playing; whole Skool courses; Bilibili; MKV instead of raw .ts; MP3 audio; subtitles as SRT; file name templates; preview and copy (link, ffmpeg, yt-dlp); Brave "disk full" fix.

Full history: [changelog](https://getvidora.com/changelog/?utm_source=github&utm_medium=roadmap).

## Never

YouTube (Chrome Web Store policy) and DRM-protected services (Netflix, Disney+, Prime Video...). Vidora does not bypass copy protection.
