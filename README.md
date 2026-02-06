# 🍺 Homebrew Tap

This is the Homebrew tap for `yindia/homebrew-yindia`, providing installation for the following CLI tools:

- [snip](https://github.com/yindia/snip) — SNIP - Search, Navigate, Index, Parse
- [rootcause](https://github.com/yindia/rootcause) — RootCause is a local-first MCP server that helps operators manage Kubernetes resources and identify the real root cause of failures through interoperable toolsets.
- [pltf](https://github.com/yindia/pltf) — The next generation of Infrastructure-as-Code. Work with high-level constructs instead of getting lost in low-level cloud configuration.

---

## 📦 Available Formulae

| Formula   | Description | Tool URL | Install Command |
|----------|-------------|----------|----------------|
| snip     | SNIP - Search, Navigate, Index, Parse | `https://github.com/yindia/snip` | `brew install yindia/homebrew-yindia/snip` |
| rootcause| RootCause is a local-first MCP server that helps operators manage Kubernetes resources and identify the real root cause of failures through interoperable toolsets. | `https://github.com/yindia/rootcause` | `brew install yindia/homebrew-yindia/rootcause` |
| pltf     | The next generation of Infrastructure-as-Code. Work with high-level constructs instead of getting lost in low-level cloud configuration. | `https://github.com/yindia/pltf` | `brew install yindia/homebrew-yindia/pltf` |

Note: add `Formula/pltf.rb` to publish the pltf formula in this tap.

---

## 🚀 Installation

### 1. Add this tap

```bash
brew tap yindia/homebrew-yindia
```

### 2. Install tools

Install individual tools:

```bash
brew install yindia/homebrew-yindia/snip
brew install yindia/homebrew-yindia/rootcause
brew install yindia/homebrew-yindia/pltf
```

Or install all:

```bash
brew install snip rootcause pltf
```

---

## 🔄 Upgrade tools

```bash
brew update
brew upgrade
```

Upgrade specific tool:

```bash
brew upgrade snip
```

---

## 📁 Repository Structure

```
.
├── Formula/
│   ├── pltf.rb
│   └── snip.rb
│   └── rootcause.rb
└── README.md
```

---

## 🛠 Development

After modifying or adding a formula:

```bash
git add Formula/<formula>.rb
git commit -m "Add or update <formula>"
git push
```

Refresh locally:

```bash
brew update
brew upgrade
```

---

## 🔎 Verify tap is working

```bash
brew tap
brew search yindia/homebrew-yindia
```
