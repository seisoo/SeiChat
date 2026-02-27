# SeiChat
## EARLY STAGES

## Client
![img](https://github.com/seisoo/SeiChat/blob/main/screenshot_1_4_4.png?raw=true)


- **WebRTC (DTLS-SRTP)** voice with **8–320 kbit/s** bitrate  
  - **Relay-only transport**
  - Automatic **P2P or relay** selection
  - **TOFU** (Trust On First Use) + **2FA**

- **Voice channels**
  - Voice with optional **webcam**
  - **Screen sharing**
  - 3D spartial audio (move the clients around to hear them from specific direction at a certain volume)

- **Text channels**
  - Channel **banners**
  - Optional **18+ / NSFW tag**
  - **Link preview & analysis** via server (title/description/preview) — **your IP stays hidden**
  - **YouTube embedding**
  - Built-in **video player**
  - **GIF / WebP / image** support

- **File upload & download**
  - **Server-side encryption at rest** (files are stored encrypted on the server)
  - Decryption is only possible with your **`.env` keys**
  - Files are transferred through the API; content is **not end-to-end encrypted** so it can be displayed client-side when needed
  - Client also stores a **local encrypted cache** (images + GIFs only)

- **Spotify integration**
  - Connects only through your **own Spotify application**
  - No shared / public OAuth app credentials

- **OBS overlay (PNGTuber)**
  - Display other users using **custom images** (defaults to their avatars)
  - Custom **positioning**
  - **Row/column layout**
  - 4 animation states: **mouth** (open/closed) + **eyes** (open/blink)

- **Rich Presence**
  - Games + Spotify
  - Custom status

- **Radio bot**
  - Listen to your music together

- **UI**
  - Windows **Acrylic** transparent design

- **Per-server authentication**
  - Each server uses its **own authentication data**


## Server
Is currently hosted via docker compose and custom image
