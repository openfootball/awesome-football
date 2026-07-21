# Awesome Football   (Open Datasets & Open Source Apps)

A collection of awesome football (national teams, clubs, match schedules, players, stadiums, etc.) datasets

**Contributions welcome. Anything missing? Send in a pull request. Thanks.**

## V3 — What's News in 2026?

### World Cup 2026
- [Onside World Cup 2026 model outputs](https://onsidearena.com/data) — model predictions (open data); per-match win/draw probabilities, champion odds (10,000-run Monte Carlo simulation) and the full 104-match schedule as CC BY 4.0 CSVs, refreshed through the tournament; includes a [public graded accuracy record](https://onsidearena.com/world-cup-2026/model-record) and a [Kaggle mirror](https://www.kaggle.com/datasets/wr0027/world-cup-2026-predictions-onside-model-outputs)
- [uanalyse World Cup 2026 predictions](https://github.com/uanalyse/world-cup-2026-predictions) — daily, timestamped forecasts published before kickoff; per-match win/draw/loss probabilities and expected goals, plus tournament probabilities (reach each stage, champion) from a 10,000-run Monte Carlo group stage with the knockout bracket solved exactly by dynamic programming (computed, not sampled). Append-only, signed CC BY 4.0 CSVs, refreshed daily through the tournament, with a live [interactive portal](https://uanalyse.co.uk/world-cup-2026).
- [World Cup AI Forecast](https://worldcupaiforecast.com/) — multilingual World Cup 2026 forecast and analysis dashboard with match win probabilities, score predictions, group standings, lineup notes, completed-match backtesting, transparent [methodology](https://worldcupaiforecast.com/methodology-en.html) and [data-source notes](https://worldcupaiforecast.com/data-sources-en.html).
- [FootyTips World Cup backtest](https://github.com/tuofangzhe/footytips-worldcup-backtest) — reproducible backtest of an open Elo + Poisson (Dixon-Coles) model across all 22 World Cups (1930–2022, 964 matches): 56.6% win/draw/loss hit rate, replayed walk-forward from the CC0 [martj42 dataset](https://github.com/martj42/international_results) with no future data. ~250 lines, zero dependencies, `npm run backtest` reproduces the numbers; live 2026 picks settled publicly after each match.
- [World Cup 2026 Tour schedule dataset](https://ay-worldcup2026.zeabur.app/dataset) — all 104 fixtures with UTC kickoff times, match pages, CSV/JSONL snapshots, a free local-time JSON API, OpenAPI spec, ICS calendar feed, and [Hugging Face](https://huggingface.co/datasets/abaiii168/world-cup-2026-tour-match-schedule) / [Kaggle](https://www.kaggle.com/datasets/ayworldcup2026/world-cup-2026-tour-match-schedule) mirrors.
- [World Cup 2026 Player Data](https://github.com/risingtransfers/world-cup-2026-data) — all 48 squads (1363 players) with per-90 stats and AI player similarity examples. CC BY 4.0.
- [WC2026 Live Tracker](https://github.com/Krymets/wc2026) — Live scores, goals & cards by minute, group standings, knockout bracket and player stats for all 104 matches. Single HTML file, no dependencies, auto-updates via ESPN API.
- [lefProg/claudial](https://github.com/lefProg/claudial) — a small fun project that lets you see live updates for the 2026 World Cup right in your Claude Code status line.
- [TopScorers World Cup 2026](https://www.top-scorers.com/en/mundial-2026) — live top scorers, assists and the Golden Boot race for the 2026 World Cup, plus group standings, results and the full 104-match schedule. Bilingual (EN/ES), free, no signup.

## V2 — What's News in 2022?

[**jfjelstul/worldcup**](https://github.com/jfjelstul/worldcup)

The Fjelstul World Cup Database is a comprehensive database about the FIFA World Cup created by Joshua C. Fjelstul, Ph.D. that covers all `21` World Cup tournaments (1930–2018). An update with data on the 2022 World Cup in Qatar will be available soon. The database includes `27` datasets (approximately 1.1 million data points) that cover all aspects of the World Cup.

[**JaseZiv/worldfootballR**](https://github.com/JaseZiv/worldfootballR)

This package is designed to allow users to extract various world football results and player statistics from the following popular football (soccer) data sites:

- FBref
- [Transfermarkt](https://www.transfermarkt.com/)
- [Understat](https://understat.com/)
- [Fotmob](https://www.fotmob.com/)

Since the release of `v0.5.3`, the library now supports very rapid loading of pre-collected data through the use of `load_` functions. The data available for loading is stored in the `worldfootballR_data` repository. The repo can be found [here](https://github.com/JaseZiv/worldfootballR_data).

[**dcaribou/transfermarkt-datasets**](https://github.com/dcaribou/transfermarkt-datasets)

this project aims for three things:

1. Acquire data from transfermarkt website using the [trasfermarkt-scraper](https://github.com/dcaribou/transfermarkt-scraper).
2. Build a **clean, public football (soccer) dataset** using data in 1.
3. Automatate 1 and 2 to **keep these assets up to date** and publicly available on some well-known data catalogs.

Checkout this dataset also in: [Kaggle](https://www.kaggle.com/davidcariboo/player-scores), [data.world](https://data.world/dcereijo/player-scores), [streamlit](https://transfermarkt-datasets.herokuapp.com/), [awesome-public-datasets](https://github.com/awesomedata/apd-core/blob/master/core/Sports/Transfermarkt-Datasets.yml)

[**somdeep/Statball**](https://github.com/somdeep/statball)

Football (soccer) stats analyser from top 5 european leagues with data obtained from Fbref and Statsbomb.

Fbref : https://fbref.com/en/comps/Big5/Big-5-European-Leagues-Stats
Statsbomb : https://statsbomb.com/

[**probberechts/soccerdata**](https://github.com/probberechts/soccerdata)

SoccerData is a collection of wrappers over soccer data from `Club Elo`, `ESPN`, `FBref`, `FiveThirtyEight`, `Football-Data.co.uk`, `SoFIFA` and `WhoScored`. You get Pandas DataFrames with sensible, matching column names and identifiers across datasets. Data is downloaded when needed and cached locally.

To learn how to install, configure and use SoccerData, see the [Quickstart guide](https://soccerdata.readthedocs.io/en/latest/usage.html). For documentation on each of the supported data sources, see the [example notebooks](https://soccerdata.readthedocs.io/en/latest/datasources/). For API reference, see the [API reference](https://soccerdata.readthedocs.io/en/latest/reference/).

## V1 — Before 2022

Note: :octocat: stands for the GitHub page and :gem: stands for the RubyGems page.

## Football Data Guides / Articles

_Where's the open football data?_

- [Guide to Football Data and APIs](http://www.jokecamp.com/blog/guide-to-football-and-soccer-data-and-apis/) — The Definite Football Data List collected by Joe Kampschmid
- [Article: Using open football data – Get ready for the World Cup in Brazil 2014](http://okfnlabs.org/blog/2014/05/06/open-data-world-cup.html) by Gerald Bauer

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

> **Non-League Match Day Culture & Fan Community Discussions** — A comprehensive guide to National League and wider non-league football match day traditions, community experiences, and fan culture.

📄 Full research document: [NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)

### Why Non-League?

| | Non-League | Premier League |
|---|---|---|
| Full away day cost | £12–27 | £50–130 |
| Cost advantage | **4–8× cheaper** | — |
| Fans attending in person | 73% | 21% |
| PL fans open to NL | 55% | — |
| Walk-on entry | ✅ Yes | ❌ Lottery/membership |

### The 3 A's

- **Affordability** — Tickets from £5, pies from £3, programmes from 20p. Season tickets from £200/year.
- **Accessibility** — No ticket lotteries, no queues. Walk up and go in. Grounds in town centres.
- **Accountability** — Chairman sits beside you. Manager in the bar. Players park where you park.

### 13 Core Match Day Traditions

1. The Pub Signal — Pre-match pub gathering to build communal energy
2. The Walk to the Ground — Pilgrimage-like procession through town
3. The Turnstile Ritual — Paper programme andCoins-in-the-slot gate purchase
4. The Physical Programme — Collectible artefact supporting club finances
5. Pie, Mash & Gravy — Legendary steak-and-ale pies for £3–4
6. The Clubhouse — Volunteer-run social club steps from the pitch
7. The Terraces — Open standing with freedom of movement
8. The Manager's Half-Time Chat — Direct address from the manager
9. The Post-Match Digestion — Lingering to replay key moments
10. The Pub Finish — Post-game debate over pints
11. The Away Day Reception — Welcoming visitors with open arms
12. The Community Connection — The club is your town, your identity
13. The Loyalty Cycle — Celebrating every success as a hard-won victory

### Key Stats at a Glance

| Metric | Value |
|---|---|
| NL away day cost | £12–27 |
| PL away day cost | £50–130 |
| Cost advantage | **4–8× cheaper** |
| NL in-person attendance | 73% |
| PL fans open to NL | 55% |
| r/nonleaguefootball | 30,000+ |

### Top 5 2026 Recommended Away Days

1. 🏆 Falmouth Town AFC — FSA Away Day Experience Award 2025
2. FC Halifax Town — The Shay, 14,000 capacity
3. Torquay United — English Riviera
4. Farnham Town — Town-centre location, innovative pricing
5. Lewes FC — South Downs, community-run

🔗 Full research & sources: [NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)

*All content compiled from open community sources (2024–2026). Dedicated to the **public domain**.*

## Football Apps

_Open source apps for match scores, picks, predictions, office pools, and more_ 

- [worldcup-2014 gem :octocat:](https://github.com/hpoydar/worldcup-2014), [:gem:](https://rubygems.org/gems/worldcup-2014)
- [world_cup_cli gem :octocat:](https://github.com/jameswilliamiii/world_cup_cli), [:gem:](https://rubygems.org/gems/world_cup_cli)
- [fatiherikli/worldcup :octocat:](https://github.com/fatiherikli/worldclub)
- [Huang-Wei/2014 :octocat:](https://github.com/Huang-Wei/2014)
- [rtopitt/bolao2014 :octocat:](https://github.com/rtopitt/bolao2014)
- [rtopitt/bolao :octocat:](https://github.com/rtopitt/bolao)
- [threefunkymonkeys/funky-world-cup :octocat:](https://github.com/threefunkymonkeys/funky-world-cup)
- [malagant/tipptop :octocat:](https://github.com/malagant/tipptop)
- [soccer_league :octocat:](https://github.com/mrjabba/soccer_league)
- [standings gem :octocat:](https://github.com/scottluptowski/standings), [:gem:](https://rubygems.org/gems/standings)
- [ahs85/bundesliga_predictions :octocat:](https://github.com/ahs85/bundesliga_predictions)
- [architv/soccer-cli](https://github.com/architv/soccer-cli)
- [4teamwork/ftw.footballchallenge :octocat:](https://github.com/4teamwork/ftw.footballchallenge)
- [sigi/bookie :octocat:](https://github.com/sigi/bookie)
- [kdungs/tippspiel :octocat:](https://github.com/kdungs/tippspiel)
- [chipsmachine/bltippspiel :octocat:](https://github.com/chipsmachine/bltippspiel)
- [chrenkot/Austrian-Bundesliga :octocat:](https://github.com/chrenkot/Austrian-Bundesliga)
- [veraefootball/vaerana-football-apps](https://github.com/veraefootball/vaerana-football-apps)
