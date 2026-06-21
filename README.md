<div align="center">

# gtv-app

**A native desktop remote for Google TV — if you want it.**

🗳️ **[Vote on it →](https://github.com/kud/gtv-app/issues/1)**

</div>

> **Status: RFC.** This app doesn't exist yet. Whether it gets built depends on you.

[`@kud/gtv-cli`](https://github.com/kud/gtv-cli) already controls a Google TV from the
terminal, and [`@kud/gtv`](https://github.com/kud/gtv) is a framework-agnostic core ready to
power a GUI. `gtv-app` would wrap that core in a **native desktop remote** — a real menu-bar /
window app you click, not a terminal you type into.

Before building it, I want to know whether anyone actually wants it.

## 🗳️ Cast your vote

Head to **[the RFC issue](https://github.com/kud/gtv-app/issues/1)** and react to the vote
comment:

| React | Means                            |
| ----- | -------------------------------- |
| 👍    | I want a native desktop app      |
| 🚀    | I'd use it daily / happy to test |
| ❤️    | Love the idea                    |
| 👀    | Watching, undecided              |

No comment required — a single reaction is your vote. If enough interest shows up, I'll build it.

## What it would be

- **Native desktop remote** — a macOS menu-bar / window app (Tauri), not a browser tab.
- **Same engine as the CLI** — built on [`@kud/gtv`](https://github.com/kud/gtv): discovery,
  pairing, and a stateful session.
- **Point-and-click** — D-pad, playback, volume, an app launcher, and keyboard input, all
  without the terminal.

## Meanwhile, there's the CLI

Don't want to wait for a vote? [`@kud/gtv-cli`](https://github.com/kud/gtv-cli) already does all
of this from your terminal today:

```sh
npm install -g @kud/gtv-cli
gtv
```

---

MIT © [kud](https://github.com/kud)
