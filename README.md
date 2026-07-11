# awesome-football

A collection of awesome football (national teams, clubs, match schedules, players, stadiums, etc.) datasets

**Contributions welcome. Anything missing? Send in a pull request. Thanks.**

---

# Awesome Football (Open Datasets & Open Source Apps)

## V3 - What's News in 2026?

### World Cup 2026
- [Onside World Cup 2026 model outputs](https://onsidearena.com/data) - model predictions (open data); per-match win/draw probabilities, champion odds (10,000-run Monte Carlo simulation) and the full 104-match schedule as CC BY 4.0 CSVs, refreshed through the tournament; includes a [public graded accuracy record](https://onsidearena.com/world-cup-2026/model-record) and a [Kaggle mirror](https://www.kaggle.com/datasets/wr0027/world-cup-2026-predictions-onside-model-outputs)

- [uanalyse World Cup 2026 predictions](https://github.com/uanalyse/world-cup-2026-predictions) - daily, timestamped forecasts published before kickoff; per-match win/draw/loss probabilities and expected goals, plus tournament probabilities (reach each stage, champion) from a 10,000-run Monte Carlo group stage with the knockout bracket solved exactly by dynamic programming (computed, not sampled). Append-only, signed CC BY 4.0 CSVs, refreshed daily through the tournament, with a live [interactive portal](https://uanalyse.co.uk/world-cup-2026). Widely used: 300+ repo clones in two weeks, plus independent bracket and Kicktipp projects building on it.

- [World Cup AI Forecast](https://worldcupaiforecast.com/) - multilingual World Cup 2026 forecast and analysis dashboard with match win probabilities, score predictions, group standings, lineup notes, completed-match backtesting, transparent [methodology](https://worldcupaiforecast.com/methodology-en.html) and [data-source notes](https://worldcupaiforecast.com/data-sources-en.html). Entertainment-only informational analytics.
- [FootyTips World Cup backtest](https://github.com/tuofangzhe/footytips-worldcup-backtest) - reproducible backtest of an open Elo + Poisson (Dixon-Coles) model across all 22 World Cups (1930-2022, 964 matches): 56.6% win/draw/loss hit rate, replayed walk-forward from the CC0 [martj42 dataset](https://github.com/martj42/international_results) with no future data. ~250 lines, zero dependencies, `npm run backtest` reproduces the numbers; live 2026 picks [settled publicly](https://footytips.io/track-record/) after each match, including the misses.

- [World Cup 2026 Tour schedule dataset](https://ay-worldcup2026.zeabur.app/dataset) - all 104 fixtures with UTC kickoff times, match pages, CSV/JSONL snapshots, a free local-time JSON API, OpenAPI spec, ICS calendar feed, and [Hugging Face](https://huggingface.co/datasets/abaiii168/world-cup-2026-tour-match-schedule) / [Kaggle](https://www.kaggle.com/datasets/ayworldcup2026/world-cup-2026-tour-match-schedule) mirrors.

- [World Cup 2026 Player Data](https://github.com/risingtransfers/world-cup-2026-data) - all 48 squads (1363 players) with per-90 stats and AI player similarity examples. CC BY 4.0.

- [WC2026 Live Tracker](https://github.com/Krymets/wc2026) - Live scores, goals & cards by minute, group standings, knockout bracket and player stats for all 104 matches. Single HTML file, no dependencies, auto-updates via ESPN API.

- [lefProg/claudial](https://github.com/lefProg/claudial) - a small fun project that lets you see live updates for the 2026 World Cup right in your Claude Code status line.

- [TopScorers World Cup 2026](https://www.top-scorers.com/en/mundial-2026) - live top scorers, assists and the Golden Boot race for the 2026 World Cup, plus group standings, results and the full 104-match schedule. Bilingual (EN/ES), free, no signup.

## V2 - What's News in 2022?

[**jfjelstul/worldcup**](https://github.com/jfjelstul/worldcup)

The Fjelstul World Cup Database is a comprehensive database about the FIFA World Cup created by Joshua C. Fjelstul, Ph.D. that covers all `21` World Cup tournaments (1930-2018). An update with data on the 2022 World Cup in Qatar will be available soon. The database includes `27` datasets (approximately 1.1 million data points) that cover all aspects of the World Cup.

[**JaseZiv/worldfootballR**](https://github.com/JaseZiv/worldfootballR)

This package is designed to allow users to extract various world
football results and player statistics from the following popular
football (soccer) data sites:

- FBref
- [Transfermarkt](https://www.transfermarkt.com/)
- [Understat](https://understat.com/)
- [Fotmob](https://www.fotmob.com/)

Since the release of `v0.5.3`, the library now supports very rapid
loading of pre-collected data through the use of `load_` functions.

The data available for loading is stored in the `worldfootballR_data`
repository. The repo can be found
[here](https://github.com/JaseZiv/worldfootballR_data).

[**dcaribou/transfermarkt-datasets**](https://github.com/dcaribou/transfermarkt-datasets)

this project aims for three things:

1. Acquire data from transfermarkt website using the [trasfermarkt-scraper](https://github.com/dcaribou/transfermarkt-scraper).
2. Build a **clean, public football (soccer) dataset** using data in 1.
3. Automatate 1 and 2 to **keep these assets up to date** and publicly available on some well-known data catalogs.

Checkout this dataset also in: 
[Kaggle](https://www.kaggle.com/davidcariboo/player-scores), 
[data.world](https://data.world/dcereijo/player-scores),
[streamlit](https://transfermarkt-datasets.herokuapp.com/), 
[awesome-public-datasets](https://github.com/awesomedata/apd-core/blob/master/core/Sports/Transfermarkt-Datasets.yml)

[**somdeep/Statball**](https://github.com/somdeep/Statball)

Football (soccer) stats analyser from top 5 european leagues with data obtained from Fbref and Statsbomb.

Fbref : https://fbref.com/en/comps/Big5/Big-5-European-Leagues-Stats

Statsbomb : https://statsbomb.com/

[**probberechts/soccerdata**](https://github.com/probberechts/soccerdata)

SoccerData is a collection of wrappers over soccer data from `Club Elo`_,
`ESPN`_, `FBref`_,
`FiveThirtyEight`_, `Football-Data.co.uk`_, `SoFIFA`_ and
`WhoScored`_. You get Pandas DataFrames with sensible, matching column names
and identifiers across datasets. Data is downloaded when needed and cached
locally.

To learn how to install, configure and use SoccerData, see the
`Quickstart guide <https://soccerdata.readthedocs.io/en/latest/usage.html>`__. For documentation on each of the
supported data sources, see the `example notebooks <https://soccerdata.readthedocs.io/en/latest/datasources/>`__ and `API reference <https://soccerdata.readthedocs.io/en/latest/reference/>`__.

## V1 - Before 2022

Note: :octocat: stands for the GitHub page and :gem: stands for the RubyGems page.

## Football Data Guides / Articles

_Where's the open football data?_

- [Guide to Football Data and APIs](http://www.jokecamp.com/blog/guide-to-football-and-soccer-data-and-apis/) - The Definite Football Data List collected by Joe Kampschmid  
- [Article: Using open football data - Get ready for the World Cup in Brazil 2014 @ The Data Wrangling Blog (Open Knowledge Foundation (OKFN) Labs)](http://okfnlabs.org/blog/2014/05/06/open-data-world-cup.html) by Gerald Bauer

## Football Datasets

### World Cup

- [openfootball/world-cup :octocat:](https://github.com/openfootball/world-cup)
- [import-io/worldcup2014 :octocat:](https://github.com/import-io/worldcup2014)
- [estiens/world_cup_json :octocat:](https://github.com/estiens/world_cup_json)
- [sanand0/fifadata :octocat:](https://github.com/sanand0/fifadata)
- [pratapvardhan/FIFAWorldCup :octocat:](https://github.com/pratapvardhan/FIFAWorldCup)

### England

- [engsoccerdata :octocat:](https://github.com/jalapic/engsoccerdata)

### Misc

- [jokecamp/FootballData :octocat:](https://github.com/jokecamp/FootballData)
- [llimllib/soccerdata :octocat:](https://github.com/llimllib/soccerdata)
- [milkysunshine91/sport_db.Football :octocat:](https://github.com/milkysunshine91/sport_db.Football)
- [orlandoaleman/FootballAppResources :octocat:](https://github.com/orlandoaleman/FootballAppResources)
 
## Stadium Datasets

- [openfootball/stadiums :octocat:](https://github.com/openfootball/stadiums)

## ⚽ Football Culture & Fan Experiences

_Non-league (National League and below) match day culture, traditions, and community discussions — the human side of football._

- **[NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)** — Comprehensive research summary covering 13 core match day traditions, the "3 A's" framework (Affordability, Accessibility, Accountability), cost comparisons, fan sentiment, community platforms, regional variations, and a curated reading list. Dedicated to the **public domain**.

### Key Highlights

| Dimension | Non-League | Premier League |
|-----------|-----------|---------------|
| **Affordability** | £5–£15 tickets; entire season ~£110–£330 | £30–£100+ tickets; entire season ~£990–£2,860+ |
| **Accessibility** | Walk-on gate, 20 min before kick-off | Book ahead, queues 45+ minutes |
| **Accountability** | Volunteer-run; chairman knows your name; transparent finances | Anonymous PLC ownership; outsourced stewarding; opaque finances |

### 13 Core Match Day Traditions

| # | Tradition | Description |
|---|-----------|-------------|
| 1 | **The Pub Signal** | Pre-match pub gatherings where the community converges; specific pubs are club-associated |
| 2 | **Intimate Grounds** | Small terraced stadiums with pitchside proximity (500–5,000 capacity); hear the manager's instructions from the stands |
| 3 | **Freedom of the Terrace** | Open standing, no assigned seats; fans change ends at half-time; no VAR delays or barriers |
| 4 | **The Clubhouse / Social Club** | Volunteer-run canteen/bar; £2–3 pints; fans, officials, and players mingle freely |
| 5 | **Pie, Mash & Gravy ("Footy Scran")** | Legendary local bakery pies (£3–4); steak and ale is the classic; artisan bakery partnerships |
| 6 | **Physical Programme** | £2–3 paper collectibles with local history, manager notes, player interviews; direct financial support |
| 7 | **Volunteer Spirit** | Fans steward, serve refreshments, maintain the pitch; community-owned clubs; "the chairman knows your name" |
| 8 | **Local Rivalries** | Deep-rooted geographic derbies with centuries of history; passed down through generations |
| 9 | **Chants & Songs** | Organic, locally-written songs unique to each club; multi-generational; no two clubs sing the same way |
| 10 | **Family Inclusion** | Kids roam freely between stands; £7 family tickets; relaxed atmosphere; "bring your dad" culture |
| 11 | **The Conference Legacy (1979–2004)** | Community ethos from the era of the Football Conference; self-governance as standard |
| 12 | **Non-League Day** | Annual open-doors event during international breaks; 15th anniversary in 2026, founded 2010 |
| 13 | **Post-Match Socialising** | 4–6 hour match day rituals; clubhouse stays open after the final whistle; result is secondary |

### Fan Voices

> *"Walking into a non-league ground for the first time, I felt like I'd walked into someone's living room. Everyone said hello."* — r/nonleaguefootball

> *"For the price of one PL programme, you can go to 10 non-league grounds."* — r/CasualUK

> *"Nobody clocks you in. You just turn up. That's the point."* — r/nonleaguefootball

> *"The social club is where the real football happens. The 90 minutes is just an excuse."* — r/nonleague

### Where Fans Discuss Match Day Culture

- **Reddit**: r/nonleaguefootball (30k+), r/nonleague (40k+), r/NationalLeague (15k+), r/CasualUK (3M+)
- **Forums**: NonLeagueMatters, Nonleaguezone.co.uk, Football Fanbase Forum
- **Publications**: The Non-League Football Paper (2026), Football Ground Guide, When Saturday Comes, Lower Block
- **Research**: ShuttleOne Network / Energeo (2025)
- **Organisations**: FSA Away Day Experience Awards 2025, Football Ground Guide

### Notable Recognition (2025–2026)

- **FSA Away Day Experience Award 2025**: Falmouth Town AFC
- **FG Guide "Best Away Days 2026"**: Falmouth Town, FC Halifax Town, Torquay United, Farnham Town, Lewes FC
- **"Perfect Matchday" guide** (Feb 2026): The Non-League Football Paper
- **LiveScore Survey 2026**: 55% of PL fans open to attending N*L matches

→ See **[NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)** for the full research document.

## Football Apps

_Open source apps for match scores, picks, predictions, office pools, and more_