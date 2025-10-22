# 🧠 Nexus Hub Doc

![Vite](https://img.shields.io/badge/Vite-4.5.0-646CFF?logo=vite)
![TypeScript](https://img.shields.io/badge/TypeScript-5.3-blue?logo=typescript)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4-38B2AC?logo=tailwindcss)
![Data Format](https://img.shields.io/badge/Data-JSON%2FTSV%2FCSV-yellow?logo=json)
![License](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-lightgrey?logo=creativecommons)
![Org-Nexicore](https://img.shields.io/badge/Org-Nexicore_Digitals-6A1B9A)
![Ecosystem-Nexus](https://img.shields.io/badge/Ecosystem-Nexus_Hub-1976D2)
[![CI Status](https://github.com/nexicore-digitals/nexus-hub-doc/actions/workflows/ci.yml/badge.svg)](https://github.com/nexicore-digitals/nexus-hub-doc/actions/workflows/ci.yml)

**Nexus Hub Doc** is the living documentation surface for the Nexus ecosystem—covering governance, Echo logic, alliance mechanics, plugin attribution, duel protocols, and contributor roles. It is not a starter kit. It is a cognitive reference space for developers, reviewers, and architects building within the Nexus framework.

---

## 🎯 Purpose

This repo exists to:

- Document every rule, schema, and mechanic in the Nexus ecosystem.
- Provide teachable, reviewable artifacts for contributors and mentors.
- Host static, structured data (JSON, TSV, CSV) rendered via a lightweight Vite + TypeScript app.
- Serve as the canonical source of truth for alliance charters, Echo logic, plugin manifests, and duel outcomes.

---

## 🧱 Tech Stack

- **Vite** + **React** + **TypeScript**
- **TailwindCSS** for styling
- **D3** and **PapaParse** for charts and data parsing
- **Static data**: All logic is driven by structured files (`.json`, `.tsv`, `.csv`)

---

## 📁 Structure

```bash

nexus-hub-doc/
├── public/          # Logos, icons, diagrams
├── src/
│   ├── data/        # JSON, TSV, CSV files
│   ├── components/  # Viewer, Chart, Manifest
│   ├── pages/       # Route-based docs
│   ├── utils/       # Parsers, loaders
│   └── App.tsx
├── index.html
├── vite.config.ts
└── README.md

```

---

## 📊 Data Sources

| File                  | Description |
|-----------------------|-------------|
| `echo-schema.tsv`     | Echo ranks, caps, modifiers |
| `plugins.csv`         | Plugin registry and attribution logic |
| `charters.json`       | Alliance rules and admission logic |
| `duels.csv`           | Duel logs and Echo transfers |
| `governance.json`     | System-wide rules and override flows |

---

## 🧠 Philosophy

- **Barebone-first**: Workers start minimal, earn capabilities through contribution.
- **Echo-aware**: Every action is teachable, reviewable, and emotionally fair.
- **Alliance-driven**: Collaboration is incentivized through currency, reputation, and role evolution.
- **Mentor-respected**: Overrides and promotions are guided by trust and clarity.

---

## 📜 License

This repository is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License**.

> You may share and adapt the material for non-commercial purposes, with attribution and under the same license. This repo is not intended for commercial reuse or repackaging.

---

## 🤝 Contributions

This repo is maintained by the Nexus ecosystem. Contributions are welcome but must align with the cognitive branding and reviewable clarity of the system. All edits are subject to mentor review.

---

## 🧩 Future Modules

- Plugin Arena
- Echo Trail Visualizer
- Alliance Role Hall
- Duel Replay Viewer
- Contributor Charter
