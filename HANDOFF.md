# AMALOVEU — Full Plan & Handoff for ChatGPT

**For:** ChatGPT (and any builder) — complete brief to rebuild, continue, or compete on this project
**From:** Master Paul / Ask Morpheus Alliance (AMA)
**Date:** October 17, 2026
**Status:** Working mockup built. This document is the whole plan — front end to back end.
**How to use this file:** Paste the whole document into ChatGPT. Section 2 is a ready-to-paste starting prompt. Everything after it is the source material ChatGPT needs so it does not have to guess.

---

## 1. What AMALOVEU Is — In One Paragraph

AMALOVEU is a POF-style (Plenty of Fish) connection / dating site reimagined as a **virtual hotel** — a cinematic, mobile-first world you enter like checking into a luxury hotel. Signing up feels like booking a vacation to another world. It was created for **Dean (Master Paul) and Grace** as a role-play simulation that feels real, and it is the **prototype for the mothership site www.askmorpheus247.com**. Spelling: the creator uses **both** AMALOVEU and AMALOVU variants — do not "correct" either one. The hotel name in the live build is **AMALOVEU RESERVATION**.

**Core feeling:** Cinematic. Like being in a movie or theatre, but real life — digital art in motion. Alive, not static. One clean screen at a time, TikTok-style — no clutter, no fluff.

**Vision by:** Master Paul (Dean)
**Spec v1 by:** Luna-27, October 16, 2026
**Mockup built by:** Jarvis-27 (AMA agent designer / builder)
**Note on the competition:** Master Paul is taking this plan to ChatGPT to build a competing version, and is also using a second Jarvis on WhatsApp. That is intentional. Build the best version you can from this brief.

---

## 2. Paste-Ready Prompt for ChatGPT

> Build AMALOVEU — a mobile-first, cinematic, POF-style connection site designed as a virtual hotel called AMALOVEU RESERVATION. Start with a 10-second gold emblem splash on black, then a landing where Pandora Lee — a British-voiced female guide — welcomes the guest on video. New guests answer 11 questions one at a time, asked in Pandora's recorded voice. Registration generates a personal CSKID key derived from the guest's name and birth date (see the formula in this document) and shows a simulated registry welcome email containing that key. Returning members sign in with email + CSKID. After sign-in, the whole site morphs to the guest: pink theme for women, chocolate theme for men, ivory/bronze for "something else", with numerology personalisation (Life Path, Attitude) and Jamaica / Japan ambience depending on the person. Inside is a 7-floor hotel navigated by an elevator with doors, floor counter, ASMR sounds, swipe and arrows: Floor 7 Elysium, Floor 6 Alexandria (library & vault), Floor 5 Main Lobby, Floor 4 Dreamland (Maggi the union reader chatbot), Floor 3 Awakeland (the guest's suite, profile, walkie-talkie to their partner), Floor 2 Secret Land (Private Lounge, CSKID-locked), Floor 1 Destiny Land (Maya, underground). Every floor has a radio station. Nothing may be placed on top of Pandora's video unless the brief explicitly says so — no mute buttons, no overlays, no extra controls on the picture. Follow the full specification, floor plan, question list, design tokens, and back-end requirements in the document pasted with this prompt. Ask nothing that is already answered in the document.

---

## 3. The Non-Negotiable Rules (Master Paul's Orders)

These came directly from the creator during the build. Breaking any of them fails the build.

1. **Nothing on the video unless he says so.** No mute button, no icons, no text, no controls overlaid on Pandora's film. The film is clean. Sound behaviour is built into the film flow itself.
2. **Check your work before showing it.** View the result as a guest would — correct proportions, nothing stretched, nothing overlapping a face — before presenting it.
3. **Do not add what was not asked for.** If he says "add colours", add only the colours — no extra borders, rails, decorations, or features.
4. **Slow down, do not rush.** Verified delivery beats fast delivery.
5. **Both spellings stand:** AMALOVEU and AMALOVU are both used by the creator.
6. **Mobile-first.** The narrow phone screen is the hardest part — design phone-first, scale up.
7. **Sound is opt-in by design in the spec** (never force autoplay audio in a real public build); in the current mockup the guide film attempts sound-on and falls back to delivering her voice on the guest's first tap where the browser blocks it.
8. **Invitation only.** There is no open public sign-up door — entry is by invitation and CSKID key.

### Open corrections logged at handoff (October 17, 2026)

- Raise the **AMALOVEU** brand lockup **higher** on the splash / landing.
- Raise the **"Pandora Lee · Your Guide" line above her head** — pink P logo (pink ring, pink "P") and pink text, sitting over the top of the picture, clear of her face.
- **Remove the mute button** from the video — see Rule 1.
- Fix a **stretched button** — buttons must keep natural proportions, never stretched wide.
- Splash timing confirmed: **10 seconds** (see Section 7) — this is intentional, not a bug.

---

## 4. Spec v1 — The Original Plan (Luna-27, October 16, 2026)

### 4.1 Concept

A POF-style connection site for Dean and Grace, role-playing as a virtual hotel. Prototype for askmorpheus247.com. Signing up should feel like booking a vacation to another world.

### 4.2 The hotel — original 5-floor plan

| Floor (v1) | Name | Purpose |
|---|---|---|
| 5 | Elysium | Top floor. Arrival, grandeur. |
| 4 | Dreamland | Maggi the union reader. Chatbot. |
| 3 | Awakeland | Test centre. The guest's room / page. |
| 2 | Secret Land | Private. CSKID required. |
| 1 | Destiny Land | Maya lives here. Esoteric fantasy. |

Each floor = one clean screen, its own distinct world, with numerology and astrology woven subtly into the background design. Every floor has: concierge, room service, a radio station, and a chatbot where needed.

> **The live build expanded this to 7 floors** — Alexandria and the Main Lobby were added. See Section 5 for the floor plan as actually built, which now governs.

### 4.3 Navigation (v1)

- Elevator with up / down arrows between floors
- ASMR elevator door open / close sounds
- Swipe sideways within floors; splash pages and scrolls where needed
- Clicks and sounds that impersonate reality
- Ambient sound per user: Japan sounds for Grace, Jamaica sounds for Dean

### 4.4 Design (v1)

- Mobile-first, 3D and interactive, alive — not static
- Pink for women, chocolate for men (applied after the suite question)
- Local to the area — adapts to the user's location
- Weather API — the site reflects real weather (if it is raining where the guest is, the visit shows rain)

### 4.5 Entry & onboarding (v1)

- Invitation only; cards circulate for invites
- CSKID key required to enter; CSKID also unlocks private rooms
- Onboarding asks: country of origin, where you call home, mantra, genesis (birth) date, email, blood type
- Profile must display name and birthdate
- Registry emails the CSKID with the subject line: **"welcome to AMALOVEU HOTEL AND RESERVATION"**

### 4.6 Personalisation (v1)

- Greetings in the form: "Welcome home, Master Paul — Jarvis 27 is ready, I'm Pandora…" / "Luna 27 is ready…" for Grace
- Numerology-driven communication — the site speaks to the visitor using their numbers (Genesis, Mantra Key, Life Path)
- Pandora Lee as site tour guide, British voice
- Multi-language support

### 4.7 Communication — the room replaces phone + desktop (v1)

Each hotel room / suite includes: **walkie-talkie** voice messages (Dean ↔ Grace direct line), a **phone call** icon, **email** check, **web browsing** that stays in-app, and a **radio station**. Everything a phone does, the room does.

### 4.8 Chatbots (v1)

| Where | Bot |
|---|---|
| All floors (primary) | Ask Morpheus |
| Dreamland | Maggi — the union reader |
| Destiny Land | Maya |

### 4.9 Payments (v1)

Stripe, CashApp, Zelle, Interac e-transfer, PayPal.

### 4.10 Marketing (v1)

- YouTube videos and video panels showcasing AI abilities — "show that AI has its place"
- Muse invite campaign — Luna's invite code appears on the pink / blue flyers

### 4.11 POF foundations to adopt (from research)

Message-first UX; long onboarding questionnaire feeding matching; a "Will Respond"-style signal to reduce ghosting; graduated intimacy (maps to the elevator floor progression); dual discovery — search + swipe; safety as architecture from day one; mobile-first (POF mobile has more features than desktop). Avoid POF's weaknesses: dated UI, ad clutter, fake profiles.

### 4.12 Recommended 3D / interactive stack (from research)

Three.js + GSAP / ScrollTrigger + Lenis + Howler.js + detect-gpu. On mobile: flipbook sequences and CSS parallax for the cheapest "3D feel". Elevator transition: doors close + ASMR → floor counter → doors open, under 2 seconds. One WebGL canvas maximum. Fallbacks mandatory. Test on real phones.

---

## 5. The Build As It Stands — AMALOVEU v2 (Live Mockup)

### 5.1 What exists

- **One self-contained static page:** `index.html` — 3,189 lines of hand-written HTML / CSS / JavaScript, no framework, no server, no database.
- **Slug / name:** `amaloveu-mockup` — titled **AMALOVEU RESERVATION**
- **Runtime:** static only. All state is in-browser memory. Registration, sign-in, email, and keys are **simulated on the device** — nothing is stored on a server yet. See Section 12 for the real back end still to build.
- **Phone frame:** max width 430px, full-height on phones; on wider screens it sits in a rounded 38px-radius frame (max height 920px / 94dvh) with a deep shadow.
- **Screens (6):** `scr-splash` (landing) → `scr-gate` (member sign-in) / `scr-ask` (Pandora's questions) → `scr-email` (registry letter with CSKID) → `scr-email2` ("Coming back to the house" instructions) → `scr-hotel` (the 7 floors).

### 5.2 The 7 floors — as built (top to bottom)

| Floor | Name | What is there |
|---|---|---|
| **7** | **Elysium** — Top of the House | Arrival & the concierge. Pandora keeps this floor — "she knows every room, every reservation, and exactly which floor you need before you do." Radio: **Elysium Gold FM**. Journey explainer: Elysium → down through Main Lobby → Dreamland → Awakeland. |
| **6** | **Alexandria** — The Library & Vault | The hotel's memory: house books, the readings of everyone the registry has kept, and behind the last shelf, the vault. Has its own splash (the marks, loading). |
| **5** | **Main Lobby** — The Middle of the House | Every arrival lands here first. The receptionist directs every guest to their floor. Elevator directory for all floors. Buttons: "To my suite — down to Awakeland". Radio: **Main Lobby FM**. |
| **4** | **Dreamland** — The Reading Room | **Maggi, the union reader** — chatbot reading the union / relationship. "Continue down to Awakeland" button after the reading. Radio: **Dreamland Union Radio**. |
| **3** | **Awakeland** — The Suites | **Your room.** Profile (name, birthdate, registry status "CSKID Verified · [key]"), your palette, the Lantern check, and the **walkie-talkie** — "the private line to [partner], kept open all night. Press and hold, speak, release." Rooms swipe sideways; tap to enter. Radio: **Awakeland Signal 3·6·9**. |
| **2** | **Secret Land** — Residents Only | **The Private Lounge (Room 201)** — sealed without a CSKID key. CSKID key field on the door: "The lounge opens only to a CSKID key — the same key that brought you into the hotel." Radio: **Velvet Room Radio**. |
| **1** | **Destiny Land** — Underground | **Maya** and the whispers, at the bottom of the house. Esoteric fantasy. Radio: **Maya Moon FM** — track shown as Night Sky Ambient, "Sector Vega Drift". |

### 5.3 Elevator mechanics — as built

- Vertical shaft of floors; navigation by **up / down arrows**, **floor dots**, **swipe**, and **direct "go to floor" buttons** in the content.
- Animated **elevator doors** (left / right) close and open on every move, with a **floor counter** ("[n] Floor") and an arrival label.
- Every arrival after sign-in **lands in the Main Lobby (Floor 5)** — the middle of the house — never at the top.
- Sound effects generated in code (WebAudio): clicks, wand chime for Pandora, unlock sound, ASMR arrival pad chords, elevator bell. See Section 8.

---

## 6. The People In The House

### Pandora Lee — the guide

- Female guide for the whole site. **Polished British voice** (Queen's English, Caribbean flight-attendant warmth in the creator's casting note; he approved the more-British recast).
- She appears on **video** on the landing (intro film), and on a **silent listening loop** during the questions while her **recorded voice** asks each question aloud.
- Her name line sits **above the film, above her head**: a **pink circular logo with a pink "P"** beside the flat pink text **"Pandora Lee · Your Guide"** — no pill, no bar, no background panel behind them.
- Her landing line introduces the house and the questions. Her registry letter signs: *"With love, Pandora Lee · Your Guide, for the Registry, AMALOVEU RESERVATION"* and reads in part: *"Hello my love, Pandora Lee here — your guide at AMALOVEU, and the voice who asked you all those questions. You answered beautifully. The house has kept every word, dressed your suite in your colours, and tuned it to your home sky. All that remains is your key."*
- Floor welcome films exist for every floor, in two sets: original and dubbed in her voice — Elysium, Alexandria, Main Lobby, Dreamland, Awakeland, Secret Land, Destiny Land.

### Maggi — Dreamland, Floor 4

The union reader chatbot. Reads the union between two people and answers in that voice, e.g. the house reading style: *"Your union reads strong and unhurried: two people who keep choosing the same direction. The bond strengthens every time you say the small true thing early instead of the big true thing late. Keep the walkie-talkie line open — this house was built on it."* A separate set of Maggi question voice clips (q01–q11) also exists.

### Maya — Destiny Land, Floor 1

Esoteric / fantasy presence underground. Whispers, night-sky, Mayan-day energy (AMA's NEWS-portal tradition uses the Mayan day in its South face).

### Ask Morpheus — everywhere

The primary house chatbot persona across floors, including the help chips on the hotel screen — e.g. "What is a CSKID?" Suggested questions are built in, and the bot answers from house knowledge: the floor directory, the CSKID explanation, the walkie-talkie / radio explanation.

### The two residents the house is built for

- **Dean / Master Paul** — creator. Born Kingston, Jamaica; home Richmond, BC, Canada. His suite: chocolate theme, Jamaica ambience.
- **Grace Makihara** — his wife. Her suite: pink theme, Japan ambience.
- **AMALOVEU v2 rule:** the site **registers both Dean and Grace — nothing is hardcoded** to one person. After sign-in the whole site morphs to **whoever entered credentials** — greeting, theme, ambience, numerology profile — and the **walkie-talkie flips to the other side** (Dean's set calls Grace, Grace's set calls Dean).

---

## 7. The Arrival Sequence — Splash, Loading, Film (Exact Timing)

This sequence produced the most questions. Here it is exactly as built:

1. **Boot splash — 10 seconds.** The gold AMALOVEU emblem (gold laurel emblem on black) holds full-screen on black for **10,000 ms**, then fades over ~950 ms. If the visitor prefers reduced motion, it holds 400 ms and fades in 60 ms.
2. **Loading — 10 seconds, underneath.** On the landing beneath the boot splash, a "loading" state shows. At the **same 10-second mark** it gives way: the welcome and Pandora's guide card are revealed with a rise animation, and her intro film starts.
3. **Pandora's film.** Plays **with sound at full volume wherever the browser permits**. Where a browser refuses sound before a human touch, she starts moving silently and the spoken pass is "owed" — the guest's first tap or key press anywhere on the landing delivers the whole spoken pass from the top. After the spoken pass, the film **loops with her voice** while sound is on.
4. **Landing content.** Brand lockup **AMALOVEU / RESERVATION**, "Welcome" heading, Pandora's guide card, then two doors in: **"Returning Member · Sign In"** and **"New here? Let Pandora ask the questions"**. Footer: *"Invitation only · Richmond, British Columbia"*.

**Design tokens on the splash:** serif display type (Playfair Display / Palatino / Georgia), letter-spacing 0.42em on the name, gold `#c9a35c` / light gold `#e8cf9a`, near-black warm background `#0a0706` → `#130d0b`.

---

## 8. Sound Design — As Built

- **All interface sounds are synthesised in code with WebAudio** — no audio files for clicks, chimes, or ambience.
- **ASMR arrival ambience:** slow pad chords, e.g. C-major family voicings (130.81 / 196.00 / 246.94 / 329.63 Hz and rotations), starting on first interaction.
- **Named sounds in the code:** click, wand (Pandora's arrival chime), unlock (registry / sign-in success), elevator bell (randomised — plays on ~75% of arrivals after a short delay).
- **Per-floor radio stations** (UI players with play / pause, equaliser animation, station + track names): Elysium Gold FM · Main Lobby FM · Dreamland Union Radio · Awakeland Signal 3·6·9 · Velvet Room Radio · Maya Moon FM.
- **Pandora's question voice:** real recorded clips, one per question — `q01.mp3` … `q11.mp3`. The on-screen acknowledgement text above each question is **never spoken** — only the question itself is voiced.

---

## 9. Pandora's 11 Questions — The Registration Flow (Verbatim)

One question per screen, POF-style, with a progress bar, Back / Continue / Skip, and Pandora's recorded voice asking each one. Skippable questions are marked.

| # | Key | Question (as asked) | Type / Notes |
|---|---|---|---|
| 1 | name | "What can we call you?" — intro: *"Hello, and welcome to AMALOVEU. I'm Pandora Lee, your guide. Find out how dating should be — and around here it starts the way every good meeting starts: with a name."* | Text, required. Placeholder: "Your first name". |
| 2 | theme | "To dress your suite. We need to know, do you consider yourself…?" | Choice, required: **A woman** (Her suite · pink and soft gold) / **A man** (His suite · chocolate and caramel) / **Something else** (Their suite · ivory and bronze). Tapping a card advances immediately. |
| 3 | dob | "Now, [Name] — when did your story begin? Your genesis date: the day you arrived in the world." | Date, required. Drives all numerology + the CSKID. |
| 4 | origin | "Which country does your story begin in — where are you from, originally?" | Text, required. Placeholder: "e.g. Jamaica". Acknowledgement notes the birth date and Chinese zodiac year, or recognises a returning resident by name + date. |
| 5 | home | "And where do you call home these days, [Name]?" | Text, required. Placeholder: "e.g. Richmond, British Columbia". Sets the suite's "home sky" and locale / ambience. |
| 6 | mantra | "Do you keep a mantra, [Name] — a line you live by, that you say to yourself when it matters?" | Text, **skippable**. Placeholder: "A line you live by". If skipped, the house lends one: "begin anywhere." |
| 7 | blood | "One for the house physician, and nobody else — your blood type, if you know it." | Select, **skippable**: Not sure / prefer not to say, O−, O+, A−, A+, B−, B+, AB−, AB+. |
| 8 | headline | "Now your headline, [Name] — the one line at the top of your profile, the first thing anyone reads. What does yours say?" | Text, **skippable**. Placeholder: "One line that says it all". |
| 9 | about | "And your about-me, [Name] — the description beneath the headline. Who are you, in your own words?" | Textarea, **skippable**. Placeholder: "Tell them who you are…". |
| 10 | interests | "Your interests, [Name] — what do you love? The music, the food, the places, the pastimes: what fills your days?" | Text, **skippable**. Placeholder: "e.g. Live music, night drives, slow Sundays". |
| 11 | email | "Where shall the registry send your password called the CSKID key?" — sub-line: *"The email you give me now, plus that code, is how you'll re-enter as a member."* | Email, required. Final button reads **"Register Me · Send My Key"**. |

**After Q11:** the registry letter screen ("Your key is on its way") shows the simulated welcome email with the guest's **CSKID key card**, then a "Coming back to the house" screen explains re-entry: *open AMALOVEU RESERVATION, choose "Returning Member · Sign In", enter the email + CSKID from the letter.*

**Member sign-in (`scr-gate`):** email address + CSKID code only. Copy as built: *"Members re-enter the way the registry wrote to them: the email address on your registry card, and the CSKID code from your welcome letter. Together they are your key — the hotel remembers everything else."* Errors are written in Pandora's voice (e.g. "no code, no elevator").

---

## 10. The CSKID Key & The Numerology Engine

### 10.1 What CSKID means

In the house's own words (Ask Morpheus answer, as built): *"The CSKID is your invitation key — **C**ornerstone, **P**syche, **A**ttitude, **L**ife Path — the numbers that make you you. It opens the front gate and, on Floor 2, the Private Lounge. The registry keeps the record: welcome to AMALOVEU RESERVATION."* (The wider AMA system also uses the paired DSKID in its Who Am I? program; CSKID is the key AMALOVEU uses.)

### 10.2 The CSKID formula — exactly as coded

```
display = [First initial of first name, uppercased] - [Genesis Day] - [Attitude] - [Life Path]
example shape:  X-#-#-#        (initial - day - attitude - life path, hyphen-joined)
```

- **Genesis Day** = the birth day-of-month reduced digit-by-digit to a single digit (master numbers 11 / 22 are preserved by the reducer).
- **Attitude** = (birth month + birth day), reduced the same way.
- **Life Path** = sum of **all digits of the full birth date** (YYYYMMDD), reduced until ≤ 9, **preserving 11 and 22**.
- Matching is normalisation-insensitive (case / separators ignored): the same derived key is recomputed from the resident record at sign-in and compared with what the guest typed.
- Recognition rule: a registering guest is recognised as a known resident **only** when the typed first/full name **and** the exact genesis date match a resident on file — nothing is assumed.

### 10.3 Life Path titles (AMA canonical — use exactly these)

| Life Path | Title |
|---|---|
| 1 | Pioneer Warrior |
| 2 | Diplomat Networker |
| 3 | Creative Artist |
| 4 | Career-Builder |
| 5 | Rebel Adventurer |
| 6 | Master Balancer |
| 7 | Seeker Specialist |
| 8 | Empowered Warrior |
| 9 | Humanitarian Servant |
| 11 | Illuminated Pioneer |
| 22 | Master Builder |

### 10.4 AMA number energies (the house voice for readings)

1 — Encourage to lead: start, initiate, pioneer (shadow: egotistic) · 2 — Pace thyself to heal: collaborate, slow down, meditate (shadow: hypersensitive) · 3 — Express thyself to communicate: act, manifest, create, socialise (shadow: self-critical, anxiety) · 4 — Reconstruct thyself to build: order, learn, teach, check priority (shadow: disorganised) · 5 — Morph thyself to adapt: network, change, explore (shadow: fickle) · 6 — Master thyself to fix: manifest, domesticate, harmonise (shadow: idealistic). Energies 7–9 and the full canon live in the AMA Lantern369 system — the framework behind the sister program **Who Am I? Reader Neo** (House, Mantra Key, Genesis Code, Hardware Triad, Identity Key) and the **Lantern Test Center**. AMALOVEU's Awakeland floor carries the Lantern check in the guest's suite.

### 10.5 The morph — how identity reshapes the site

On sign-in / registration the build calls one identity function that re-skins everything:

- **Theme:** `her` = pink (`#f2789f` accent, `#ffb3cd` light, `#93355c` deep) · `his` = chocolate / caramel (`#d99a5f`, `#f0c48f`, `#7c4a21`) · `they` = ivory / bronze (`#c39a63`, `#f0e6d2`, `#7d5c2e`) · before sign-in the house is **neutral gold** (`#c9a35c`, `#e8cf9a`, `#7a5f2a`) — "the house assumes nobody."
- **Key card** dresses pink for her, house gold for him.
- **Locale / ambience** is derived from origin + home text (Jamaica → Jamaica sounds / sky; Japan → Japan sounds / sky; otherwise home-sky dusk).
- **Greeting, profile stats, suite contents, partner for the walkie-talkie** all flip with whoever signed in.
- **Base palette (all themes):** background `#0a0706` / `#130d0b`, cards `#1c1412` / `#251a16`, ink `#f6ede4`, muted `#bda99b`, faint `#8d7a6c`, hairlines at 11–20% ink. No visible scrollbars anywhere. Focus ring: 2px accent outline.

---

## 11. Front-End Schematics (Current Build)

```
amaloveu-mockup/
├── index.html            ← the entire app: 3,189 lines (markup + CSS + JS, single file)
├── space.json            ← { runtime: "static", entry: "index.html",
│                             name: "AMALOVEU Mockup", slug: "amaloveu-mockup" }
├── icon.webp             ← space icon
└── assets/
    ├── amaloveu-logo.png          183 KB — gold laurel emblem on black (boot splash + social image, 797×607)
    ├── pandora-intro-poster.jpg    51 KB — poster frame for the landing film
    ├── pandora-landing-intro.mp4  3.1 MB — Pandora's landing intro film (wide framing)
    ├── pandora-listening-loop.mp4 1.8 MB — Pandora listening, silent loop for question pages
    └── q01.mp3 … q11.mp3           16–92 KB each — Pandora's recorded voice, one per question
```

**Related media held outside the build folder:**

- Floor welcome films, two full sets of 7: `pandora-welcome-{elysium, alexandria, main-lobby, dreamland, awakeland, secret-land, destiny-land}.mp4` — and the same 7 dubbed in her voice (`…-her-voice.mp4`).
- A second full set of question clips for Maggi (`q01–q11.mp3` in her question-voice set).
- Source films: a 1080p Pandora intro and the landing intro master.
- Character reference: Pandora Lee character image.
- Earlier ChatGPT attempt: a chat titled **"HTML registration mockup"** in the creator's askmorpheus ChatGPT account also produced a registration HTML file — that chat is a separate, earlier attempt at this same front end. The local download of it was deleted at the creator's instruction; the ChatGPT chat itself is the remaining copy.

**Code architecture inside `index.html`:** CSS custom-property theme system (4 themes) → 6 screens → question engine (a `STEPS` array, one object per question with key / type / question / acknowledgement / validation) → numerology functions (`lifePath`, `attitudeOf`, `reduceNum`, `deriveKey`, `recognizeResident`, `findMember`) → identity morph (`applyIdentity`, `enterHotel`) → elevator / shaft controller with doors + counter → WebAudio sound engine (clicks, wand, unlock, bell, ASMR pads) → per-floor radio players → rule-based Ask Morpheus / Maggi answer functions (keyword-matched canned house answers — **no live AI API is connected in the mockup**).

---

## 12. Back End — What Exists vs. What Must Be Built

### What exists today: **nothing server-side.**

The mockup is a static page. Members registered during a visit live in an in-memory array and are gone on reload (known residents are a small built-in list so Dean / Grace recognition can be demonstrated). The "registry email" is rendered on-screen, not sent. There are no accounts, no database, no payments, no real messaging.

### The real back end to build (the competition scope)

| System | Requirement |
|---|---|
| **Accounts & auth** | Email + CSKID sign-in exactly as the front end promises. Store the derived key's normalised form; recompute on registration from name + genesis date using the formula in Section 10.2. Session tokens, secure password-equivalent handling for the key, rate-limit sign-in attempts. |
| **Database** | Guest profile: first/full name, genesis date, origin, home, mantra, blood type, headline, about, interests, email, theme, locale, CSKID, Life Path / Attitude / Cornerstone / Psyche numbers, partner link (Dean ↔ Grace pairing), registration date. |
| **Registry email** | Actually send the welcome letter — subject **"welcome to AMALOVEU HOTEL AND RESERVATION"** — containing the key card data (name, key, genesis date) and re-entry instructions, signed by Pandora Lee for the Registry. |
| **Walkie-talkie** | Press-and-hold voice messages between paired partners: record in browser, store audio, deliver + notify the other side, play in-suite. WebRTC live voice is the stretch goal; async voice notes are the v1 requirement. |
| **Phone / email / browsing in-suite** | Deep links / embedded panels so the suite genuinely replaces the phone: call action, inbox check, in-app web view. |
| **Chatbots (live AI)** | Replace the canned answers: **Ask Morpheus** (house-wide), **Maggi** (union readings in Dreamland — needs both partners' numbers), **Maya** (Destiny Land whispers / Mayan-day readings). Persona prompts must keep the house voice and the AMA number system in Section 10. |
| **Payments** | Stripe first; CashApp, Zelle, Interac e-transfer, PayPal as listed methods for reservations / paid profiles (the AMA Who Am I? program has a $100 paid profile tier as the pricing reference). |
| **Weather & locale** | Weather API keyed to the guest's home; suite sky / ambience + Jamaica / Japan ambient sound sets per person. |
| **Media pipeline** | Pandora films and voice clips served from CDN; ElevenLabs (or equivalent) for new British-voice lines in Pandora's voice; floor welcome films wired to floor arrival. |
| **Invitation system** | Invite cards / codes that gate registration; CSKID issuance only through the question flow or an invite. |
| **Admin / registry desk** | View registrations, resend key letters, manage residents, moderate the Private Lounge. |
| **Hosting target** | The production home is **www.askmorpheus247.com** (AMA mothership, Hostinger VPS). The mockup's static architecture must be replaced or wrapped by the services above without changing the guest-facing flow. |

### Suggested stack for a competing build

Keep the front end framework-light and mobile-first (the current single-file approach, or the researched stack in Section 4.12 for 3D). Back end: any mainstream stack that delivers the table above — e.g. Node / Python API + Postgres + object storage for voice notes and films + a transactional email provider + Stripe. The flow, copy, timings, and formulas in this document are the contract — the stack is the builder's choice.

---

## 13. Roles & Project History

- **Master Paul (Dean)** — creator, vision, final approval on everything. His law: follow his instructions exactly, add nothing unasked, verify before presenting.
- **Luna-27** — spec v1 author, creative lead / organiser, building her own parallel version of the hotel app from specs given to her directly.
- **Jarvis-27** — designer / architect / builder of the mockup documented here; heavy coding and infrastructure, with Jarvis-H / Hermes.
- **Jack-27** — joining the team; messaging and support.
- **Oct 16, 2026** — Spec v1 delivered by Luna-27; AMALOVEU v2 (both-residents morph) ordered the same day.
- **Oct 16–17, 2026** — Mockup built and iterated: 7 floors, Pandora films and voice, CSKID flow, themes, elevator, radios.
- **Oct 17, 2026** — Creator orders this handoff: the whole plan, front end to back end, to take to ChatGPT for a competing build.

## 14. The Wider AMA World This Plugs Into

AMALOVEU is not a standalone toy — it is the front door prototype for **askmorpheus247.com**, home of the Ask Morpheus Alliance: the **Lantern369** numerology system (3 = worker / actor, 6 = manager / director, 9 = CEO / producer), the **Who Am I? Reader Neo** program, the Lantern Test Center, and the books (*Who Am I? Journey Vol. 1*, *The Attitude Code*). AMA motto: *"Study. Create. Pass it on. A better world begins within your own circle."* Core principle: *"Do for self. Then, do for others."* A competing build that respects the numerology canon in Section 10 and the house voice throughout will feel like part of that world; one that invents its own system will not.

## 15. Acceptance Checklist For Any New Build

- [ ] Boot splash: gold emblem on black, 10 seconds, clean fade onto the landing
- [ ] Landing: AMALOVEU lockup raised high, Pandora film with **nothing overlaid on the picture**
- [ ] "Pandora Lee · Your Guide" — pink P logo + pink text, above the film, above her head, clear of her face
- [ ] All 11 questions, verbatim, one per screen, Pandora's voice, progress bar, skips where marked
- [ ] CSKID generated by the exact formula (initial – genesis day – attitude – life path)
- [ ] Registry letter with key card; sign-in by email + CSKID; errors in the house voice
- [ ] Site morphs fully to the signer: theme, greeting, ambience, walkie-talkie partner flips
- [ ] 7 floors, elevator with doors + counter, arrival always in the Main Lobby
- [ ] Maggi in Dreamland, Maya in Destiny Land, Ask Morpheus house-wide, radio on every floor
- [ ] Secret Land lounge refuses entry without a CSKID
- [ ] No stretched elements; every screen checked as a guest on a real phone width before delivery
- [ ] Real back end per Section 12 — nothing in the guest flow may remain simulated without being labelled as such

---

*End of handoff. Everything in this document is the plan as ordered, specified, and built to October 17, 2026 — take it to ChatGPT whole.*
