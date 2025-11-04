# Ryukyu 琉球
### A 3D Hack-and-Slash set in 1600s Okinawa — Master Karate, Unleash Fire, and Defend Your Homeland

![Unreal Engine](https://img.shields.io/badge/Unreal_Engine-black?style=flat-square&logo=unrealengine&logoColor=white)
![C++](https://img.shields.io/badge/C++-blue?style=flat-square&logo=cplusplus&logoColor=white)

![Ryukyu Banner](https://user-images.githubusercontent.com/example/RyukyuBanner.png)

---

## Overview

**Ryukyu** is a 3D **hack-and-slash action game** built in **Unreal Engine 5**, set in early 1600s Okinawa after the Satsuma invasion of 1609 — a time when weapons were banned and **karate (empty-hand fighting)** began to rise.

You play as **Chiyo (千代)**, one of the first karate practitioners, who must defend Okinawa from **demonic invaders** using martial arts alone.  
Combat revolves around **chaining combos**, **dodging**, and **unlocking new techniques** through a traditional **karate belt progression system**.

---

## Core Fantasy

> “I am mastering karate in its earliest form, unlocking supernatural powers to avenge my family and save Okinawa.”

---

## Core Gameplay Loop

1. **Train in the Dojo** – Practice attacks on training dummies in a safe zone.  
2. **Fight Waves of Demons** – Test your mastery in real combat arenas.  
3. **Build Combos** – Chain light and heavy attacks to rack up XP and belt rank.  
4. **Progress Belts** – Unlock new moves, dodge counters, and fire techniques.  
5. **Mastery & Challenge** – Push your skills against elite enemies and bosses.

> **Loop:** Train → Fight → Progress → Reward → Mastery

---

## Gameplay Features

| Feature | Description |
|----------|--------------|
| **Combo System** | Chain light/heavy attacks to create unique combo strings. |
| **Belt Progression** | Earn XP to advance from **White → Black Belt**, unlocking new moves. |
| **Dynamic Combat** | Balance safe combos vs riskier, high-damage techniques. |
| **Stylish Feedback** | Combo counter, hit sparks, and smooth animation flow. |
| **Enemy AI** | Basic AI that approaches, attacks, and retreats — scalable to elite variants. |
| **Dojo Hub** | A tranquil training space to practice moves and experiment with flow. |

---

## Prototype Scope (v0.1)

- 1 Playable character (Chiyo)
- Working dojo environment
- Light / Heavy attack combos
- Health system & reactive training dummies
- Basic belt progression: **White → Yellow**
- Combo counter + simple UI (health, belt XP)
- Next: Enemy AI + Fire unlock system

---

## Inspirations

- **Bayonetta 3 / Devil May Cry 5** – stylish, combo-heavy action  
- **Sifu** – martial arts realism and flow-based combat rhythm  
- **Lollipop Chainsaw** – arcade-style hack-and-slash energy  
- **Okinawan Karate History** – real-world inspiration from weapon bans and kobudo origins  

---

## Art, UI, & Music

- **Visual Style:** grounded realism with light supernatural energy
- **UI:** minimalist Japanese-inspired HUD with health, combo, and belt XP meters  
- **Music:** composed using *traditional 1600s Japanese instruments*  
  - Shamisen (三味線)  
  - Shakuhachi (尺八)  
  - Koto (琴)  
  - Biwa (琵琶)  
  - Tsuzumi (鼓)

---

## Technical Details

**Engine:** Unreal Engine 5  
**Language:** Blueprints (visual scripting)  
**Template:** Third-Person  
**Platform:** Windows (Prototype)  

### Player Blueprint Variables
| Variable | Type | Description |
|-----------|------|-------------|
| `IsAttacking` | Boolean | Tracks if Chiyo is mid-animation |
| `ComboIndex` | Integer | Determines current combo stage |
| `QueuedInput` | Enum/State | Stores next attack input in combo window |

### Input Mapping
| Action | Keyboard | Gamepad |
|--------|-----------|----------|
| Light Attack | Left Mouse Button | Square / X |
| Heavy Attack | E | Triangle / Y |
| Dodge | Left Ctrl | R1 |
| Jump | Space | Cross / A |

---

## Narrative Overview

**Act 1: Beginnings**  
Chiyo’s family is slaughtered by demons. She trains in secret, discovering the origins of karate.

**Act 2: Rising Conflict**  
As the invasion worsens, Chiyo gains fire powers — her fists ignite with spiritual energy.

**Act 3: Mastery & Resistance**  
Chiyo becomes a living symbol of Okinawan resistance, taking the fight to the demon fortress.

**Final Confrontation:**  
A fiery duel with the Demon Lord — the embodiment of oppression — marking the birth of karate as both art and resistance.

---

## Future Goals

- Enemy & Boss AI with multi-phase behavior trees  
- Full Belt System (White → Black)  
- Fire-wielding unlock progression  
- Environmental hazards (traps, destructibles)  
- Narrative cutscenes & voice acting  
- Multiple level environments (dojo, villages, battlefields)

---

## Credits

**Game Design / Development / Music:**  
 *Amani Howe*  

**Engine:** Unreal Engine 5  
**Tools Used:** Photoshop, MuseScore, Blueprints, UMG, Behavior Trees

---

## Disclaimer

> Ryukyu is a **work of fiction** inspired by Okinawan culture and the origins of karate.  
> It is not a historical simulation and does not aim to represent real events or beliefs.

---

## Other

Developed as part of **Module 4002 – Unreal Engine Game Design**  
*Prototype Date:* October 2025  
