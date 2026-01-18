# StreakRewards

StreakRewards is a fully customizable **daily streak rewards plugin** for Minecraft servers. It encourages players to join the server daily by rewarding consecutive logins through a clean **GUI-based reward system** with rich visual and sound feedback.

---

## 🚧 Project Status

⚠️ **StreakRewards is currently not available for download.**
This plugin is under active development and continuously being improved.
It will be released publicly once it reaches a stable and production-ready state.

---

## ✨ Features

* 🗓️ **Daily streak system** (consecutive day tracking)
* 🎁 **Day-based rewards** with full customization
* 🖼️ **GUI-based reward menu**
* 🔓 Available / ✅ Claimed / 🔒 Locked reward states
* 🎨 **Hex color support** for names and lores
* 🔊 Sound feedback on actions
* 📩 Chat, ActionBar and Title messages
* 💾 Persistent data storage (UUID-based)
* ⚡ Lightweight and performance-friendly

---

## 🧠 How It Works

Each player has a **daily streak** that increases when rewards are claimed on consecutive days. If a day is missed, the streak can be reset depending on configuration logic.

When a player opens the reward menu:

* The current day reward is shown as **available**
* Previously claimed rewards are marked as **claimed**
* Future rewards remain **locked**

All progress is saved and restored automatically after server restarts.

---

## 🖼️ GUI System

The reward menu is fully configurable via `config.yml`:

* Custom menu title and size
* Decorative items and fillers
* Close button support
* Different item visuals for reward states

Each reward day can display custom names, lores, and materials.

---

## ⚙️ Configuration

StreakRewards uses simple YAML files for configuration.

### `config.yml`

* GUI layout and visuals
* Reward item states (available / claimed / locked)
* Sounds and visual feedback
* Messages, titles, and actionbars

### `data.yml`

* Stores player progress
* Tracks:

  * Last claimed date
  * Current streak count
* UUID-based data storage for reliability

No advanced technical knowledge is required for basic setup.

---

## 🎯 Use Cases

* Survival servers with daily login rewards
* Skyblock servers encouraging daily activity
* Community servers increasing player retention
* Any server looking for a streak-based reward system

---

## 🛠️ Technologies Used

* Java
* Spigot / Paper API
* YAML Configuration

---

## 📄 License

This project is distributed under its own license. Please check the repository for usage terms.

---

Feel free to open issues or suggest improvements!
