Awesome Series @ Planet Open Data

[World (Countries, Cities, Codes, ...)](https://github.com/planetopendata/awesome-world) •
[Football (Clubs, Players, Stadiums, ...)](https://github.com/planetopendata/awesome-football) •
[SQLite (Tools, Books, Schemas, ...)](https://github.com/planetopendata/awesome-sqlite)


# Awesome Football   (Open Datasets & Open Source Apps)

A collection of awesome football (national teams, clubs, match schedules, players, stadiums, etc.) datasets

**Contributions welcome. Anything missing? Send in a pull request. Thanks.**

## V3 -  What's News in 2026?

### World Cup 2026 
- [Onside World Cup 2026 model outputs](https://onsidearena.com/data) - model predictions (open data); per-match win/draw probabilities, champion odds (10,000-run Monte Carlo simulation) and the full 104-match schedule as CC BY 4.0 CSVs, refreshed through the tournament; includes a [public graded accuracy record](https://onsidearena.com/world-cup-2026/model-record) and a [Kaggle mirror](https://www.kaggle.com/datasets/wr0027/world-cup-2026-predictions-onside-model-outputs)

- [uanalyse World Cup 2026 predictions](https://github.com/uanalyse/world-cup-2026-predictions) - daily, timestamped forecasts published before kickoff; per-match win/draw/loss probabilities and expected goals, plus tournament probabilities (reach each stage, champion) from a 10,000-run Monte Carlo group stage with the knockout bracket solved exactly by dynamic programming (computed, not sampled). Append-only, signed CC BY 4.0 CSVs, refreshed daily through the tournament, with a live [interactive portal](https://uanalyse.co.uk/world-cup-2026). Widely used: 300+ repo clones in two weeks, plus independent bracket and Kicktipp projects building on it.

- [World Cup AI Forecast](https://worldcupaiforecast.com/) - multilingual World Cup 2026 forecast and analysis dashboard with match win probabilities, score predictions, group standings, lineup notes, completed-match backtesting, transparent [methodology](https://worldcupaiforecast.com/methodology-en.html) and [data-source notes](https://worldcupaiforecast.com/data-sources-en.html). Entertainment-only informational analytics.
- [FootyTips World Cup backtest](https://github.com/tuofangzhe/footytips-worldcup-backtest) - reproducible backtest of an open Elo + Poisson (Dixon-Coles) model across all 22 World Cups (1930-2022, 964 matches): 56.6% win/draw/loss hit rate, replayed walk-forward from the CC0 [martj42 dataset](https://github.com/martj42/international_results) with no future data. ~250 lines, zero dependencies, `npm run backtest` reproduces the numbers; live 2026 picks [settled publicly](https://footytips.io/track-record/) after each match, including the misses.

- [World Cup 2026 Tour schedule dataset](https://ay-worldcup2026.zeabur.app/dataset) - all 104 fixtures with UTC kickoff times, match pages, CSV/JSONL snapshots, a free local-time JSON API, OpenAPI spec, ICS calendar feed, and [Hugging Face](https://huggingface.com/datasets/abaiii168/world-cup-2026-tour-match-schedule) / [Kaggle](https://www.kaggle.com/datasets/ayworldcup2026/world-cup-2026-tour-match-schedule) mirrors.

- [World Cup 2026 Player Data](https://github.com/risingtransfers/world-cup-2026-data) - all 48 squads (1363 players) with per-90 stats and AI player similarity examples. CC BY 4.0.

- [WC2026 Live Tracker](https://github.com/Krymets/wc2026) - Live scores, goals & cards by minute, group standings, knockout bracket and player stats for all 104 matches. Single HTML file, no dependencies, auto-updates via ESPN API.

- [lefProg/claudial](https://github.com/lefProg/claudial) - a small fun project that lets you see live updates for the 2026 World Cup right in your Claude Code status line.

- [TopScorers World Cup 2026](https://www.top-scorers.com/en/mundial-2026) - live top scorers, assists and the Golden Boot race for the 2026 World Cup, plus group standings, results and the full 104-match schedule. Bilingual (EN/ES), free, no signup.

## V2 -  What's News in 2022?

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

The data available for loading is stored in the `worldfootballR_data` repository. The repo can be found
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
`ESPN`_,
`FBref`_,
`FiveThirtyEight`_,
`Football-Data.co.uk`_,
`SoFIFA`_ and
`WhoScored`_. You get Pandas DataFrames with sensible, matching column names
and identifiers across datasets. Data is downloaded when needed and cached
locally.

To learn how to install, configure and use SoccerData, see the
`Quickstart guide <https://soccerdata.readthedocs.io/en/latest/usage.html>`__. For documentation on each of the
supported data sources, see the `example notebooks <https://soccerdata.readthedocs.io/en/latest/datasources/>`__ and `API reference <https://soccerdata.readthedocs.io/en/latest/reference/>`__.



## V1  - Before 2022

Note: :octocat: stands for the GitHub page and :gem: stands for the RubyGems page.


## Football Data Guides / Articles

_Where's the open football data?_

- [Guide to Football Data and APIs](http://www.jokecamp.com/blog/guide-to-football-and-soccer-data-and-apis/) - The Definite Football Data List collected by Joe Kampschmid  
- [Article: Using open football data - Get ready for the World Cup in Brazil 2014 @ The Data Wrangling Blog (Open Knowledge Foundation (OKFN) Labs)](http://okfnlabs.org/blog/2014/05/06/open-data-world-cup.html) by Gerald Bauer

## Football Datasets

### World Cup

- [openfootball/world-cup :octocat:](https://github.com/openfootball/world-cup)
- [import-io/worldcup2014 :octocat:](https://github.com/import-io/worldcup2014) - World cup data
- [estiens/world_cup_json :octocat:](https://github.com/estiens/world_cup_json) - rails backend for a scraper that outputs World Cup data as JSON
- [sanand0/fifadata :octocat:](https://github.com/sanand0/fifadata) - scraping FIFA world cup data
- [pratapvardhan/FIFAWorldCup :octocat:](https://github.com/pratapvardhan/FIFAWorldCup) - FIFA World Cup data includes teams data, squad formations, clubs dominance

### England

- [engsoccerdata :octocat:](https://github.com/jalapic/engsoccerdata) - all top 4 tier football matches in England 1888-2014; collected by James Curley

### Misc

- [jokecamp/FootballData :octocat:](https://github.com/jokecamp/FootballData) - a hodgepodge of JSON and CSV football data
- [llimllib/soccerdata :octocat:](https://github.com/llimllib/soccerdata) - a collection of soccer results
- [milkysunshine91/sport_db.Football :octocat:](https://github.com/milkysunshine91/sport_db.Football) - general purpose football database
- [orlandoaleman/FootballAppResources :octocat:](https://github.com/orlandoaleman/FootballAppResources)
 

## Stadium Datasets

- [openfootball/stadiums :octocat:](https://github.com/openfootball/stadiums)


## ⚽ Football Culture & Fan Experiences

_Community-driven documentation on match day traditions, fan culture, and the non-league experience. New for 2026: National League & wider non-league coverage._

### Overview: The 3 A's of Non-League Football

| Principle | What It Means |
|-----------|---------------|
| **Affordability** | A full away day costs £25–44 (vs £70–148 in the Premier League) — a 4–8× saving |
| **Accessibility** | Walk-on gates, no ticket lotteries, no membership queues — just turn up |
| **Accountability** | The chairman sits next to you; the manager is in the bar at full time |

<details>
<summary><b>📄 Click to expand: Full research document (NON-LEAGUE-MATCHDAY-CULTURE.md)</b></summary>

[📄 **NON-LEAGUE-MATCHDAY-CULTURE.md**](NON-LEAGUE-MATCHDAY-CULTURE.md) — Comprehensive guide covering:

- **The 3 A's Framework** — Affordability, Accessibility, Accountability
- **13 Core Match Day Traditions** — From The Pub Signal to The Loyalty Cycle
- **The Perfect Match Day Sequence** — Full 11:00 AM to 5:00 PM timeline ritual
- **Fan Sentiment Highlights** (2024–2026) — Quotes from Reddit and specialist publications
- **Cost Comparison** — Non-league is 4–8× cheaper than the Premier League
- **Regional Variations** — North of England, Midlands, South/SW, London, Scotland
- **Community Discussion Platforms** — Reddit communities, forums, and publications directory
- **Notable Recognition** (2025–2026) — FSA Awards, FGG rankings, LiveScore survey data
- **Top 5 Recommended Away Days for 2026** — Falmouth Town, Halifax, Torquay, Farnham, Lewes
- **Full Source Bibliography** — 13+ cited sources
</details>

### Key Fan Culture at a Glance

| Metric | Value |
|--------|-------|
| Average non-league away day cost | £25–44 |
| Average Premier League away day cost | £70–148 |
| Non-league is ___times cheaper___ | 4–8× |
| PL fans open to non-league (2026) | 55% (up from 49% in 2025) |
| Non-league fans attending in person | 73% (vs 21% for PL fans) |
| r/nonleaguefootball members | 30,000+ (up 40% since 2024) |
| Non-League Day 2026 | **15th anniversary** (28th March) |

#### Fan Voices

> *"Non-league football forges a connection you simply don't find in the top divisions. It has nothing to do with glory or riches. It's about belonging."* — The Non-League Football Paper

> *"The best part of the non-league experience is the freedom of movement. Most grounds allow you to stand wherever you like."* — The Non-League Football Paper

> *"It's a local thing. Non-league clubs aren't just based in communities, they are communities."* — The Non-League Football Paper

### Where Supporters Discuss Match Days

| Community | Platform | Members |
|-----------|----------|---------|
| [r/nonleaguefootball](https://www.reddit.com/r/nonleaguefootball) | Reddit | 30,000+ |
| [r/nonleague](https://www.reddit.com/r/nonleague) | Reddit | 40,000+ |
| [r/NationalLeague](https://www.reddit.com/r/NationalLeague) | Reddit | 15,000+ |
| [NonLeagueMatters](https://nonleaguematters.co.uk) | Forum | Long-running UK non-league forum |
| [TheFans.io](https://thefans.io) | Forum | Non-league fan community |
| [Football Fanbase Forum](https://www.footballfanbase.com/forum) | Forum | UK-wide non-league discussion |
| [The Non-League Football Paper](https://www.thenonleaguefootballpaper.com) | Publication | Daily coverage since 2025 |
| [Football Ground Guide](https://footballgroundguide.com) | Guide | Away day guides & best ground rankings |
| [Non League Chat (Facebook)](https://www.facebook.com/groups/nonleaguechat) | Facebook | 30,000+ members |
| [Lower Block](https://lowerblock.com) | Publication | Non-league culture features |

### Notable Recognition (2025–2026)

- 🏅 **FSA Away Day Experience 2025**: Falmouth Town AFC
- ⭐ **FGG Best Away Days 2026**: Falmouth Town, FC Halifax Town, Torquay United, Farnham Town, Lewes FC
- 📅 **Non-League Day 2026**: 15th anniversary (28th March); Premier League investing £23.6M into National League + £207M into 1,000+ grassroots clubs via Football Foundation
- 📊 **LiveScore NL Fan Survey 2026**: 10-year high attendances for NL South & Isthmian Premier

### Recommended Away Days for 2026

1. **Falmouth Town AFC** (Bickland Park, Step 4) — FSA Award winner, Cornish coast setting, holiday-like atmosphere
2. **FC Halifax Town** (The Shay, National League Premier) — 14,000-capacity classic ground, walkable town centre
3. **Torquay United** (Plainmoor, Nat. League South) — English Riviera, seaside weekend + football
4. **Farnham Town** (Memorial Ground, Step 3) — Innovative pricing, quality food, supporter-first model
5. **Lewes FC** (The Dripping Pan, Isthmian Premier) — Community-owned, locally sourced food, craft beer

### Supporters' 13 Core Match Day Traditions

1. The Pub Signal — Pre-match pub gathering & team news debate
2. The Walk to Ground — Communal stroll through town streets
3. The Turnstile Ritual — Paper programme & ticket purchase at the turnstile
4. Pie, Mash & Gravy — The culinary centrepiece of the non-league match day
5. The Social Club / Clubhouse — Volunteer-run community pre-match hub
6. The Terraces — Free-standing, change ends at half-time, pure football
7. Manager's Half-Time Chat — Direct intimacy between manager and fans
8. Post-Match Digestion — Lingering to soak in the atmosphere
9. The Pub Finish — After-game debate in the local pub
10. Away Day Reception — Opponent fans welcomed with hospitality
11. Community Connection — Club *is* the community, not just based there
12. The Loyalty Cycle — Sticking with the team through thick and thin
13. The 12th Man Spirit — Volunteer stewards, groundsmen, and bar staff

<details>
<summary><b>🗺️ Click to expand: Regional Variations</b></summary>

**North of England**: Heartland of non-league; "shuttle bus" tradition for away games; strong terrace culture with songs passed through generations.

**Midlands**: Cape Town, Tamworth, Leamington known for passionate support; traditional social clubs thrive.

**South/South West**: Coastal grounds (Torquay, Falmouth) combine football with seaside holidays; rising attendances.

**London**: Dense network of inner-city and suburban clubs; FA Cup giant-killing culture; diverse, multicultural support.

**Scotland**: SPFL pyramid integration; distinctive terrace songs; strong community connection through youth academies.

For the full 2026 recommended away days list and comprehensive source bibliography, see **[NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)**.
</details>

### Contributing

Non-league match day culture is open to contributions! The awesome-football project welcomes both datasets and community documentation.

- 📌 **How to contribute**: PRs welcome — add a tradition, a quote, or a community link
- 📜 **License**: All content is dedicated to the **public domain** — free to use, share, and build upon
- 📖 **Source materials**: Research from Reddit, The Non-League Football Paper, Football Ground Guide, FSA Awards, and LiveScore NL Fan Survey

---

## Football Apps

_Open source apps for match scores, picks, predictions, office pools, and more_
