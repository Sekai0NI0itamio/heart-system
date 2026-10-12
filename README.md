# Heart System

A lightweight, server-side permadeath mod for Minecraft 1.12.2 Forge. Every player has a heart count. Die and you lose one. Kill another player and you gain one. Reach zero hearts and you are permanently banned.

No gimmicks. No altars. Just hearts.

## How It Works

| Event | Effect |.
|---|---|.
| You die (any cause) | −1 heart |.
| You kill another player | +1 heart |.

Hearts are the **only** way to gain max health. Mob kills, items, and regeneration do not grant hearts. The only path to more hearts is PvP.

## Features

- **Death penalty** — Every death costs exactly 1 heart, regardless of cause.
- **Permadeath** — When a player's hearts reach the minimum (default 0), they are permanently banned with the reason "Permadeath: ran out of hearts".
- **Live max health** — The player's max health bar reflects their current heart count in real time.
- **Persistence** — Heart counts are saved per player UUID and survive server restarts.
- **Server broadcast** — A message is sent to all online players when someone is permabanned.

---

This github repository is auto created using itamio's Mod Compiler repository workflow.

If this project is useful, consider giving it a star. It helps others discover the project and motivates continued development.
