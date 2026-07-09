# 🐉 Dragon Warrior Quest

An epic, multi-lingual, RPG-style board game built with pure HTML, CSS, and JavaScript. 

Roll the dice, navigate a treacherous board filled with Magic Portals and Dragon Traps, collect precious Jewels, and utilize unique class abilities to be the first hero to reach exactly Tile 100 and defeat the Dragon!

## ✨ Features

* **9 Unique Hero Classes:** Play as a Knight, Ranger, Mage, Ninja, Vampire, Fairy, Werewolf, Royal, or Scholar. Every class has a unique game-changing ability!
* **AI Name Generation:** Uses a lightning-fast AI model (Llama) to auto-generate context-aware, culturally accurate fantasy names based on your selected class and language.
* **Massive Cultural Failsafes:** If the AI is ever offline, the game instantly falls back to massive local arrays of legendary names, including Arthurian legends, *Three Kingdoms* strategists, *Wuxia/Xianxia* masters, and Sengoku-period Samurai.
* **4 Languages Supported:** Fully playable in English, Traditional Chinese (繁體中文), Japanese (日本語), and Spanish (Español) with dynamic translations.
* **Dynamic Event Log:** A built-in terminal keeps track of every dice roll, trap sprung, jewel spent, and magical ability used.
* **Procedural Board Generation:** The board is generated randomly every time you play, guaranteeing a new layout of traps and portals.

## 📜 Quest Rules

1. **The Goal:** Reach exactly **Tile 100** to defeat the Dragon! If you roll a number that takes you past 100, you will bounce backwards.
2. **Portals & Traps:** **Magic Portals 🌀** jump you forward. **Dragon Traps 🔥** drop you backward. Watch out for the guaranteed endgame trap between tiles 96-99!
3. **Jewel Shield:** Collect **💎 Jewels** during your journey. If you land on a trap, you will automatically spend 3 Jewels (or 2 if you are a Knight) to shatter the trap and stay safe!
4. **Milestones:** Passing tiles **25, 50, and 75** yields Treasure Chests containing 1 Jewel (or 2 for the Knight).

## ⚔️ Hero Classes

Every class bends the rules of the board in their own unique way:
* 🛡️ **Knight:** Trap shields cost only 2 Jewels. Gains an extra +1 Jewel from Milestones.
* 🏹 **Ranger:** Speed boosts! Adds +1 to every dice roll.
* 🧙 **Mage:** Earns 3 Jewels from Portals. Automatically spends 5 Jewels to forge a new, permanent Portal forward.
* 🥷 **Ninja:** Rolling a 6 grants a bonus turn.
* 🧛 **Vampire:** Chaos magic! When trapped, swaps places with a random player ahead of them. If already in the lead, feeds in the dark for 3 Jewels instead.
* 🧚 **Fairy:** Starts with 3 Jewels. Rolling a 6 shields everyone from traps for 1 turn, but forces them to pay you 1 Jewel in tribute!
* 🐺 **Werewolf:** Immune to 1 Trap as a Wolf. Reverts to a Human after springing a trap, and transforms back into a Wolf upon hitting the next one.
* 👑 **Royal:** Never bounces back at the end of the board. Stops exactly at the Lair.
* 🦉 **Scholar:** Closes Portals permanently after use. Uses alchemy to deepen Traps, pushing their destination lower for the next victim.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, Vanilla JavaScript (No external frameworks or dependencies).
* **AI Integration:** [Pollinations AI](https://pollinations.ai/) text generation API (Llama model) with custom parsing logic.
* **Deployment:** Optimized for Cloudflare Pages.

## 🚀 How to Play

Because this game is built in pure Vanilla JavaScript, no complex installation is required!

1. Clone or download this repository.
2. Open the `index.html` file directly in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Select your language, set up your players, click **Start Quest**, and roll the dice!

---
*Game Design & Development by Colette.*