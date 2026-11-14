# ✨ ANIMON

**Pull a random anime character. Get a shiny gold collectible card. Flex it.**

ANIMON is a single-file anime character discovery app that turns the anime multiverse into a booster pack. Hit **NEW CARD**, pick your element, and see who the universe hands you: artwork, series, a real quote, and a rarity based on how loved the character actually is.

<img width="1920" height="1021" alt="image" src="https://github.com/user-attachments/assets/a47973b3-df2b-4aef-8d1c-7a3462cb1663" />

---

## 🎴 What's on a card?

Every card has exactly five things:

1. **Rarity badge** at the top
2. **Character artwork** as the main event
3. **Anime series** the character comes from
4. **Character name**
5. **A real quote** from that series
6. **Unique number** at the bottom, which is the character's actual ID from the database (never random)

No fake stats. No ATK/DEF nonsense. Just vibes and lore.

## 💎 Rarity

Rarity is **not random**. It's calculated from how many people have favourited the character.

| Tier | Favourites | Vibe |
|---|---|---|
| 🌈 **MYTHIC** | 30,000+ | The rarest of the rare |
| 🟡 **LEGENDARY** | 10,000+ | Everyone knows them |
| 🟣 **EPIC** | 2,500+ | Seriously popular |
| 🔵 **RARE** | 500+ | A solid fan base |
| ⚪ **COMMON** | under 500 | Hidden gems |

## 🔥 Five elemental reveals

Each pull is randomly summoned with an element, each with its own animation and sound:

🔥 Fire · 🌊 Water · 🌿 Earth · 🌪️ Air · ⚡ Lightning

## 🛡️ Strict validation

ANIMON is picky. A character is **only revealed** if all of these check out:

- ✅ The artwork actually loads
- ✅ The anime series is found
- ✅ A genuine quote is fetched
- ✅ The quote belongs to that series

If anything fails, the character is quietly discarded and the search continues behind the loading screen.

## 🖼️ One-click PNG

Hit **SAVE PNG** and your card downloads as a **1080 × 1620** image, the same size on every screen, phone or ultrawide.

## 🌌 The atmosphere

- Drifting nebula background with twinkling stars, popping sparkles and the occasional shooting star
- Ambient space drone with soft chimes (mute it with the ♪ button)
- Reveal sounds that change with each element
- Fully responsive, so the card fits your window instead of overflowing it

## 🔌 Powered by

- **[Jikan](https://jikan.moe/)** (via an edge proxy) for characters, artwork and series data
- **[Animechan](https://animechan.io/)** for anime quotes

### ⏳ A note on rate limits

Animechan's free tier has a small hourly request limit. If you pull a lot of cards quickly, ANIMON will tell you how long to wait. To save your quota, it remembers every quote it finds, and which series have no quotes, in your browser's local storage, so the more you play, the fewer requests it needs.

## 🤝 Contributing

Ideas, bugs and pull requests are welcome. Open an issue and say hi.

## ⭐ Liked it?

If ANIMON made you smile, **star the repo**. It costs nothing and makes a developer very happy.

---

## 📜 License

This project is licensed under the **MIT License**.

You are free to use, copy, modify, merge, publish, distribute and improve the original project code under the terms of the license.

See the [LICENSE](LICENSE) file for details.

**Important:** The MIT License applies to the original project code, not third-party anime characters, artwork, logos, quotes or API content. Those remain subject to their respective rights and terms.

---

Developed by **VinuXD** 💜
