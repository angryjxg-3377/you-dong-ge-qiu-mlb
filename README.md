# ⚾ you-dong-ge-qiu-mlb

> OpenClaw Skill · YDGQ MLB Tipster v1.0

**The most comprehensive AI MLB betting analysis skill available today** — covering 10 bet types, all 30 MLB teams + Minor Leagues, and a 15-factor proprietary model built specifically for baseball.

---

**YDGQ** = 你懂个球 (Nǐ Dǒng Gè Qiú)

Three layers of meaning:
- **Literal**: "You know baseball" — yes, with data you actually do
- **Slang**: "You know absolutely nothing" — a brutal reminder that baseball humbles everyone
- **The twist**: The AI doesn't really know either — but data-backed guesses beat blind ones

*The name that mocks the user, mocks itself, and still tries to help.* ⚾

Your mate swears the Dodgers always cover with a lefty on the mound.
YDGQ checks the wind direction at Yankee Stadium, the umpire's
strike zone, and whether the bullpen is overworked —
at machine speed.

---

## Why MLB Needs Its Own Skill

MLB betting has unique dynamics that no other sport shares:

| | Soccer | NFL | NBA | MLB |
|---|---|---|---|---|
| Starting pitcher impact | None | None | None | **#1 factor (40%)** |
| Weather importance | Minimal | Moderate | None | **Critical (wind = runs)** |
| Ballpark factor | Minimal | None | None | **Major (Coors vs Petco)** |
| F5 / first half bet | No | No | No | **MLB-unique** |
| NRFI prop | No | No | No | **MLB-unique** |
| Umpire impact | Minimal | None | Moderate | **Significant** |
| Underdog win rate | ~35% | ~37% | ~35% | **~44% — highest** |
| Games per season | 38 | 17 | 82 | **162 — richest data** |

YDGQ MLB is built from the ground up for these differences — especially the wind direction model, F5 analysis, and NRFI probability, which are MLB-exclusive analytical edges.

---

## Features

- **Auto-activation** — Triggered by MLB keywords: "run line", "F5", "NRFI", "starting pitcher", "strikeout props" etc.
- **Full MLB coverage** — All 30 MLB teams, 162-game season through World Series
- **10 bet types** — Moneyline, Run Line, Over/Under, F5, NRFI/YRFI, Player Props, Team Totals, Series Betting, Parlay, Live betting
- **15-factor analysis** — Starting pitcher, bullpen, ballpark factor, wind direction, umpire tendencies, platoon matchups
- **Wind Direction Model** — Automatically calculates run total adjustment based on wind speed and direction
- **Ballpark Adjustment System** — Built-in park factors for all 30 MLB stadiums (Coors +1.5 to Petco -0.7)
- **NRFI Probability Engine** — Dedicated first-inning scoring probability model
- **3 strategies** — Safe / Balanced / Value parlay
- **Auto result check** — Ask "did the under hit?" and Skill checks the final score
- **Bet memory** — Special situation tracking (wind plays, NRFI record, Coors Field performance)
- **Multi-platform** — WhatsApp, Telegram, Discord, Slack, Feishu and more

---

## Installation

```bash
mkdir -p ~/.openclaw/skills/you-dong-ge-qiu-mlb
cp SKILL.md ~/.openclaw/skills/you-dong-ge-qiu-mlb/
```

---

## Get Your Free API Keys

### BALLDONTLIE (Required — Free)

Complete MLB data including every pitcher's stats, every game, with historical data and real-time updates.

1. Go to **https://www.balldontlie.io**
2. Click **Sign Up** → verify email
3. Copy your API Key from the dashboard
4. Run:

```bash
openclaw config set ydgq.balldontlie_key YOUR_KEY_HERE
```

---

### The Odds API (Recommended — 500 free/month)

MLB odds from DraftKings, FanDuel, BetMGM, Caesars, Bovada and more, including F5 lines and player props.

1. Go to **https://the-odds-api.com**
2. Click **Get API Key** — free, no credit card
3. Run:

```bash
openclaw config set ydgq.odds_api_key YOUR_KEY_HERE
```

---

### OpenWeatherMap (Required for MLB — Free)

⚡ Wind direction is the single biggest non-pitcher factor in MLB totals. This key is more important in MLB than any other sport.

1. Go to **https://openweathermap.org**
2. Sign up → **My API Keys** → copy default key
3. Run:

```bash
openclaw config set ydgq.weather_key YOUR_KEY_HERE
```

**Free tier:** 1000 requests/day — more than enough

---

## Connect Your Platform

```bash
# Telegram
openclaw config set telegram.token YOUR_BOT_TOKEN

# Feishu / Lark
openclaw plugins install @larksuiteoapi/feishu-openclaw-plugin

# Restart gateway
openclaw gateway restart
```

---

## How to Use

```
give me MLB picks for tonight's full slate
Dodgers vs Yankees — under or over?
any good NRFI plays tonight?
F5 picks for today
Glasnow strikeout prop tonight — worth it?
did the under hit last night?
my MLB betting record
```

---

## Legal Notice

MLB sports betting is legal in 38+ US states.

This Skill is an analysis tool only. It does not accept wagers.

**Bet responsibly:**
- US: National Problem Gambling Helpline — 1-800-522-4700
- Canada: ConnexOntario — 1-866-531-2600
- Global: [Gamblers Anonymous](https://www.gamblersanonymous.org)

Minimum legal betting age: 21 in most US states. Not for use by minors.

---

## The YDGQ Family

| Skill | Sport | Markets |
|-------|-------|---------|
| [you-dong-ge-qiu-football-oracle](https://github.com/angryjxg-3377/you-dong-ge-qiu-football-oracle) | ⚽ Soccer (China) | Chinese Sports Lottery |
| [you-dong-ge-qiu-tipster](https://github.com/angryjxg-3377/you-dong-ge-qiu-tipster) | ⚽ Soccer (Global) | International betting |
| [you-dong-ge-qiu-nfl](https://github.com/angryjxg-3377/you-dong-ge-qiu-nfl) | ⚡ NFL + CFB | US football betting |
| [you-dong-ge-qiu-nba](https://github.com/angryjxg-3377/you-dong-ge-qiu-nba) | 🏀 NBA + NCAA | US basketball betting |
| **you-dong-ge-qiu-mlb** | ⚾ MLB | US baseball betting |

---

## License

MIT · Fork freely · PRs welcome

*你懂个球 (Nǐ Dǒng Gè Qiú) — Chinese slang: "You know absolutely nothing about baseball." ⚾*
