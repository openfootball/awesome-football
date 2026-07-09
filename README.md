# README.md
---
## Updating a file in a repo
Path: README.md
Message: Add Football Culture & Fan Experiences section
Updated file: README.md
---

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

- [World Cup 2026 Tour schedule dataset](https://ay-worldcup2026.zeabur.app/dataset) - all 104 fixtures with UTC kickoff times, match pages, CSV/JSONL snapshots, a free local-time JSON API, OpenAPI spec, ICS calendar feed, and [Hugging Face](https://huggingface.co/datasets/abaiii168/world-cup-2026-tour-match-schedule) / [Kaggle](https://www.kaggle.com/datasets/ayworldcup2026/world-cup-2026-tour-match-schedule) mirrors.

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
`ESPN`_, `FBref`_, `FiveThirtyEight`_, `Football-Data.co.uk`_, `SoFIFA`_ and
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

## Football Culture & Fan Experiences

_Non-league football offers some of the most authentic, affordable, and
community-driven match day experiences in English football. This section
celebrates the grassroots culture that makes the sport special._

### 13 Core Match Day Traditions

| # | Tradition | Description |
|---|-----------|-------------|
| 1 | The Pub Signal | Pre-match gatherings at local pubs where fans debate team news and build community |
| 2 | Intimate Grounds | Small stadiums (500–5,000) where supporters are pitchside, not in corporate boxes |
| 3 | Freedom of the Terrace | Open standing, no assigned seats; you can change ends at half-time to follow the ball |
| 4 | The Clubhouse / Social Club | Volunteer-run, affordable, family atmosphere where fans and officials mingle |
| 5 | Pie, Mash & Gravy | Legendary local food — £3–£4 weekend pies directly supporting the club |
| 6 | Physical Programme | Paper programmes as collectible souvenirs; every penny goes to club finances |
| 7 | Volunteer Spirit | Clubs run by volunteers; fans often help steward or serve refreshments |
| 8 | Local Rivalries | Decades-old, deeply-rooted geographic derbies, not manufactured for commercial purposes |
| 9 | Chants & Songs | Organic, locally-written songs reflecting community identity, often humorous |
| 10 | Family Inclusion | Children free to roam the ground; £5–£15 tickets welcoming to all ages |
| 11 | The Conference Legacy | Community-over-commercial ethos from the old Football Conference era (1979–2004) |
| 12 | Non-League Day | Annual event opening doors to new supporters during international breaks |
| 13 | Post-Match Socialising | The clubhouse stays open; the social experience continues well past full-time |

### The 3 A's of Non-League Culture

| Principle | Meaning |
|-----------|--------|
| **Affordability** | Match day costs a fraction of Premier League prices — a family of four can attend for under £50 |
| **Accessibility** | Grounds are walkable, queues are short, standing terraces keep you close to the action |
| **Accountability** | Fan voice actually matters at non-league clubs — committees are responsive, meetings are public |

### 8 Golden Tips for New Fans

1. Bring cash — many non-league grounds still don't take cards at the turnstile
2. Buy the programme — it goes straight to club finances
3. Stand on the terrace — experience the game as it was meant to be seen
4. Arrive early — pre-match rituals are half the experience
5. Talk to fans — non-league supporters love sharing their club's story
6. Stay after — the clubhouse continues the match day experience
7. Explore the pyramid — every level has its own character
8. Support locally — your money stays in the community

### Where Fans Discuss Match Day Culture

| Platform | Link | What Fans Discuss |
|----------|------|-------------------|
| r/nonleaguefootball | [Reddit](https://reddit.com/r/nonleaguefootball) | Groundhopping culture, family-friendly stories, match reports |
| r/nonleague | [Reddit](https://reddit.com/r/nonleague) | Broader non-league discussion, culture, community |
| r/NationalLeague | [Reddit](https://reddit.com/r/NationalLeague) | National League-specific match day experiences |
| r/CasualUK | [Reddit](https://reddit.com/r/CasualUK) | Casual fan experiences and non-league recommendations |
| NonLeagueMatters | [Forum](https://nonleaguematters.co.uk) | National League discussion, away day guides, derby coverage |
| Nonleaguezone.co.uk | [Website](https://nonleaguezone.co.uk) | Away day guides, programme collecting |
| The Non-League Football Paper | [Website](https://nonleaguefootballpaper.co.uk) | Match day guides, features ("Perfect Matchday" guide, Feb 2026) |
| Football Ground Guide | [Website](https://www.footballgroundguide.com) | "Best Away Days in Non-League Football" (2026 edition) |
| TheFans.io | [Website](https://thefans.io) | Live stats, ground reviews |
| When Saturday Comes | [Website](https://www.wsc.co.uk) | "Why more fans are turning to non-League" editorial |
| FSA | [Website](https://www.thefsa.com) | Away Day Experience Awards |

### Cost & Accessibility Comparison

| | Non-League | Premier League |
|---|-----------|---------------|
| Ticket | £5–£15 | £30–£70+ |
| Food & Drink | £3–£7 | £8–£20+ |
| Season (20 away) | ~£300 | £1,500–£3,000+ |
| Time to enter | ~20 min | 45+ min |

### Notable Recognition (2025–2026)

- **FSA Away Day Experience Award 2025**: Falmouth Town AFC (Bickland Park) — Overall Winner
- **"Perfect Matchday" guide** — The Non-League Football Paper (February 2026)
- **"From the Clubhouse to the Pitch"** — Non-League Football Paper feature (July 2025)
- **"7 Golden Tips for National League Fans"** — Non-League Football Paper series
- **When Saturday Comes editorial** (Feb 2025): "Why more fans are turning to non-League"
- **Football Ground Guide** 2026 away day guides for National League and below

### Full Documentation

For the complete research guide with the 13 traditions, fan sentiment highlights,
recommended grounds, open data gaps, and a curated reading list, see:
- **[NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)** — Comprehensive research guide
- **[MATCHDAY-CULTURE.md](MATCHDAY-CULTURE.md)** — Quick reference summary

### Contributing

Want to add a local club's match day culture to this section? See the
[Contribution Guide](https://github.com/openfootball/awesome-football) below.

## Football Apps

_Open source apps for match scores, picks, predictions, office pools, and more_