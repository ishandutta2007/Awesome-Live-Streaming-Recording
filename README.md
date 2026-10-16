# Awesome-Live-Streaming-Recording

# Top Live Streaming & Recording Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Broadcasting, Screen Recording & Self-Hosted Streaming Infrastructure*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Live Streaming & Recording**. These tools enable content creators, broadcasters, and organizations to capture, mix, encode, and distribute live video to platforms like YouTube, Twitch, and custom RTMP endpoints — with emphasis on open-source, self-hostable solutions.

**Examples** include Streamlabs, vMix, Restream.io, StreamYard, Wirecast, Lightstream, BoxCast, Dacast, and Vimeo Livestream (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, RTMP ingestion, multi-platform restreaming, and local recording — ideal for streamers, broadcast engineers, and developers building transparent streaming infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Streamlabs](https://streamlabs.com/)**  
  Free and open-source streaming software built on OBS and Electron, with cloud-based features, alerts, and monetization tools .

- **[vMix](https://www.vmix.com/)**  
  Professional live production software for Windows with multi-camera switching, instant replay, and vMix Call. Plans range from **$60 (Basic HD)** to **$1,200 (PRO)** lifetime, or **$50/month (MAX)** .

- **[Restream.io](https://restream.io/)**  
  Cloud-based multistreaming service allowing simultaneous broadcast to 30+ platforms without additional encoding overhead.

- **[StreamYard](https://streamyard.com/)**  
  Browser-based live streaming studio for interviews, webinars, and multi-guest broadcasts with direct-to-platform streaming.

- **[Wirecast](https://www.telestream.net/wirecast/)**  
  Professional cross-platform live production software with unlimited inputs, built-in titles, and GPU-accelerated encoding.

- **[Lightstream](https://golightstream.com/)**  
  Cloud-based streaming studio with remote guest support and integrations for Xbox, PlayStation, and PC gaming.

- **[BoxCast](https://www.boxcast.com/)**  
  End-to-end live streaming platform for organizations. Plans range from **$99/month (Standard)** to **$449/month (4K Plan)** billed annually, with automated captioning and geo-blocking .

- **[Dacast](https://www.dacast.com/)**  
  White-label video streaming platform starting at **$39/month (Starter)** with 2.4 TB bandwidth, up to **$165/month (Scale)** with 24 TB bandwidth and priority support .

- **[Vimeo Livestream](https://vimeo.com/)**  
  Enterprise live streaming solution integrated with Vimeo's video platform; paid plans start at **$65/month** with custom enterprise options .

## Open-Source GitHub Projects

- **[OBS Studio](https://github.com/obsproject/obs-studio)**  
  **The industry-standard free and open-source software for live streaming and screen recording** — 76,000+ GitHub stars. Unlimited scenes, sources, audio mixer, plugins, and support for Windows, macOS, and Linux .

- **[Owncast](https://github.com/owncast/owncast)**  
  **Self-hosted, decentralized live streaming and chat server** — run your own streaming platform without YouTube or Twitch. Compatible with any RTMP broadcaster (OBS, Streamlabs, Restream). Single Go binary with React frontend, MIT licensed .

- **[MediaMTX](https://github.com/bluenviron/mediamtx)**  
  **Zero-dependency live media server and proxy** — single executable for publishing, reading, recording, and proxying streams via SRT, WebRTC, RTSP, RTMP, HLS, and MPEG-TS. Automatic protocol conversion, hot reloading, Prometheus metrics, and cross-platform support .

- **[PeerTube](https://github.com/Chocobozzz/PeerTube)**  
  ActivityPub-federated video streaming platform using P2P delivery directly in the browser — 15,000+ stars. Decentralized alternative to YouTube for live and on-demand content .

- **[Muxshed / Shed](https://github.com/muxshed/shed)**  
  **Self-hosted streaming studio and multistreaming solution** — one stream in, many destinations out simultaneously. No cloud middleman, no per-channel fees. Features scene management, browser sources, audio mixer, scheduled broadcasts, local recording, WebRTC guest links, Stream Deck integration, and a public watch page with HLS delivery .

- **[Prism](https://github.com/topics/restream)**  
  Self-hosted multistreaming solution (Dockerfile-based) for simultaneously redirecting RTMP streams to YouTube, Twitch, and custom RTMP servers .

- **[OpenStudio](https://github.com/msitarzewski/openstudio)**  
  **Browser-native multi-host podcast and live studio** — hybrid architecture with peer-to-peer media and centralized signaling. Features mix-minus audio routing, Icecast output, and zero commercial dependencies. Roadmap includes decentralized station discovery via DHT .

- **[Kap](https://github.com/wulkano/Kap)**  
  Open-source screen recorder built with web technology — 19,000+ stars. Clean, minimal interface for quick screen captures on macOS .

- **[Lembang-Opcast](https://github.com/JiilanTj/Lembang-Opcast)**  
  Open-source screen recording and live streaming application for Linux with X11 capture, PulseAudio, FFmpeg encoding, and RTMP streaming support .

### Additional Strong Open-Source Options

- **[Restream self-hosted alternatives](https://github.com/topics/restream)** — 53+ public repositories matching the "restream" topic, including Docker containers for RTMP relay, HLS restreaming proxies, and multi-platform pushers .
- **[Owncast P2P](https://github.com/cdnbye/owncast-p2p)** — Peer-assisted video delivery fork of Owncast using SwarmCloud for reduced bandwidth costs .
- **[bilistream](https://github.com/topics/restream)** — Self-hosted B站 (Bilibili) auto-relay tool monitoring Twitch/YouTube for automatic streaming .
- **[Chat.Overlay.Ninja](https://github.com/topics/restream)** — Send live chat to OBS or vMix as featured chat overlay .
- **[FFmpeg](https://github.com/FFmpeg/FFmpeg)** — The foundational multimedia framework powering most open-source streaming tools for encoding, transcoding, and muxing.

**Frameworks for building custom systems**: Combine **OBS Studio** for capture and encoding, **Owncast** for self-hosted distribution, **MediaMTX** for protocol routing and recording, and **Muxshed** for multistreaming to external platforms. For browser-based production, **OpenStudio** provides a zero-dependency WebRTC studio with Icecast output. For Linux-specific screen recording, **Lembang-Opcast** offers a lightweight GTK-based alternative .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Live streaming requires adequate upload bandwidth, hardware encoding capability, and proper RTMP endpoint configuration.
- Self-hosted streaming servers require network security (firewall rules, HTTPS), sufficient CPU/GPU for transcoding, and monitoring for stream health.
- Platform terms of service apply when restreaming to YouTube, Twitch, and other services — verify compliance for your use case.

---

**Made for content creators, broadcast engineers, event producers, and self-hosting enthusiasts.**  
Let's make live streaming more open, self-hosted, and vendor-neutral.
