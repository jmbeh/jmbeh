# Hi, I'm JM 👋

Simplicity is my compass, but I earn it through rigorous thinking—I use data to light the way when it matters, and trust judgment when it's time to learn by doing. That's because **strategy is intent; code is reality**, so I channel my curiosity into **agentic coding** to ensure they actually align. I write and prototype to comprehend the problem space before engineering begins, because that's where the hard questions live. 

---

### 🧪 Insights from the Lab

I build tools that solve practical problems in my daily life—and just as importantly, to learn. Each project teaches me something about technology *and* about people.

**Nutty Baseball** — *Learning baseball alongside my son*  
Built as a web app with zero backend—local storage only. I wanted zero friction for parents who feel behind their kids. My son's love for Peanuts comics inspired him to explore baseball, so the Peanuts theme wasn't just decoration—it reframed "I don't know baseball" from embarrassing to endearing. Adults relax when the UI winks at their confusion. (Also learned way more about Charlie Brown than expected.)

**Dad Aura** — *Real-time aura scoring from my son's Apple Watch*  
SMS webhook → Supabase real-time → instant dashboard updates. The tech came together quickly. But what I didn't expect: my son controlling how many times I can "flip" negative scores became our most engaging feature. That power asymmetry created negotiation moments that strengthened our relationship more than the scoring itself.

**Allegro** — *Music practice companion for parents*  
Multi-API orchestration: AudD for recognition, MusicBrainz for metadata, Spotify for recommendations, Claude for coaching suggestions. Each service fails gracefully without breaking the experience. What surprised me: audio recognition trained on studio recordings struggles with music practice. Kids stop mid-phrase, repeat sections, play wrong notes—that abrupt start-stop-repeat pattern makes it hard to identify the song, let alone the version or composer. Suddenly I needed "close enough" matching that works with fragments. Real-world use breaks clean assumptions.

**LifeSynced** — *Unified work/personal calendar*  
The hardest part: deciphering future events from recurring series that accumulated one-off adjustments over time. The way ICS encodes these makes it surprisingly complex to figure out what's actually happening next Tuesday. But the design decision that unlocked real utility: privacy-first by default. Showing "[Personal Event]" with password-gated reveal made the tool safe to demo with any audience—so more people could see what it does: detect conflicts between calendars *and* denoise by hiding events that clutter your calendar but don't actually matter. Good defaults expand both reach and utility.

---

### 🛠️ The Toolkit

To build and learn at this pace, I keep my stack modern and flexible:
- **Writing & Agentic Coding:** Cursor
- **Frameworks:** LangChain, Model Context Protocol
- **Prototyping:** Next.js, TypeScript, Python
- **Data:** PostgreSQL, Prisma
- **Infrastructure:** GitHub, Vercel
- **Design:** Tailwind CSS (personal); Adobe Spectrum (work)

But honestly, the tools matter less than the mindset. I don't code for the mechanics; I code agentically to validate ideas, test hypotheses, prove the architecture holds—and ensure the intent is ultimately served.

---

### 🔭 Current Focus

Here's what I'm working on next:

**Personal Projects**

- **Nutty Baseball:** Ambient listening for backyard games—automatically tracking scores by listening to our natural conversation. The challenge: phone mics pick up everything, and game-relevant talk ("that's a strike!") gets mixed with regular conversation. Same audio recognition complexity as Allegro, but now I need to filter signal from noise in real-time.

- **Dad Aura:** AI guardrails that go beyond content filtering—teaching the system when to say no, when to disagree with dad or child, and how to nurture healthy values in both. The tricky part: defining what "right" looks like when parenting decisions aren't black-and-white. Sometimes refusing to change aura points *is* the ethical choice, even when a parent or child asks. Teaching AI to enforce alignment boundaries requires codifying judgment, not just rules.

- **Allegro:** Real-time "play along" suggestions—analyzing what my kids are playing and recommending chords/riffs so I can jam with them on guitar. Building on the audio recognition lessons: matching their imperfect playing to playable chord progressions in real-time, keeping suggestions simple enough for my skill level, and making the "close enough" matching work when they drift tempo or hit wrong notes. It's the same audio challenge as before, but now with the added complexity of making recommendations musically coherent.

- **LifeSynced:** Adding an AI agent that proactively reminds me of important life events (wedding anniversary, birthdays) and helps me plan ahead—suggesting how to celebrate, curating gift ideas, even buying small gifts on my behalf. The interesting part: teaching an agent to act autonomously on commerce decisions while respecting budget constraints and personal taste. It's agentic commerce in practice, juggling multiple calendars while ensuring nothing important falls through the cracks.

**At Work (Adobe)**

These personal projects help me think through problems I tackle professionally. My work repos are internal, but I'm focused on monetization strategy (defining how we value and price AI/MCP/API primitives), building a prototype library for prototype-first development for the entire organization, and codifying expertise into teachable frameworks for teams and AI systems. When prototypes reveal flaws in my assumptions early, that's a win—teams move faster when we learn what doesn't work before committing at scale. Across all of it, my approach stays consistent: build to understand, use to validate, distill to refine.

---

### 📬 Let's Connect

I value meaningful connections—let's trade notes on AI and monetization, or collaborate on interesting problems.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jmbeh/)

