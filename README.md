<p align="center">
  <img src="assets/icon.png" width="112" alt="SpotiTube" />
</p>

<h1 align="center">SpotiTube</h1>

<p align="center">
  <b>Your Spotify and YouTube Music libraries in one desktop player — with a queue you're in charge of.</b>
</p>

<p align="center">
  <a href="https://github.com/Roguu2/SpotiTube-releases/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/Roguu2/SpotiTube-releases?label=latest&color=1DB954&style=for-the-badge"></a>
  <a href="https://github.com/Roguu2/SpotiTube-releases/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/Roguu2/SpotiTube-releases/total?color=FF0033&style=for-the-badge"></a>
  <img alt="Windows and macOS" src="https://img.shields.io/badge/Windows%20%C2%B7%20macOS-18181d?style=for-the-badge">
</p>

<p align="center">
  <a href="https://github.com/Roguu2/SpotiTube-releases/releases/latest"><b>⬇ Download for Windows</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/Roguu2/SpotiTube-releases/releases/latest"><b>⬇ Download for macOS</b></a>
</p>

<p align="center">
  <img src="assets/library.png" alt="SpotiTube library with Spotify and YouTube Music playlists, the queue open on the right and the YouTube player docked in the sidebar" />
</p>

---

## Stop switching apps

Your playlists live in two places. SpotiTube puts them in **one window**: every playlist and every track carries a
colour-coded badge, so you always know where it came from.

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>One library, two services</h3>
      Spotify and YouTube Music playlists side by side. Filter by source, or open <b>Split View</b> to browse both
      catalogs in parallel columns.
    </td>
    <td width="50%" valign="top">
      <h3>Hybrid playlists</h3>
      Mix tracks from Spotify and YouTube Music in a single playlist. Add any track with one click, from any
      playlist or search result.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Search both at once</h3>
      One search box, results from both catalogs next to each other.
    </td>
    <td width="50%" valign="top">
      <h3>Pick the version you want</h3>
      Studio cut, live, remix, slowed, acoustic: swap the version of any track and SpotiTube remembers your
      choice.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Recently played</h3>
      Everything you listened to, from both services, grouped by day, with one-click <b>Jump back in</b> to the
      playlists you played from.
    </td>
    <td width="50%" valign="top">
      <h3>Resume where you left off</h3>
      Close the app mid-song and it comes back paused at the same spot, with your whole queue intact.
    </td>
  </tr>
</table>

| Split View | Hybrid playlists |
| --- | --- |
| ![Spotify and YouTube Music playlists in parallel columns](assets/split-view.png) | ![Adding a track to a new hybrid playlist](assets/hybrid-playlists.png) |

## Your queue, your rules

<table>
  <tr>
    <td width="55%" valign="top">
      <ul>
        <li><b>Play next</b> or <b>Add to queue</b> on any track: right-click it, or use the <b>⋯</b> button</li>
        <li>Mix tracks from Spotify and YouTube Music in the same queue</li>
        <li><b>Drag &amp; drop</b> to reorder, or <code>Alt</code> + <code>↑</code> / <code>↓</code></li>
        <li>Remove single tracks, clear what you queued, or clear everything</li>
        <li>Double-click any entry to jump straight to it</li>
        <li>Your picks play before the rest of the playlist, and shuffle leaves them where they are</li>
        <li>Swap the playing track for a live, remix or slowed version with <b>Change version</b></li>
        <li><b>Picks up where you left off</b>: your queue and the song you were on come back after a restart</li>
      </ul>
    </td>
    <td width="45%" valign="top">
      <img src="assets/queue.png" alt="Queue panel with the playing track and reorderable upcoming tracks" />
    </td>
  </tr>
</table>

## Feels like a native app

- **Taskbar controls**: hover over SpotiTube in the Windows taskbar to skip or pause, just like Spotify. On macOS
  the same controls are in the Dock menu.
- The current song appears in the window title, so you see it in the taskbar and when switching apps
- Media keys, system media controls and a tray menu
- Frameless, dark window designed for OLED screens, with a glow that follows the album art
- Keyboard shortcuts for everything: `Space`, `←` `→`, `Ctrl+F`, `Ctrl+E` (queue), …
- **Updates itself**: new versions download in the background and install with one click

> **Good to know:** YouTube currently doesn't let apps stream complete tracks directly, so most tracks play through
> **YouTube's official player**. It must stay visible, but you can make it compact, move it to any corner, or dock it
> in the sidebar where it covers nothing.

## Get started in a minute

1. **Download** the installer from the [latest release](https://github.com/Roguu2/SpotiTube-releases/releases/latest):
   - Windows 10/11: `SpotiTube-<version>-Setup.exe`
   - macOS 12+ (Intel and Apple Silicon): `SpotiTube-<version>-universal.dmg`
2. **Install and open it.** Sample Spotify and YouTube Music playlists are ready to play straight away, no account
   needed.
3. **Connect your accounts** in **Settings** to see your own library:
   - **YouTube Music:** search and playback work without an account. To load your own playlists and likes, paste a
     cookie from your signed-in browser; SpotiTube explains where to find it.
   - **Spotify:** create a free app in the
     [Spotify Developer Dashboard](https://developer.spotify.com/dashboard) and add your Spotify account under
     **User Management**. Then paste the app's Client ID and click **Connect**. You don't need Spotify Premium.

> The installers are not code-signed yet, so your system may warn you the first time:
> - **Windows:** SmartScreen → **More info** → **Run anyway**.
> - **macOS:** right-click the app → **Open**, then **Open** again.

## FAQ

<details>
<summary><b>Is it free?</b></summary>

Yes. SpotiTube is free, with no ads and no account of its own.
</details>

<details>
<summary><b>Do I need Spotify Premium?</b></summary>

No. Spotify provides your playlists and track details; the audio itself plays from YouTube Music, because Spotify
does not let third-party apps stream full tracks.
</details>

<details>
<summary><b>Where does the music come from?</b></summary>

From YouTube Music. Each Spotify track is matched to the best YouTube Music upload automatically: same song, same
artist, same length, and no covers or remixes unless you ask for one. You can always pick a different version.
</details>

<details>
<summary><b>Why is there a small YouTube player?</b></summary>

YouTube currently doesn't let apps stream complete tracks directly, so SpotiTube plays them through YouTube's
official player, which never cuts out. SpotiTube does not try to get around YouTube's protections. YouTube requires
the player to stay visible, but you can make it compact, move it to any corner, or dock it in the sidebar.
</details>

<details>
<summary><b>What happens to my data?</b></summary>

Everything stays on your computer. Your Spotify login and YouTube Music cookie are encrypted with your operating
system's keychain and are only ever sent to Spotify and YouTube. SpotiTube has no servers and collects no analytics.
</details>

<details>
<summary><b>How do updates work?</b></summary>

SpotiTube checks this page for new versions, downloads them in the background and offers **Restart to update**.
You can also check manually in **Settings → Updates**. On macOS, automatic installation needs a signed build; until
then the app links you to the new download instead.
</details>

<details>
<summary><b>Something doesn't play or sounds wrong.</b></summary>

Open the **queue** and use **Change version** under the playing track to pick another upload. SpotiTube remembers
your choice. If a problem persists, please describe it in a new issue in this repository.
</details>

---

<sub>SpotiTube is an independent project and is not affiliated with, endorsed by or sponsored by Spotify or
YouTube/Google. Spotify and YouTube Music are trademarks of their respective owners. Playback relies on YouTube
services and may change whenever they do.</sub>
