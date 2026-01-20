# Strange Times

A 16-bit *Stranger Things*–inspired game built in **Unity**, set in the Upside Down.

---

## Game Overview

**Strange Times** is a retro-style action game where players can choose to play as either a **Hazmat Soldier** or a **Demogorgon**. The game features combat-driven gameplay, AI-controlled enemies, and an eerie reimagining of Hawkins and the Upside Down.

---

## Playable Characters

### Hazmat Soldier (Human)
- Customizable name
- Equip armor, weapons, and upgraded suits
- Fights Demogorgons in the Upside Down and Hawkins Lab

### Demogorgon
- Attacks Hawkins Lab, Hawkins town, and hazmat soldiers
- Can kill humans in one hit
- Feeds on corpses to regain health

---

## World Design

- **Upside Down**
  - Procedurally generated *or* hand-crafted
- **Hawkins**
  - Town and Lab areas
- **Right Side Up**
  - Limited to Hawkins Lab

---

## Combat Mechanics

### Demogorgon Combat
- One-hit kills using collision detection + attack animation
- Killed enemies:
  - Fly backward on death
  - Switch to a second “dead” sprite with a large cut
- Feeding:
  - Restores health
  - Demogorgon is immobile for **2.5 seconds** while feeding

### Health & Damage Values
| Weapon          | Damage |
|-----------------|--------|
| Flamethrower    | −5 HP / second |
| Gun             | −5 HP per shot |
| Shotgun         | −15 HP per shot |

- Demogorgon starts with **50 HP**

---

## Crawls

- When playing as a hazmat soldier, you can collect coins, items (health buffs ect.), armor, and other weapons
- If you die on a crawl, you lose all collected items.
- You enter a crawl by going through the main gate at hawkins lab and start in the upside down version of it.

---

## AI Behavior

- Demogorgons chase humans when playing as a human
- Humans attack you when playing as the Demogorgon
- Humans can appear in the Upside Down
- Demodogs accompany the Demogorgon and they attack humans

---

## Enemies & Creatures

- Hazmat Soldiers NPC + playable
- military personnel (both Earth + upside down) and scientists (hawkins lab) NPCs
- Demogorgons NPC + playable
- Demodogs NPC 
- Mind Flayer *(planned)*

---

## Art Style

- 16-bit pixel art
- Retro horror aesthetic

---

## Platforms & Distribution

- Built with **Unity**
- Published on:
  - Unity Play
  - itch.io
- Web-embeddable version supported

---

## Planned Features

- Mind Flayer boss
- Expanded Hawkins town
- More weapons and armor upgrades
- Improved enemy AI

---

## Development

- Engine: Unity
- Language: C#
- Platform: PC / Web

---
