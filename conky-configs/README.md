# 🌀 TokyoNight Conky Configuration

A Minimal Conky configuration inspired by the [TokyoNight](https://github.com/folke/tokyonight.nvim) color scheme. Designed for Linux Mint Cinnamon and optimized for JetBrains Mono font lovers.

This config displays essential system information  CPU, memory, disk usage, uptime, temperatures, and network activity in a stylish panel on your desktop.


## 📁 Folder Structure

```
conky-configs/
├── TokyoNight.conf
└── README.md
```

# ⚙️ Installation

### 🧰 Dependencies

Make sure you have Conky and lm-sensors installed:

```bash
sudo apt update
sudo apt install conky lm-sensors
```
Run sensor detection if not done before:

```bash
sudo sensors-detect
```
### 📦 Setup Instructions

1. Clone This Repository
```bash
git clone https://github.com/Nidszxh/DotfilesDump.git
cd DotfilesDump 
```

2. Move the Config
```bash
mkdir -p ~/.config/conky/
cp conky-configs/TokyoNight.conf ~/.config/conky/
```

3. Launch Conky
```bash
conky -c ~/.config/conky/TokyoNight.conf
```