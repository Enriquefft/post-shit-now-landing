# Lovable Prompt — Post Shit Now Landing Page

Paste this entire block into Lovable:

---

Build a modern, dark-themed landing page for "Post Shit Now" — a CLI-first social media growth system for developers and teams. The aesthetic is terminal/hacker meets clean SaaS. Think Linear or Raycast's landing pages but with a raw, developer-first edge.

## Design System

- **Background:** Near-black (#0A0A0B) with subtle noise/grain texture
- **Primary accent:** Electric green (#00FF88) — used sparingly for CTAs, highlights, terminal cursors
- **Secondary accent:** Soft purple (#A78BFA) for secondary elements
- **Text:** White (#F5F5F5) for headings, muted gray (#9CA3AF) for body
- **Font:** Inter or Geist for body, JetBrains Mono or Fira Code for code/terminal elements
- **Cards:** Dark gray (#141417) with subtle border (#1F1F23), slight glow on hover
- **Terminal blocks:** Styled like real terminal windows with title bar dots (red/yellow/green), dark background (#0D0D0F), green monospace text
- **Spacing:** Generous — let the content breathe. Each section should feel like its own "screen"
- **Animations:** Subtle fade-in-up on scroll for each section. Terminal typing animation for the hero command.

## Sections (in order)

### 1. Navigation Bar
- Logo: "PSN" in monospace bold + full name "Post Shit Now" next to it in regular weight
- Nav links: Features, How It Works, Pricing, Platforms
- CTA button: "Get Started" → links to #get-started section
- Sticky on scroll, with backdrop blur

### 2. Hero Section
- **Badge/pill** above headline: "CLI-First Social Media" in a small rounded pill with green border
- **Headline:** "Stop Overthinking. Start Posting."
- **Subheadline:** "A terminal-first social media system that learns your voice, generates content that sounds like you, and posts across X, LinkedIn, Instagram, and TikTok. No web app. No dashboard. Just commands."
- **Terminal mockup** below the text showing:
```
$ /psn:post

  ✦ Voice: Personal (English)
  ✦ Platform: X + LinkedIn
  ✦ Topic: "Why most developer tools fail at onboarding"

  Generating draft...

  ━━━━━━━━━━━━━━━━━━━━ 100%

  📝 Draft ready for review
  ┌──────────────────────────────────────────┐
  │ Most dev tools nail the demo but fumble  │
  │ the "okay now what?" moment.             │
  │                                          │
  │ The gap between first impression and     │
  │ daily habit is where 90% of tools die.   │
  │                                          │
  │ Three things that actually work:         │
  │ → Progressive disclosure (not a wall     │
  │   of settings)                           │
  │ → Real task on day 1 (not a tutorial)    │
  │ → Celebrate the first win (not upsell)   │
  └──────────────────────────────────────────┘

  ▸ Post now  ▸ Schedule  ▸ Edit  ▸ Regenerate
```
- **Two CTAs below terminal:** "Clone the Repo →" (primary green button) and "Watch Demo" (ghost/outline button)
- **Social proof line** below CTAs: "Works with X, LinkedIn, Instagram & TikTok" with small platform icons

### 3. Problem Section
- **Section label:** "THE PROBLEM" in small caps, green
- **Headline:** "You Know You Should Post. You Just... Don't."
- **Three problem cards** in a row:
  - Card 1: Icon (clock). Title: "The Blank Page Problem". Body: "You open Twitter. Stare at the compose box. Close it. Repeat tomorrow. Sound familiar?"
  - Card 2: Icon (dollar). Title: "SaaS Tool Fatigue". Body: "Buffer, Hootsuite, Sprout Social — $50-300/month for features you use 10% of. And your posts still sound like a marketing bot."
  - Card 3: Icon (robot). Title: "AI Slop". Body: "Generic AI content gets suppressed by algorithms and ignored by humans. Platforms are actively detecting and downranking it."

### 4. Solution / Value Prop Section
- **Section label:** "THE SOLUTION" in small caps, green
- **Headline:** "Your Terminal Is Your Social Media Command Center"
- **Subheadline:** "PSN is a git repo you clone. It becomes your social media workspace — voice profiles, content drafts, analytics, strategy config. All version-controlled. All yours."
- **Three value prop cards:**
  - Card 1: Icon (terminal). Title: "One Command to Post". Body: "Type /psn:post. Get a voice-matched draft in seconds. Review, edit, schedule. Done. No context-switching."
  - Card 2: Icon (brain). Title: "It Learns Your Voice". Body: "A voice interview captures how you actually talk. Every edit you make teaches the system. Posts get better over time — not generic, yours."
  - Card 3: Icon (key). Title: "Bring Your Own Keys". Body: "Your API keys, your data, your costs. No middleman billing. No vendor lock-in. Cancel nothing — it's a git repo."

### 5. Features Grid Section
- **Section label:** "FEATURES" in small caps, green
- **Headline:** "Everything You Need. Nothing You Don't."
- **6 feature cards** in a 3x2 grid:
  1. **Voice Profiles** — "Three personas: Personal, Brand Operator, Brand Ambassador. Each with its own voice DNA. Switch between them per post."
  2. **Smart Scheduling** — "Trigger.dev handles the automation. Schedule posts, collect analytics, refresh tokens — all running in the cloud while you sleep."
  3. **Content Intelligence** — "Trend monitoring from Hacker News, Reddit, Product Hunt, RSS feeds. The system surfaces what's relevant to your content pillars."
  4. **Idea Bank** — "Capture ideas instantly with /psn:capture. They mature through a pipeline: spark → seed → ready → developed. Never lose an idea again."
  5. **Weekly Planning** — "/psn:plan generates your content calendar. Series-first slotting, pillar balancing, content recycling. Review once, post all week."
  6. **Learning Loop** — "Analytics feed a preference model that gets smarter weekly. It learns which hooks, formats, and topics work for YOUR audience."

### 6. How It Works Section
- **Section label:** "HOW IT WORKS" in small caps, green
- **Headline:** "Three Steps. Five Minutes."
- **Three steps in a horizontal flow with connecting lines/arrows:**
  - Step 1: Number "01" large. Title: "Clone & Setup". Terminal showing: `git clone psn && /psn:setup`. Body: "Clone the repo. Run setup. Connect your API keys and platforms. One-time, 5 minutes."
  - Step 2: Number "02" large. Title: "Find Your Voice". Terminal showing: `/psn:voice interview`. Body: "A conversational interview captures your authentic voice. How you talk, your opinions, your style — in English, Spanish, or both."
  - Step 3: Number "03" large. Title: "Start Posting". Terminal showing: `/psn:post`. Body: "Generate voice-matched content. Review. Schedule or post instantly. The system handles the rest."

### 7. Platform Support Section
- **Section label:** "PLATFORMS" in small caps, green
- **Headline:** "Four Platforms. Real API Costs."
- **Subheadline:** "No hidden fees. You pay the platforms directly, at their actual API rates."
- **Four platform cards** side by side:
  - **X (Twitter):** "$0.01/post, $0.005/read. ~$2-5/month for active posting. The old $200/month barrier is gone."
  - **LinkedIn:** "Free API. Partner approval required (takes weeks). Tokens refresh every 60 days — PSN handles it automatically."
  - **Instagram:** "Free API. Business/Creator account required. 200 req/hr rate limit — PSN batches intelligently."
  - **TikTok:** "Free API. Audit required for public posting. PSN handles the submission process."
- Each card has the platform's logo/icon and a status badge: X = "Ready", LinkedIn = "Ready", Instagram = "Coming Soon", TikTok = "Coming Soon"

### 8. For Teams Section
- **Section label:** "FOR TEAMS" in small caps, purple accent
- **Headline:** "Personal Brands + Company Brands. Separated by Design."
- **Two-column layout:**
  - Left column: "Personal Hub" card — "Your analytics, your ideas, your voice — always yours. Leaving a company? Delete one file. Your history stays."
  - Right column: "Company Hub" card — "Shared content calendar, approval workflows, team idea bank, brand voice consistency. Admin creates once, team connects via invite code."
- **Bottom note:** "Employee advocacy gets 561% more reach than company posts alone. PSN makes both effortless."

### 9. Bilingual Section (smaller, not a full section)
- **A banner/callout block:**
- "🌐 Bilingual by Default" — "English + Spanish. Not translations — independently crafted content in each language. Voice profiles have language-specific sections. Because your Spanish voice isn't a translation of your English one."

### 10. CTA / Get Started Section (id="get-started")
- **Headline:** "Ready to Actually Post?"
- **Terminal mockup:**
```
$ git clone https://github.com/your-org/post-shit-now
$ cd post-shit-now
$ /psn:setup
```
- **Primary CTA:** "Star on GitHub ★" (large green button)
- **Secondary CTA:** "Read the Docs" (ghost button)
- **Small text below:** "Free and open source. No account needed. No credit card. Just clone and go."

### 11. Footer
- Left: "Post Shit Now" + "Built with Claude Code, Trigger.dev & too much caffeine"
- Right: Links — GitHub, Documentation, License (MIT)
- Very minimal, dark

## Uploaded Image Assets
I'm uploading these pre-generated images. Use them directly instead of creating placeholders:

1. **OG Image** — Use as the og:image meta tag. Do not display on the page itself.
2. **Hero Background** — Use as a subtle background image/overlay behind the hero section. Apply low opacity so text remains readable.
3. **Terminal Mockup** — Use this as the hero terminal visual. If the image looks better than a CSS terminal, use the image. If a CSS terminal with typing animation looks better, use CSS and keep this as a fallback.

For all other visuals (feature icons, platform logos, decorative elements), use Lucide icons and CSS styling — do NOT use placeholder images.

## Important Notes
- The page should feel fast, confident, and slightly rebellious — this is NOT a corporate SaaS product
- No stock photos. No generic illustrations. Terminal mockups and code are the visual language.
- Mobile responsive — the terminal mockups should stack vertically on mobile
- Add smooth scroll between sections
- OG meta tags: title "Post Shit Now — CLI-First Social Media", description "Stop overthinking. Start posting. A terminal-first system that learns your voice and posts across X, LinkedIn, Instagram & TikTok." Use the uploaded OG image.
