# Unifeed

**UniFi Protect → YouTube Live Streaming**

Stream your UniFi Protect cameras to YouTube Live using webcam.io, Docker + FFmpeg, or other methods.

### [View the Deployment Guide →](https://kjcornwell.github.io/Unifeed/)

## Quick Start (Docker)

```bash
git clone https://github.com/kjcornwell/Unifeed.git && cd Unifeed
cp .env.example .env    # fill in your RTSP creds + YouTube stream key
docker compose up -d
```

## What's Covered

- **webcam.io** — cloud relay service (no local software)
- **Docker + FFmpeg** — self-hosted, auto-restart, multi-camera
- **FFmpeg direct** — quick command-line streaming
- **OBS Studio** — GUI-based streaming
- **MediaMTX** — RTSP relay/proxy for advanced setups
- **Windows Service (NSSM)** — persistent background service
