# BlurLocal

**[Try it →](https://NakliTechie.github.io/blurlocal)**

Blur faces in photos and videos locally in your browser. No upload. No server. No account.

Powered by [MediaPipe Face Detection](https://ai.google.dev/edge/mediapipe/solutions/vision/face_detector) — the model runs entirely in WebAssembly on your device.

## Features

- **Face detection** — drop any photo or video, faces are detected instantly
- **Gaussian blur** — smooth, natural face obscuring
- **Pixelate mode** — mosaic-style face hiding
- **Adjustable intensity** — slider from subtle to completely unrecognizable
- **Selective blur** — click any face to toggle blur on/off individually
- **Video support** — frame-by-frame face detection and blur, export as WebM
- **Privacy-first** — images and videos never leave your device

## Usage

Open `index.html` directly in Chrome or Edge. No build step, no install, no server.

First load downloads ~5 MB of face detection model weights — cached by the browser after that, works offline.

## How it works

1. Drop a photo or video
2. Click **Detect & Blur** — all faces are blurred by default
3. Click any face box to toggle blur on/off
4. Switch between Gaussian and Pixelate, adjust intensity
5. Download the result

## Part of the NakliTechie series

| Tool | What it does |
|------|--------------|
| [**BabelLocal**](https://github.com/NakliTechie/BabelLocal) | Offline translation — 200 languages, NLLB model |
| [**StripLocal**](https://github.com/NakliTechie/StripLocal) | EXIF metadata stripper — nothing leaves the browser |
| [**GambitLocal**](https://github.com/NakliTechie/GambitLocal) | Chess vs Stockfish — correspondence mode via URL |
| [**VoiceVault**](https://github.com/NakliTechie/VoiceVault) | Audio transcription — Whisper, offline-first |
| [**KingMe**](https://github.com/NakliTechie/KingMe) | English draughts — custom minimax AI, zero deps |
| [**SnipLocal**](https://github.com/NakliTechie/SnipLocal) | Background remover — RMBG-1.4, passport mode |
| **BlurLocal** | Face blur — MediaPipe detection, gaussian & pixelate |
| [**LocalMind**](https://github.com/NakliTechie/LocalMind) | Private AI chatbot — Gemma via WebGPU |
| [**PredictionMarket**](https://github.com/NakliTechie/PredictionMarket) | Prediction market simulator — Parimutuel & LMSR |

---

**Built by [Chirag Patnaik](https://github.com/NakliTechie)**

## License

MIT
