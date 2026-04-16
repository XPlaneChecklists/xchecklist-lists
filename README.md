# X-Plane XChecklist Community Repository

A centralized library of `clist.txt` files for use with the XChecklist plugin in X-Plane.

## ✈️ What is this?

This repository provides ready-to-use checklists for aircraft in X-Plane, designed for compatibility with the XChecklist plugin.

Each checklist is tailored to a specific aircraft add-on and follows a consistent structure so users can quickly find and install the correct file.

## 📂 Repository Structure

Checklists are organized as follows:

```

/<studio>/<icao>/<variant>/clist.txt

```

### Definitions

- **studio** — Aircraft developer (e.g., `laminar`, `toliss`, `zibo`)
- **icao** — ICAO aircraft code (e.g., `a320`, `b738`)
- **variant** — Specific model or mod (e.g., `a320neo`, `b737-800x`)

### Example

```

/toliss/a320/a320neo/clist.txt
/zibo/b738/b737-800x/clist.txt

```

## 🚀 Installation

1. Locate your aircraft folder in X-Plane:
```

X-Plane/Aircraft/<Your Aircraft>/

```

2. Download the appropriate `clist.txt` from this repository.

3. Place the file in the aircraft’s root directory (same folder as `.acf` file).

4. Launch X-Plane and open XChecklist.

## 🧭 Guidelines

- Checklists should reflect the aircraft’s actual systems and flows.
- Prefer real-world procedures where applicable.
- Keep steps clear, concise, and compatible with XChecklist formatting.

## 🤝 Contributing

We welcome contributions from the community.

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request.

## ⚠️ Disclaimer

These checklists are community-created and may not perfectly reflect real-world procedures. Use at your own discretion.
