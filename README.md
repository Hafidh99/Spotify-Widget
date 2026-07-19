<h3 align="center">🎵 Jamming Session</h3>
<p align="center">
  <a href="https://spotify-widget-lemon.vercel.app/api/orchestrator/redirect" target="_blank">
    <img src="https://spotify-widget-lemon.vercel.app/api/orchestrator?background_type=blur_dark&border_color=A855F7&show_status=true" alt="Spotify Widget" />
  </a>
</p>

---

## 🌟 Customizations (Fork Updates)

This fork includes some custom features added on top of the original widget to make it more interactive and realistic:

- **True BPM Synchronization**: The equalizer bars animation speed is perfectly synchronized with the actual BPM (tempo) of the song currently playing, dynamically fetched from the Spotify API.
- **Smart "Paused" State**: When Spotify is paused or nothing is playing:
  - The equalizer animation completely stops (no more dummy heartbeat).
  - The inner contents (album art, background, text, and equalizer bars) automatically switch to a grayscale color filter.
  - A red **[PAUSED]** stamp overlay appears on the album art so visitors immediately know the widget isn't broken, but rather no music is currently playing.
  - The custom widget border color (e.g., the purple border) remains fully vibrant!
