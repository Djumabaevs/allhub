# AllHub — Portfolio Site

Build a stunning Apple-style single-page portfolio website showcasing all projects by Bakyt Dzhumabaev. 

## Requirements
- Single `index.html` file with embedded CSS and minimal JS (no frameworks, no build tools)
- Apple-inspired design: clean white/dark sections, large typography (SF Pro or Inter), smooth scroll animations, glassmorphism cards, subtle gradients
- Responsive (mobile-first)
- Sections: Hero, iOS Apps, Web Projects, Games, Blockchain, AI/ML, Bots, Infrastructure
- Each project card: name, icon/emoji, short description, tech stack badges, links, hosting info (frontend/backend)
- Smooth scroll-triggered fade-in animations (IntersectionObserver)
- Dark/light mode toggle
- Language: English (international portfolio)
- Command to run: just open index.html or use `python3 -m http.server 8080`

## Projects Data (USE EXACTLY THIS):

### 📱 iOS Apps (App Store)
All links format: https://apps.apple.com/app/idXXXXXXX

1. **Vectors Sketch** (id6758646967) — Vector drawing tool. Swift, UIKit
2. **FocusFlowDaily** (id6758512712) — Focus & productivity timer. Swift, SwiftUI
3. **SkyMapUSA** (id6758521674) — Sky map & star gazing. Swift, CoreLocation, ARKit
4. **Hydro Water** (id6758605857) — Water intake tracker. Swift, HealthKit
5. **Sallary Online Tracker** (id6758534537) — Income tracking app. Swift, CoreData
6. **Mind Glow Offline** (id6758568929) — Offline mindfulness & meditation. Swift, AVFoundation
7. **Archaman** (id6757703612) — AR experience app. Swift, ARKit, RealityKit
8. **Tamakpet** (id6758340935) — Virtual pet game. Swift, SpriteKit
9. **BreatheNowLife** (id6758463417) — Breathing exercises. Swift, HealthKit
10. **Sight Camera X** (id6758730624) — Camera with filters. Swift, AVFoundation, CoreImage
11. **Offline Menu Translator** (id6758393945) — Offline menu translation. Swift, Vision, CoreML
12. **CaloriesSnap** (id6759057387) — AI calorie counter from photos. Swift, CoreML, Vision
13. **Aura Lights** (id6758928631) — Ambient lighting control. Swift, HomeKit
14. **Environment Scan** (id6758941256) — Bluetooth/Wi-Fi device scanner. $3.99. Swift, CoreBluetooth, NetworkExtension
15. **Sense — Body Intelligence** (id6758951696) — 8 health sensor modules. $4.99. Swift, HealthKit, CoreMotion
16. **HapticTerrarium** (id6758998219) — Therapeutic haptic sandbox. $0.99. Swift, CoreHaptics, SpriteKit
17. **PoseScope** (id6759051036) — AI pose analysis. $4.99. Swift, Vision, CoreML
18. **ScreenSense** — Screen Time dashboard (in development). Swift, DeviceActivityReport, SwiftData, App Groups
19. **Dreams AI** — AI dream journal with local Qwen 3.5 0.8B model bundled on-device. Swift, CoreML, NLP. Runs completely offline, no cloud needed.

### 🌐 Web Projects

1. **Real Dashboard** — Palantir-style 3D geospatial command dashboard with interactive globe
   - URL: https://real-dashboard.vercel.app
   - Frontend: Vercel (Three.js + 3d-tiles-renderer + satellite.js + Vite)
   - Backend: Hetzner 65.109.4.13 (Express + WebSocket, reallife.relaxlisten.live)
   - APIs: Google 3D Map Tiles, CelesTrak (satellites), OpenSky (flights), Windy (webcams), USGS (earthquakes)
   - Tech: Three.js, DRACO, OrbitControls, post-processing (Bloom, NightVision, FLIR, CRT shaders)

2. **ProofSnap** — AI photo verification on blockchain. Take photo → AI analysis → SHA-256 → Merkle Tree → Polygon
   - URL: https://proof.relaxlisten.live
   - Frontend: iOS native app (Swift)
   - Backend: Hetzner 65.109.4.13 (Node.js, Fastify, SQLite, port 3002, proofsnap.service)
   - Blockchain: Polygon Mainnet (ethers.js, merkletreejs)
   - Contract: 0x669cA94...on Polygon

3. **КиноПоток (MovieStream)** — Movie & TV streaming aggregator
   - URL: https://relaxview.live
   - Frontend: Vercel (Next.js + React 19 + Tailwind CSS)
   - Backend: Serverless (Vercel)
   - APIs: TMDB, iframe video players
   - Samsung TV compatible (Tizen Chromium 38-69)

4. **AlgoApp** — Decentralized code challenge platform (LeetCode + Blockchain + AI Judge)
   - URL: https://algoapp-eta.vercel.app
   - Frontend: Vercel (Next.js)
   - Backend: Hetzner 65.109.4.13 (Node.js)
   - AI: Qwen + LoRA model for code evaluation
   - Blockchain: BNB Smart Chain (ALGO token + Soulbound NFTs)
   - Status: PAUSED

5. **Wateron** — Crypto token website (1 WTRN = 1 liter of water)
   - URL: https://wateron.vercel.app
   - Frontend: Vercel
   - Blockchain: BNB Smart Chain (ERC-20)

6. **iAppUsed** — Used Apple devices marketplace
   - Frontend: Next.js + Firebase
   - Backend: Firebase (Firestore)
   - Local path: ~/Downloads/iapp-used/

7. **Photo ID (Foto)** — Passport photo creator PWA
   - GitHub: https://github.com/Djumabaevs/foto
   - Tech: HTML5 + CSS3 + Vanilla JS, PWA, AI background removal, face detection
   - Presets: KR, USA, Schengen, etc.

8. **WorldCraft** — 3D habit tracker city builder
   - URL: https://djumabaevs.github.io/worldcraft/
   - GitHub: https://github.com/Djumabaevs/worldcraft
   - Tech: Three.js, OrbitControls, procedural buildings, PWA
   - Features: 9 categories, day/night cycle, achievements, infinite building growth

9. **GhostLine VPN** — Custom VPN solution
   - Tech: WireGuard + VLESS + Hysteria2
   - Server: Hetzner 65.109.4.13
   - Clients: macOS, iOS (QR code)

### 🎮 Games (Web, HTML5)

1. **BioLab: Containment Breach** — 3D FPS shooter
   - URL: https://djumabaevs.github.io/3dgame/
   - Tech: Three.js, WebGL, procedural textures, bloom post-processing
   - Features: 8 weapons, 3 levels, 5+ enemy types, boss fights

2. **Nova Strike** — Space shooter (waves, 3 weapons, bosses)
3. **Cyber Runner** — Run & gun platformer (Contra-style)
4. **Gravity Flip** — Puzzle platformer with gravity switching
5. **Shadow Quest** — RPG adventure
6. **Turbo Drift** — Racing game
7. **Mind Grid** — Candy Crush-style match game (Canvas)
8. **Empire Clash** — RTS strategy (fog of war, units, resources)
9. **Tactical Ops** — Tactical top-down shooter (waves, radar)

All games: HTML5 Canvas, single-file, mobile + desktop

### ⛓️ Blockchain

1. **Wateron (WTRN)** — ERC-20 token on BNB Smart Chain
   - Contract: 0x669cA94...
   - Tech: Solidity, Remix, MetaMask
   - Concept: 1 WTRN = 1 liter of water
   - Level: 🟢 Beginner

2. **Blockchain Voting** — Decentralized voting DApp
   - Tech: Solidity 0.8.24, Hardhat, Vite, React, MetaMask, OpenZeppelin
   - Networks: BNB Chain + Ethereum Sepolia
   - Level: 🟡 Intermediate

3. **VoteChain** — Custom L1 Blockchain (!)
   - Tech: Go, Cosmos SDK, CometBFT, Protobuf, CosmJS, Keplr
   - Frontend: https://votechain-gules.vercel.app/
   - Server: Hetzner 65.109.4.13 (votechaind.service)
   - Chain ID: votechain-1, denom: uvote
   - 3 custom modules: election, ballot, identity
   - RPC: rpc.relaxlisten.live, API: api.relaxlisten.live
   - Level: 🔴 Advanced — own blockchain from scratch!

### 🧠 AI / ML

1. **DSA LLM** — Custom model for algorithms
   - Variant A: Transformer from scratch (10M params, tiktoken)
   - Variant B: Qwen2.5-Coder-1.5B + LoRA fine-tune (4M trainable)
   - Tech: PyTorch, Transformers, PEFT, tiktoken

2. **Qwen 3.5** — Local AI model (0.8B multimodal, 262K context)
   - For DSA training pipeline

3. **Dreams AI** — AI dream journal iOS app with Qwen 3.5 0.8B bundled locally on-device
   - Tech: Swift, CoreML, converted Qwen model, runs fully offline

### 🤖 Bots

1. **Mia** — AI girlfriend Telegram bot with BNB subscription ($3/mo)
   - Server: Hetzner 65.109.4.13 (/root/mia_bot_v2.py)
   - Tech: Python, Telegram Bot API, BNB payments

2. **Anjela** — AI webdev Telegram bot that builds small websites
   - Server: Hetzner 65.109.4.13 (/root/webdevbot.py)
   - Auto-deploy commits to GitHub

### 🏗️ Infrastructure
- **Server:** Hetzner 65.109.4.13 (Ubuntu)
  - Services: VoteChain, ProofSnap, Real Dashboard, AlgoApp, Mia, Anjela, GhostLine VPN
  - Monitoring: Uptime Kuma (port 3001)
  - File Browser (port 8080)
  - Nginx reverse proxy + Let's Encrypt SSL
- **Domains:** relaxview.live, relaxplay.live, relaxlisten.live
- **Deploy:** Vercel (frontends), Hetzner (backends), GitHub Pages (games)

## Design Guidelines
- Hero: large title "Bakyt Dzhumabaev" + subtitle "Full-Stack Developer · iOS · Web · Blockchain · AI" with subtle gradient background
- Use CSS Grid for project cards
- Cards: glassmorphism (backdrop-filter: blur), rounded corners, subtle shadows
- Tech badges: small colored pills (like GitHub topics)
- Hosting badges: "Frontend: Vercel" "Backend: Hetzner" as colored tags
- Section headers: large bold text with subtle gradient underline
- Smooth scroll-triggered animations (fade up)
- Color scheme: white bg with indigo/purple accents (like Apple), dark mode with deep navy
- Footer with GitHub, LinkedIn, Telegram links
- Navigation: sticky top bar with section links

DO NOT use any external CDN or framework. Pure HTML + CSS + JS.
Create ONLY index.html in the current directory.
Make it BEAUTIFUL. Apple-quality design.
