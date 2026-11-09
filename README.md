# Solo Leveling Dungeon Hunter

A walk-around dungeon hunter in the style of early Pokémon, with a Summoners War feel. Explore top-down dungeon floors, bump into monsters to battle them, beat the boss, and descend to the next, harder gate. No build step — open `index.html` in any modern browser.

## How it plays

- Each gate is a procedurally generated floor: 9 roaming monsters, 3 treasure chests (gold and potions), and a boss waiting in the far corner.
- Move with the on-screen D-pad, arrow keys, or WASD. Bump into a monster to start a battle.
- Win the battle and you're back on the map. Beat the boss and a glowing portal opens where it fell — walk in to descend to the next gate.
- Four tabs keep it tidy: **Hunt**, **Level Up**, **Army**, and **Shop**.

## Battles

- Enemies fight on a glowing rune platform, with star grades, element badges, and turn bars.
- Combat is turn-by-turn, based on speed: everyone has their own turn gauge, and a turn-order strip shows who goes next.
- Attack, or use the hunter's skills: Power Strike, Shadow Rush, and Monarch's Wrath.
- AUTO battle and ×1/×2/×3 speed, plus a Flee button.
- Beat a boss and you can ARISE it as a shadow — each shadow adds a permanent damage bonus.

## Summons (Shadow Army)

- Mystic Scroll summons build a collectible Shadow Army that fights with you.
- Each summon has one of 6 elements — **Fire, Water, Earth, Wind, Light, Dark** — with an advantage cycle, and one of 4 roles: **Attack, Defense, Healer, Support**.
- Each summon has **4 named skills with descriptions**, so you can see what it's good at and build toward that. Attacks run off each summon's own skills, element, and role.
- Summons level up from their own attacks — XP for every hit they land, plus a bonus for the killing blow.
- Each summon **evolves twice, at Lv 8 and Lv 16, and each evolution doubles its total power**.
- Each summon has **6 rune slots** of its own. Runes drop from monsters and bosses in five sets — Fatal, Energy, Guard, Rage, Swift — so you can rune each shadow toward its strengths.

## Progression

- Earn XP and gold, level up from Rank E toward S and Monarch, and spend stat points on Strength, Agility, and Vitality.
- Leveling up opens a pop-up and pauses the battle behind it, with buttons to spend stat points or keep hunting.
- The Level Up tab shows your hunter's stats plus a growth card for each summon, with a gold badge when you have points to spend.
- A shop sells weapons, armor, potions, and healing.
- Tap any summon card in the **Army** tab and it jumps straight to that summon on the Level Up tab — the card flashes gold so you spot it right away.

## Saving

Progress auto-saves after every action and when you close the tab — level, XP, gold, shadow army, runes, gate, and your exact spot on the floor. Come back and it picks up right where you left off. A "Progress saved" line shows the last save time. Restart clears the save.

## Controls

- **Move:** on-screen D-pad, arrow keys, or WASD
- **Battle:** tap Attack, a skill, or a potion; AUTO to let it fight for you

## Run it locally

```bash
# any static server works, e.g.
python3 -m http.server
```

Then open http://localhost:8000 in your browser.

## Play online

Published with GitHub Pages — play it at https://prestonross88.github.io/solo-leveling-dungeon-hunter/

*Arise.*
