# CLAUDE.md — purposetask

## Purpose

This repo contains Andrew Springman's unsolicited website feedback for [PurposeTask](https://purposetask.org), a North Carolina nonprofit connecting motivated workers (Taskers), nonprofits (Architects), and mission-driven donors (Sustainers) to verified community outcomes.

The repo was created in response to a LinkedIn message from Garrett Astler (PurposeTask founder) and contains:

- `index.html` — a revised landing page mockup showing suggested improvements
- `reply.md` — draft LinkedIn reply to Garrett
- `reply.pdf` — formatted PDF version of the reply
- `images/` — screen captures from the PurposeTask teaser video
- `context/` — Garrett's original message and the Otter transcripts behind the feedback

The live GitHub Pages URL: **https://andrewspringman.github.io/purposetask/**

## Context

### Who is Garrett Astler?
Founder of PurposeTask. Connected with Andrew on LinkedIn at the Charlotte Startup House Jam. Offered introductions to Ken Norton and Andrew Weiler (Innovation & Technology Lead at ForCLT — Ken is now ED there, making timing interesting). Mentioned MeckMIN (Mecklenburg Metropolitan Interfaith Network) and a FaithTech Matthews meetup. Andrew had already reached out to Ken and Andrew Weiler on LinkedIn before replying.

### What is PurposeTask?
A civic infrastructure nonprofit with three user types:
- **Taskers** — motivated workers who complete skills-based tasks and get paid same-day (character: Marcus)
- **Architects** — nonprofits who scope and post community work (character: Becca)
- **Sustainers** — mission-driven donors who fund tasks and receive verified proof of impact (character: Robert)

501(c)(3) status pending. Based in North Carolina. Video: https://youtu.be/T7HTqmNeLks

### Original site issues Andrew identified
1. Text doesn't have the same vibe as the video — video tells a story, frames with opportunity, pictures the platform; text leads with function
2. Hero tagline ("Where capacity finds purpose, and purpose finds momentum") is abstract
3. Personas in the video are unnamed — Marcus has a name but the nonprofit coordinator and donor don't
4. Video is embedded in a way that blocks clicking the YouTube icon (can't get to transcript easily)
5. Andrew's generation scans text before deciding to watch a video — the transcript should be reachable
6. No visual connection between the video and the text (no screen captures, no shared phrases)
7. The word "displaced" has a negative connotation — "motivated" is more accurate and empowering

### What the revised mockup changes

**Content:**
- Hero headline replaced with shorter tagline: *"The people, the need, and the funding — together."*
- Sub-headline uses "motivated workers" instead of "displaced workers"
- Personas named and given circular portrait photos from the video
- Product screenshots alongside each persona (Task Map app, task board, donor report iPad)
- Stat bar: "Task completed. Worker paid. Dollars accounted for."
- Proof flow: Task defined → Worker matched → Work completed → Worker paid → Donor sees proof
- Form copy: Garrett's exact original text restored ("If this belongs in your world, reach out...")
- Footer: Garrett's exact original legal text restored verbatim

**Design:**
- Color scheme matches purposetask.org: warm cream/linen bg (`#f0ebe1`), gold accent (`#b8942a`), dark charcoal buttons/footer (`#1f1c14`)
- Sticky nav with hamburger menu (links: See how it works, Get in touch)
- Video embedded via standard YouTube iframe (YouTube logo stays clickable → transcript accessible)
- No nav CTA button — the hero and hamburger menu handle it
- All revision annotation notes removed — mockup presented clean

**Persona layout (name above role):**
- Portrait circle → Name (bold) → Role label → Pull quote → Body copy → Tag

### reply.md — what Andrew's reply covers
1. **Website feedback** — video is better in multiple ways; suggest phrases + screen caps to connect them; shorter tagline; "motivated" not "displaced"; link to the mockup
2. **Video feedback** — YouTube icon should be clickable for transcript; name the other two characters
3. **Introductions** — already reached out to Ken and Andrew Weiler; knows Ken well, only met Andrew once; Drew Burdick may know Andrew better; Ken knows him best
4. **MeckMIN** — hasn't connected with them; curious to hear Garrett's impressions
5. **FaithTech** — must have missed the Matthews meetup; tries to go every month
6. **Getting together** — evenings and weekends, or lunch at 11:30 at the Billy Graham Library; evenings open this week
- Closes: "Blessings, Andrew"

## File Map

```
purposetask/
├── CLAUDE.md                       # This file
├── index.html                      # Revised landing page mockup (GitHub Pages)
├── reply.md                        # LinkedIn reply draft (plain text)
├── reply.pdf                       # LinkedIn reply (formatted PDF)
├── images/
│   ├── marcus.png                  # Marcus portrait (Tasker)
│   ├── marcus-app.png              # Task Map app screenshot
│   ├── becca.png                   # Becca portrait (Architect)
│   ├── becca-taskboard.png         # Task board dashboard screenshot
│   ├── robert.png                  # Robert portrait (Sustainer)
│   └── robert-report.png           # Electronic donor report (iPad screenshot)
└── context/
    ├── garrett-message.md          # Garrett's original LinkedIn message verbatim
    ├── otter-transcript.md         # Otter transcript 1: Andrew's initial reaction to the site/video
    └── otter-transcript-2.md       # Otter transcript 2: Andrew's feedback on the mockup
```

## Relationship to personal-agents

This repo is standalone. It is not part of the personal-agents system and does not read `profile.json`. It exists purely to house the PurposeTask feedback artifacts.
