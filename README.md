# HCPS – Historical Combat Performance Simulator

A GPT-powered ensemble model and Monte Carlo simulation built to rank 130+ warriors from the Three Kingdoms and post-Han era based on 1v1 combat effectiveness.

This project blends historical analysis, AI modeling, and statistical methods to produce a composite warrior ranking with percentile normalization and integrity controls.

## 🔍 Core Features
- 🛡️ Trait-based scoring system across 12 combat categories (e.g., Offense, Agility, Fight IQ)
- 🧠 GPT-audited rating system using randomized logic-gated prompts
- 🎲 Monte Carlo simulation layer with 30 trial iterations
- 📊 Percentile-normalized score aggregation (peak, top-10 frequency, volatility)
- ✅ Integrity-adjusted rankings with feedback loop auditing

## 📂 File Overview
- `Ultimate Dynasty Warriors.xlsx` — Core dataset, rankings, and score breakdowns
- `Overview.xlsx` — Summary and normalization logic
- `Ultimate Warrior Audit Prompt.docx` — GPT-based audit template
- `Ultimate Dynasty Warrior Prompt.docx` — 1v1 duel simulation template

## 🧪 Status
Actively refining metrics, adjusting weights, and expanding validation methods.

## Rating Methodology Overview

The HCPS rating system blends historical records with simulation feedback to produce consistent, evidence-weighted combat scores for each warrior. We analyzed distribution shapes across all traits, adjusted for duel presence, formation roles, age, and temperament caps. The result is a battle-tested framework grounded in repeatable logic — not just fan impressions.

Key features:
- Statistical sanity checks (skew, bimodal curves, outlier detection)
- Duel receipt modifiers for Finishing Instinct and Weapon Skill
- Formation role penalties to balance linebreakers vs. duelists
- Age-based decline logic for stamina, agility, and durability
- Capped temperament bonus to avoid personality overboosting

💡 All logic and formulas are fully documented in [`docs/methodology.md`](./docs/methodology.md).

