# Vidora roadmap

What we are working on, what comes next, and what we are exploring. The order follows your votes: add a 👍 to [Ideas](https://github.com/romainGouraud/vidora/discussions/categories/ideas) and to [site requests](https://github.com/romainGouraud/vidora/issues?q=is%3Aopen+label%3Asite-request+sort%3Areactions-%2B1-desc).

*Last updated: October 21, 2026.*

## In progress

- **Fewer failed downloads, from real failures**: each release starts from the anonymous error reports (no addresses, no file names) and fixes the most frequent causes first.
- **Microsoft Edge Add-ons**: the listing is public (1.0.77); version 1.0.84 is in review at Microsoft, and 1.0.85 is uploaded and will follow right after.
- **Measuring what matters, privately**: a daily anonymous signal (no identifier, no address) to count active devices and check each fix, with a screen in Settings that shows exactly what is sent.

## Next

- **Resume after a crash for direct downloads**: large single files restart where they stopped instead of from zero.
- **More course platforms**: Kajabi and Patreon next, with the same "whole course" card as on Skool and Teachable where the platform allows it.
- **Online tools in more languages.**
- **Resume after a browser crash for streams with a separate audio track in MPEG-TS** (1.0.79 covers single-track MPEG-TS and fMP4 streams).

## Exploring

- **Firefox version.**
- **Subscriber-only Twitch VODs** (public clips and VODs already work).

Ideas move from Exploring to Next when they get votes and are technically possible.

## Recently shipped

**1.0.85 (submitted October 21, 2026)**: public broadcasters (Arte, ARD Mediathek, SVT Play, Yle Areena) with whole series; on-device transcription and chapter suggestions with Chrome's built-in AI; a keyboard shortcut for the side panel; videos found again when you come back to a tab; detection code loaded only where a video can play (about four times lighter on pages full of ad frames); rate limits handled per server; every assembled video checked before delivery; one memory budget for large downloads; security hardening (no requests to your local network from a page's stream list, sender checks on page messages).

**1.0.84 (submitted October 20, 2026)**: faster large downloads over several connections; complete subtitles (HLS, DASH, Vimeo) with your preferred language and on-device translation; the side panel becomes a download manager (search, filters, "Already downloaded" badge, show in folder); the video you are watching comes first; rename in the card; "Capture" on the in-page button; title, date and thumbnail written into the MP4; keyboard and screen reader accessibility; a "What Vidora sends" screen; better detection of players that load videos in a background worker; multi-part DASH videos assembled into one file; Hotmart lessons keep downloading when their token expires.

**1.0.83 (October 18, 2026)**: clear Vimeo messages, in your language, when Chrome's site access setting or an anti-robot check blocks the player; one card per Bunny Stream video; no double download when Chrome stops the extension mid-transfer ("Resume" is offered instead); fixes for streams refused with the page address, servers refusing bursts, lists of lists, players added late and expired signed links.

**Online tools (October 18, 2026)**: [MKV to MP4](https://getvidora.com/tools/mkv-to-mp4-converter/) and [video to GIF](https://getvidora.com/tools/video-to-gif/), free, in your browser, nothing uploaded.

**1.0.82 (October 18, 2026)**: Skool lessons whose video is on Vimeo, Loom or Wistia are now part of the whole-course download; Bunny Stream "play" links found and downloaded; torrent links no longer shown as videos; a clear state instead of endless retries when Chrome blocks Vidora on the Vimeo player.

**1.0.81 (October 17, 2026)**: Teachable courses (a lesson with its sound and real title, the whole course in one click); Kajabi and Wistia videos with their real title and a single card; sound kept on videos offered in several languages; a clear message when a site's video can only be read by its own player.

**1.0.80 (October 16, 2026)**: Instagram reels, video posts and carousels with sound, at the best quality available; "Audio only" always saves a real .m4a file; Vimeo videos opened a while ago no longer fail on an expired link; more Vimeo videos found on course platforms; an easier-to-read review request.

**1.0.79 (October 16, 2026)**: Google Drive videos downloaded as the original file, with sound; resume after a browser crash for the most common stream format (MPEG-TS), with a check that the server still sends the same video; steadier Vimeo messages; save retry also without notifications.

**1.0.78 (October 15, 2026)**: downloads continue on their own after a quick browser restart; faster Skool lessons; quality choice on more servers; a clear message instead of silence on unreadable Vimeo videos; one automatic retry when Chrome briefly fails to save a finished file.

**1.0.77 (October 12, 2026)**: a stream whose server briefly returns errors (502, 503) no longer fails the whole download; rating and sharing links open the store you installed from.

**1.0.76 (October 11, 2026)**: long downloads that survive interruptions and slow servers; quality lists loading on more sites; placeholder files no longer saved as a success; better course platform support; "Retry save" when the disk is full; capture while playing from the button on the video.

**1.0.75 (October 10, 2026)**: live streams recorded until you press Stop; capture while playing; whole Skool courses; Bilibili; MKV instead of raw .ts; MP3 audio; subtitles as SRT; file name templates; preview and copy (link, ffmpeg, yt-dlp); Brave "disk full" fix.

Full history: [changelog](https://getvidora.com/changelog/?utm_source=github&utm_medium=roadmap).

## Never

YouTube (Chrome Web Store policy) and DRM-protected services (Netflix, Disney+, Prime Video...). Vidora does not bypass copy protection.
