# Liso privacy policy

_Last updated: November 13, 2026_

Liso is a Chrome extension that makes video smoother by drawing in-between frames on your own computer's GPU.

## Data collected

**None.** Liso doesn't collect, store, sell or send any personal or browsing data.

- **Video:** the frames of the video you're watching are processed **only on your computer**, in your GPU's memory, to draw the in-between frames. No image, sound or information about the video leaves your computer.
- **Sites:** the extension runs on the pages you open to find `<video>` elements. It doesn't read page text, forms, passwords or history, and doesn't record which sites you visit.
- **Settings:** your preferences (on/off, output rate, quality, audio sync, appearance, language, diagnostics options and the list of sites where it's off) are kept in `chrome.storage.sync`. If Chrome sync is on, Chrome itself syncs them across your devices through your Google account; Liso has no access to that service and runs no server of its own.
- **Network:** the extension makes no network requests.

## Permissions

| Permission | Why |
|---|---|
| Site access (content script on all pages) | Find the videos on the page and draw the smoothed version over them. |
| `storage` | Keep your preferences. |
| `activeTab` | In the popup, show the current tab's address for the "Run on this site" switch and ask its video for live status. |

## Protected content (DRM)

Liso doesn't get around content protection. DRM-protected video (for example Netflix, Prime Video, Crunchyroll) isn't processed: the browser doesn't expose those frames, and the extension simply leaves them alone.

## Contact

Privacy questions: `kaue.malheiros@gmail.com`
