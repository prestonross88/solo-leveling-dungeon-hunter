# Solo Leveling Dungeon Hunter

A walk-around dungeon hunter in the style of early Pokémon, with a Summoners War feel. Explore top-down dungeon floors, bump into monsters to battle them, beat the boss, and descend to the next, harder gate. No build step — open `index.html` in any modern browser.

## How it plays

- Each gate is a procedurally generated floor: 9 roaming monsters, 3 treasure chests (gold and potions), and a boss waiting in the far corner.
- Move with the on-screen D-pad, arrow keys, or WASD. Bump into a monster to start a battle.
- Win the battle and you're back on the map. Beat the boss and a glowing portal opens where it fell — walk in to descend to the next gate.

## Battles

- Enemies fight on a glowing rune platform, with star grades, element badges (Fire, Water, Wind, Light, Dark), and turn bars. Elements have an advantage triangle.
- Attack, or use three skills: Power Strike, Shadow Rush, and Monarch's Wrath.
- AUTO battle and ×1/×2/×3 speed, plus a Flee button.
- Beat a boss and you can ARISE it as a shadow — each shadow adds a permanent damage bonus.

## Progression

- Earn XP and gold, level up from Rank E toward S and Monarch, and spend stat points on Strength, Agility, and Vitality.
- A shop sells weapons, armor, potions, and healing.
- Mystic Scroll summons build a collectible Shadow Army that fights with you.
- A 6-slot rune system (Fatal, Energy, Guard, Rage, Swift) — runes drop from monsters and bosses.

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
