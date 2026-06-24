# Chat log — session 2026-06-13

Setting up the repo and building the first draft of the slide deck.

---

**Me:** I'm going to give a presentation and this repo is for the slidedeck and whatever else I need. You're going to help me with tools to build the deck and to get over my extreme fear of empty page. I do know what I want to say but getting started is difficult.

**Claude:** Asked about: (1) what NPS stands for, (2) audience and setting, (3) slide tool preference.

Answers: Net Promoter Score · Conference/meetup · Reveal.js

---

**Me:** All of those things. It is a stupid metric in isolation and not "the one number you need to know" like the original paper claimed in its title. But when you ask enough many people in comparable setting and you have a benchmark it really does carry information. I have seen this in my job at HappySignals. And from a different perspective, it's an actual statistic, a combination index of kurtosis and skewness, and that's what I'm focusing on. I'm a statistician, not a market researcher.

**Claude:** Identified three-act structure:
1. Tear it down — the "one number" claim is overblown, show the information loss
2. Build it back up — NPS is skewness + kurtosis, it's a real statistic
3. Land the nuance — it works when: large enough sample, comparable conditions, benchmark exists. HappySignals evidence.

Built first-draft `index.html` with Reveal.js via CDN. Slides scaffold with TODO stubs for: exact formula/derivation, skewness/kurtosis diagrams, HappySignals data, speaker name and conference details.

