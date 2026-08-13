[![Modrinth](https://img.shields.io/badge/Modrinth-NukeFishing-brightgreen)](https://modrinth.com/plugin/xrayspyglass)
# XraySpyglass 🔭👁️

Turn a regular spyglass into a **player-detecting X-Ray Spyglass**!
Aim in any direction and right-click — any player caught in your sightline **glows through walls** for a few seconds. 🕵️‍♂️✨

---

## 🚀 Features 🌟

- `/getxrayspyglass` 🛠️ → Get a custom glowing spyglass
- Right-click while aiming 🔭 → Reveals any player along your line of sight, walls included
- **Invisible players are skipped** — no potion-cheesing 🚫🫥
- **Sneaking players are still caught** — nowhere to hide 🕵️
- Configurable cooldown & glow duration via `config.yml` ⚙️
- Simple, lightweight, no external dependencies

---

## 📜 Commands

| Command             | Description                     |
| -------------------- | -------------------------------- |
| `/getxrayspyglass`   | 🔭 Get the X-Ray Spyglass        |

## 🔑 Permissions

| Permission             | Default | Description                              |
| ----------------------- | ------- | ------------------------------------------ |
| `xrayspyglass.get`      | op      | Allows getting the X-Ray Spyglass          |
| `xrayspyglass.use`      | true    | Allows using the X-Ray Spyglass effect     |

## ⚙️ Configuration

```yaml
# How many seconds must pass between spyglass uses
cooldown-seconds: 10

# How many seconds a detected player stays glowing
glow-seconds: 10
```

Found at `plugins/XraySpyglass/config.yml` after first run — edit and `/reload` (or restart) to apply.

---

## ⚡ Installation

1. Download the latest JAR and place it in your server's `plugins` folder 📥
2. Start or restart your Paper server 🔄

**Requires:** Paper 1.21.11+ • Java 21+

---

## 📄 Author & Use

Plugin by **Metro** 💥
Free to use on your servers. Re-uploading or claiming as your own is **not allowed**.

---

Have fun spotting players through walls! 🎉🔭👁️
