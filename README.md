# Tristan — League of Legends Scouting Report

Interactive player scouting report built with Python and the Riot Games API.

**Live site:** https://shinariii.github.io/scout-tristan/

---

## Player

- **IGN:** worker co ops#mybad
- **Rank:** Masters
- **Role:** Top Lane
- **Region:** NA
- **Sample:** 50 ranked solo/duo games (Patch 16.10)

---

## Charts

**Champion Pool** — Win rate and key stats by champion, color coded from red to green.

**Gold Diff at 10 by Champion** — Average gold advantage or deficit at 10 minutes per champion, pulled from match timeline data.

**KDA Trend** — KDA across last 50 ranked games with win/loss color coding per game.

**Kill Participation Trend** — Team fight involvement across last 50 games.

**Damage vs CS/min** — Resource efficiency scatter showing how well the player converts farm into damage output.

**Performance Radar** — Overall player profile across KDA, CS/min, damage, kill participation, and gold-to-damage efficiency.

---

## Key Findings

- Strong early laner — positive gold diff at 10 on most champions
- Best champion is Rumble (77.8% win rate, 9 games)
- Jayce shows a lead conversion problem — +326 gold at 10 but only 33% win rate
- Renekton anomaly — loses lane (-570 gold at 10) but wins games at 66.7%

---

## Methodology

Data pulled via Riot Games API. Match timeline data used for gold diff at 10. All stats normalized per minute to account for game length variance.

---

## Tools

Python · Pandas · Plotly · Riot Games API · Google Colab
