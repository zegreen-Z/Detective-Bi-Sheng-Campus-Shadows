# 🕵️ Detective Survival Simulator  
*A branching narrative game about truth, signals, and the cost of looking away*

## 📖 Overview

**Detective Survival Simulator** is a single‑player, text‑driven interactive fiction game set in a fictional university. You play as a new student who, together with a handful of classmates, uncovers two interwoven cases: an industrial cover‑up at a local shipyard, and a deeply troubling pattern of ignored warning signs leading to a campus tragedy.

The game is a **pure front‑end web application** – no server, no database – built entirely with HTML, CSS, and vanilla JavaScript. It can be played directly in your browser, and all progress is saved locally in your browser's `localStorage`.

> **Current version**: v5.0 (June 2026)

## 🎭 Story & Themes

The narrative explores two parallel investigations:

1. **The Shipyard Case** – A worker dies under suspicious circumstances. As you dig deeper, you uncover illegal toxic dumping, financial corruption, and a murder contract.

2. **The Campus Case** – A withdrawn student exhibits escalating warning signs over several months. Despite multiple red flags reported by teachers, counsellors, and peers, the system fails to intervene in time.

At its heart, the game asks: **What happens when signals are everywhere, but no one connects them?**

The story is mature, grounded, and inspired by real‑world events – it does not glorify violence, but rather examines the human cost of institutional inertia and inaction.

## ✨ Features

- **Branching narrative** with meaningful choices that affect the outcome.
- **Six playable chapters** with over 60 unique scenes and 100+ choices.
- **Four character archetypes** (Balanced, Ability‑focused, Fate‑driven) with different stat growth multipliers.
- **Five core stats**: HP, Intelligence, Physical, Presence, Luck – each capped at 5 with weighted multipliers per character type.
- **Clue system** – collect and track narrative clues; the final ending depends on how many clues you uncover.
- **NPC relationship system** – build trust with key characters to unlock deeper dialogue and hidden information.
- **Daily activities** (study, gym, socialise, rest) to manage stats between story events.
- **Three‑slot save/load system** using browser `localStorage`.
- **Typing animation** for immersive reading, with a skip button.
- **Responsive dark‑theme UI** optimised for both desktop and mobile.

## 🧑‍🤝‍🧑 Characters（This is a temporary beta build; it will be overwritten in the summer update.）

| Name | Type | Description |
|------|------|-------------|
| **冰燃气** (Balanced) | No weakness, no standout strength. Stat gain ×0.5. Ideal for first‑time players. |
| **水蒸气** (Ability) | High Intelligence & Physical, but low Presence & Luck. Stat gain ×1.0. Best for direct investigation. |
| **小煤气** (Fate) | High Luck & Presence, but low Intelligence & Physical. Stat gain random (0.1–0.8). High risk, high reward. |

Plus six NPCs with their own dialogue trees and relationship scores that affect what they reveal.

## 🎮 How to Play

1. **Choose a character** – each has different starting stats and growth modifiers.
2. **Read the story** – text appears with a typing effect. Click choices to advance.
3. **Manage your stats** – HP, Intelligence, Physical, Presence, and Luck all influence your success in skill checks and the final outcome.
4. **Collect clues** – every clue you find contributes to the ending you will receive.
5. **Talk to NPCs** – build relationships to unlock deeper conversations and hidden information.
6. **Use Daily actions** between main story beats to prepare for upcoming challenges.
7. **Save often** – use the three save slots to keep your progress.

> **Tip**: The Fate‑type character (“小煤气”) has a random stat multiplier each time – you might get a huge bonus or a tiny one. Save before taking risky actions!

## 💾 Save System

All saves are stored in your browser’s `localStorage` under the key `detective_save_slot_1/2/3`.  
You can save, overwrite, load, or delete any slot from the in‑game **Save** tab.

## 🛠️ Technology Stack

- **Frontend**: Pure HTML5 + CSS3 + Vanilla JavaScript (no frameworks)
- **Styling**: Custom CSS with CSS variables, responsive design, smooth animations
- **Data**: All story content is embedded in a single JavaScript object (`STORY`) – easily replaceable with a JSON fetch if desired
- **Persistence**: Browser `localStorage` for saving/loading
- **Deployment**: GitHub Pages (static hosting)

## 🚀 Future Plans

- [ ] Expand and refine the story content – the current version is a rough prototype; future updates will rewrite/add more branching plots, enrich character dialogues, and deepen the narrative.
- [ ] Extract story data to an external `story.js` for easier editing.
- [ ] Add more character‑specific dialogue and branching paths.
- [ ] Polish the UI with more visual feedback and sound effects.
- [ ] Add an optional “speed‑run” mode.

## 📝 Personal Notes *(by the author)*

> **2026‑06‑24**  
> This is the first finished project I made during the DuanWu Festival holiday on June 19, 2026 – of course, with a huge help from AI. I originally wanted to submit this as my C++ assignment, but the text/plot part didn't quite satisfy me, and revising it would take forever (though I do want to make it perfect, because this story is deeply tied to my three best friends so far: one is a junior high classmate, and our friendship has amazingly lasted this long; the other two are my high school deskmate and the one in front of me – without them, I don't think I would have easily climbed out of the drowning sea). Besides, I have five final exams waiting for me – if I don't get ideal grades and miss the scholarship, I'll be super sad (but as I'm writing this, I've already messed up two exams, so…). Anyway, that's why I made a new one, EgaoCampus (a parody/abstract school), blending various trending college‑related memes and events. I hope it brings people some joy.  
> Because, you know, finding happiness for myself is really hard – maybe due to neurodivergence (or maybe not, but I don't want to use that as an excuse), my threshold for happiness is just too high. I wish that if I project happiness outward, it could somehow bounce back to me.  
> To avoid leaving this repository empty – which would be too rude – I'm uploading the HTML file. During the summer break, I'll further update both games, and upload thought‑over, polished C++ code, JSON files, and more (in short, a prettier and more complete project).

## 📄 Copyright & Usage License

This game is a derivative fan-work created as a companion piece to the author's original novel “宿慧侦探毕盛”. It is provided to players **completely free of charge**.

**All game content** (including but not limited to story text, character designs, dialogue, scenes, UI layout, and source code) is the exclusive property of the author Moyang（zegreen-Z）, and is protected by the Copyright Law of the People's Republic of China and applicable international copyright treaties.

**You are permitted to:**
- Download, install, and play the game for personal entertainment;
- Share the game with others, provided that you distribute it intact and without any modifications.

**You are NOT permitted to:**
- Copy, modify, adapt, reverse‑engineer, or create derivative works based on this game;
- Use the game or any part of it for commercial purposes (including selling, advertising, paid distribution, etc.);
- Remove or alter any copyright notices or attribution within the game.

For cooperation or special licensing requests, please contact me via GitHub (open an Issue or start a Discussion in this repository).

## 🙏 Acknowledgements

- Thanks to my friends for their emotional support.
- Thanks to the open‑source community for making web development accessible.
- Special thanks to AI assistants for helping with debugging and narrative structure.

##**Status: Final exam period — partial files pending. Full update coming this summer.**
