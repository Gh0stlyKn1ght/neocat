# **Neocat**, your Rust-powered GUI networking toolkit for Linux:

---

## 📘 `README.md` — Neocat

````markdown
# 🐱 Neocat

**Neocat** is a modern, Rust-powered GUI networking toolkit for Linux systems, designed for penetration testers, sysadmins, and developers who want a better interface for common terminal tasks like reverse shells, network scans, and HTTP testing.

> 🔧 Inspired by tools like `netcat`, `nmap`, and `curl`, Neocat wraps essential networking utilities in a sleek, themed GUI with project saving, visual workflow, and live network insights.

---

## 🚀 Features

- 📝 **Hosts File Editor**
  - Enable/disable entries with one click
  - Apply changes directly to `/etc/hosts` (with sudo)
  - Save profiles for dev, prod, testing, or ad-blocking

- 🎧 **Netcat Listener**
  - Start reverse/bind shell listeners on any port
  - Monitor connections in real time
  - Log session output
  - TTY-friendly shell display

- 🌐 **cURL Composer**
  - Build and send HTTP requests
  - Set custom headers, methods, and JSON bodies
  - View raw HTTP responses and status codes

- 🔍 **Nmap Scanner**
  - Run scans (ping, full port, service/version detection)
  - Set options via checkboxes (e.g., `-sV`, `-Pn`, `-O`)
  - Save/recall scan profiles
  - Parse output in-app

- 📡 **Network Info Dashboard**
  - View active network interfaces, IPs, MACs
  - See DNS servers and default gateway
  - Detect public IP using external query

- 🎨 **20+ Built-in Themes**
  - Choose from Dracula, Tokyo Night, Nord, Gruvbox, One Dark, etc.
  - Live preview of colors in each panel
  - Save your preferred theme globally or per project

- 💾 **Project Save/Load**
  - Save your session as a `.neocat` file
  - Restore all settings (netcat, curl, hosts, scans, theme)
  - Great for CTFs, pentests, or reusable lab setups

---

## 🖼️ Screenshots

> Coming soon — once GUI scaffolding is live

---

## 🛠️ Built With

- [Rust](https://www.rust-lang.org/)
- [Iced](https://github.com/iced-rs/iced) — cross-platform GUI in Rust
- `serde`, `tokio`, `reqwest`, `nix` — for JSON, async, HTTP, and system access
- Custom GTK-compatible theming engine

---

## 📦 Installation (Linux/Debian)

```bash
sudo apt install libgtk-3-dev build-essential
git clone https://github.com/yourusername/neocat.git
cd neocat
cargo build --release
sudo ./target/release/neocat
````

---

## 📁 Project Status

🟩 Planning & Design
🟨 GUI Scaffolding (Iced)
⬜ Feature Implementation
⬜ First Release (v0.1.0)

> Want to contribute? See the [Contributing Guide](CONTRIBUTING.md)

---

## 📘 Roadmap

* [ ] Port forwarding helper tab (socat, SSH)
* [ ] Payload generator for bash/python/powershell
* [ ] Shell session manager
* [ ] Plugin system for extensions (e.g. OSINT, HTTP fuzzing)

---

## 🧠 Philosophy

> "Tools should be powerful and invisible."

Neocat gives you the speed and flexibility of the command line with the structure and comfort of a visual interface — without bloated frameworks or unnecessary cloud dependencies. Built from scratch in Rust for security, clarity, and future growth.

---

## 📜 License

MIT

---

## 👤 Author

Created by [Carlos “Gh0stly”](https://github.com/Gh0stlyKn1ght)
Follow for updates: [github.com/Gh0stlyKn1ght/neocat](https://github.com/Gh0stlyKn1ght/neocat)

```


