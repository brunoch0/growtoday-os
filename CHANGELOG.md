# Changelog

All notable iterations of Growtoday OS dashboard.

Format inspired by [Keep a Changelog](https://keepachangelog.com/).

---

## [v1.2] · 2026-05-26 · Notion SNS Sync

### Added
- Sync with Notion Business Units DB for all 18 units' homepage + active SNS channels
- 5 additional SNS brand logos: Telegram, Facebook, Substack, Reddit, Snapchat
- Confirmed URLs for 16 units (homepage and/or YouTube)
- All channels from Notion `주요 채널` field rendered as clickable icons per unit

### Notes
- Specific handles for Instagram/LinkedIn/TikTok still `#` placeholders — Notion stores channel types but not URLs

---

## [v1.1] · 2026-05-26 · Personal Layer + Link Infrastructure

### Added
- **Personal section** inserted above Business in L0 — Option C "Stacked Pipeline" architecture
- 4 Personal cards: 운동 (Workout) · 공부 (Study) · Tool Lab · 습관 (Habits)
- Workout card with real data: 88kg → 83kg target / 1mo, running 3×/week 5-10km
- Other 3 cards as SAMPLE (Bruno fills via operation)
- Tool Lab card with 5 tools (Obsidian/ManyChat/VSCode/ElevenLabs/Blink AI) tracking graduation pipeline
- Pipeline visualization arrow: "Personal feeds Business · Tool Lab → 사업 graduate"
- **Per-unit SNS link row** in each business card header
- LINK_META + unitSocialsHTML() infrastructure for clickable social icons
- 6 new brand logos: LinkedIn, VSCode, Obsidian, TikTok, X (Twitter), Threads

### Fixed
- TDZ ReferenceError: moved `const PERSONAL` and `const LINKS` declarations to before render function calls

---

## [v1.0] · 2026-05-26 · MoraèVision Funnel Restructure

### Added
- L1 console restructured to match Bruno's CodePen reference design
- Row-based layout — single nodes vs paired nodes
- **Flow A · 오디언스 빌딩** expanded from 5 → 12 nodes (Instagram → Claude+Higgsfield → Canva+vidIQ → Reel+CTA → ManyChat 3-DM+Welcome DM → Notion K-beauty+Bridge → moraevision.com+이메일 DB)
- **Flow B · 브랜드 매칭** expanded from 5 → 7 nodes (k-ugc-match inquiry → vidIQ analysis + Top 5 matching → Gmail proposal + approval → UGC content + delivery)
- **Convergence point**: "두 채널 합류 · 거래 성사" between flows
- **DEAL CLOSED ribbon** — gold trophy + "K-브랜드 × Dubai 크리에이터" with live pulse
- 8 functional icons (heroicons solid): Bolt, Search, Check, Video, Package, Mail, Trophy, Globe — for non-brand workflow nodes
- Korean sub-descriptions per node make funnel readable for first-time viewers

---

## [v0.9] · 2026-05-26 · Zellys Premium Jewelry Tier

### Added
- **PREMIUM · 3 VARIANTS** section in Zellys card
- Sapphire / Silver / Gold faceted jewelry Zellys (from Bruno's FBX archive)
- Black-background removal + transparent PNG processing
- Hover glow effect per jewel color
- Confirms Zellys IP's 3-product structure: Color Characters / Brand Collabs / Premium Jewelry

---

## [v0.8] · 2026-05-26 · L0 Brand Logos

### Added
- Real brand logos in every L0 unit card's flow-rail (Instagram pink, Claude coral, Notion gray, Gmail red, YouTube red, Canva teal, Figma red)
- Mini SVG (16px) inside 28px chip, hover-scale on interaction
- ManyChat / vidIQ / Higgsfield / Lovable remain text fallbacks (not in Simple Icons)

---

## [v0.7] · 2026-05-26 · L1 Brand Logos

### Added
- Inline SVG brand logos in L1 MoraèVision nodes (replaced text codes)
- All logos fetched from Simple Icons GitHub source (no external CDN dependency)
- 7 brand logos extracted as path data and embedded inline

---

## [v0.6] · 2026-05-26 · L1 Tool Brand Colors

### Added
- TOOL_COLOR map — semantic brand color for each tool code
- L1 KPI accents per tool brand (events=Instagram-pink, followers=lime, DM=ManyChat-blue, inquiries=gold)
- Flow A (cyan/audience) vs Flow B (orange/B2B) visual differentiation

---

## [v0.5] · 2026-05-26 · MoraèVision L1 Drill-down

### Added
- L1 modal opens on click of cyan ribbon "⏵ CLICK · OPEN L1 CONSOLE"
- 4 live ticker KPIs (events, followers, DM, B2B inquiries)
- Flow A and Flow B with 5 nodes each (linear)
- Live event stream with timestamps
- Sky Zellys walking down each flow column
- ESC / backdrop click closes modal

### v0.5.1 - 5.3 fixes
- Cyan pulsing ribbon for L1 entry visibility
- Modal HTML positioning fixes for click handler

---

## [v0.4] · 2026-05-26 · Defense AI Animated Skin

### Added
- Custom 30-frame military saluting GIF for Defense AI unit (1.2s loop)
- Korean flag belly display
- Special skin overlay on Defense AI card

---

## [v0.3] · 2026-05-25 · 11-Color Zellys Sprites

### Added
- 11 color variants of Zellys (red/yellow/green/purple/lavender/magenta/orange/blue/sky/neon/mint)
- Per-unit color mapping — each business unit's Zellys walker uses its theme color
- Sky Zellys for MoraèVision, magenta for Zellys, orange for Bruno, etc.

---

## [v0.2] · 2026-05-25 · Cross-Card EDGES

### Added
- 14 ecosystem connections between units
- Cyan "highway" lines connecting related units (artpiad → yalee, morae → bruno, defense → cooperate, etc.)
- Walking Zellys can cross from one unit to another on the highway

---

## [v0.1] · 2026-05-25 · L0 Foundation

### Added
- 18-unit dashboard skeleton
- Header with status indicators
- 4 KPI tiles (Active Units, Today Events, Deals, AI Labor)
- 3-tier priority layout: High (2-col, 4 cards) / Medium (3-col, 9 cards) / Low (4-chip strip)
- Dark theme inspired by Bloomberg Terminal × Notion
- IBM Plex Sans/Mono typography

---

## Session Stats

- **Duration**: ~6 hours overnight (~22:00 → 04:00 Dubai, May 25-26, 2026)
- **Iterations**: 12 versions
- **Final size**: ~1.5 MB single-file HTML
- **Lines of code**: ~2,500
- **Assets embedded**: 20 PNG/GIF sprites (Zellys color/jewelry/military skins)
- **Brand logos integrated**: 18 (via Simple Icons)
- **Notion DB integrated**: 18 business units fully mapped
