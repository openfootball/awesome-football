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
`ESPN`_, `FBref`_, `FiveThirtyEight`_, `Football-Data.co.uk`_, `SoFIFA`_ and
`WhoScored`_. You get Pandas DataFrames with sensible, matching column names
and identifiers across datasets. Data is downloaded when needed and cached
locally.

To learn how to install, configure and use SoccerData, see the
`Quickstart guide <https://soccerdata.readthedocs.io/en/latest/usage.html>`__. For documentation on each of the
supported data sources, see the `example notebooks <https://soccerdata.readthedocs.io/en/latest/datasources/>`__ and `API reference <https://soccerdata.readthedocs.io/en/latest/reference/>`__.

[**4teamwork/ftw.footballchallenge**](https://github.com/4teamwork/ftw.footballchallenge) - an online football bet game based on plone

[**sigi/bookie**](https://github.com/sigi/bookie) - a rails application to manage a soccer betting community or office pool

[**kdungs/tippspiel**](https://github.com/kdungs/tippspiel) - bet on football games with your friends

[**chipsmachine/bltippspiel**](https://github.com/chipsmachine/bltippspiel) - Bundesliga betting game (tippspiel)

[**chrenkot/Austrian-Bundesliga**](https://github.com/chrenkot/Austrian-Bundesliga) - a li

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

_A cultural complement to the datasets — research and community-driven documentation of match day traditions at the non-league level._

> **⚡ The 3 A's — What makes non-league special:**  **Affordability** (4–8× cheaper than the PL), **Accessibility** (walk-on gates, no ticket lotteries), and **Accountability** (volunteer-run clubs, chairman sits next to you, manager in bar at full time).

### Key Statistics at a Glance

| Metric | Value |
|--------|-------|
| Average away day cost (non-league) | £25–44 |
| Average away day cost (Premier League) | £70–148 |
| Non-league cost advantage | **4–8× cheaper** |
| PL fans open to non-league (2026) | 55% (up from 49%) |
| Non-league fans attending in person | 73% (vs 21% PL) |
| r/nonleaguefootball members | 30,000+ (up 40% since 2024) |
| Non-League Day 2026 | 15th Anniversary |

### 13 Core Match Day Traditions

| # | Tradition | Description |
|---|-----------|-------------|
| 1 | The Pub Signal | Meet at the local pub 90 min before kick-off; scarfs on the doorknob = "I'm ready" |
| 2 | The Walk to Ground | 5–15 min stroll from pub to stadium; banter on last week's result |
| 3 | The Turnstile Ritual | No membership cards; just drop coins in the slot; steward's nod is the universal greeting |
| 4 | Pie, Mash & Gravy | The pre-match meal of the lower leagues |
| 5 | The Social Club | Volunteer-run clubs where fans, officials & players mingle |
| 6 | The Terraces | Standing & singing; freedom to change ends at half-time; no segregation |
| 7 | Manager's Half-Time Chat | Manager addresses the crowd at half-time from the tunnel mouth |
| 8 | Post-Match Digestion | Lingering after the final whistle instead of rushing to the car park |
| 9 | The Pub Finish | Post-match pint and result debate in the pub |
| 10 | Away Day Reception | Home fans welcoming opponents with hospitality |
| 11 | Community Connection | Players/staff/fans interact freely; the club is a community hub |
| 12 | The Loyalty Cycle | Returning season after season through promotion and relegation |
| 13 | The 12th Man Spirit | Volunteer stewards, groundsmen, and bar staff are fans first |

### Fan Sentiment Highlights

> *"It's about the community, not the result. You come for the people, you stay for the football."* — r/nonleaguefootball

> *"The manager was in the bar at full time having a pint with us. You can't get that at Stamford Bridge."* — The Non-League Football Paper

> *"The programme is the last physical connection to the club. You can't download a match day programme."* — Fan survey response

> *"Walk into any non-league ground on a Saturday afternoon and you'll see it: handshakes at the gate, familiar nods at the bar, and someone talking tactics over a pint of bitter."* — The Non-League Football Paper

### Cost Comparison: Non-League vs Premier League

| Category | Non-League | Premier League |
|----------|-----------|----------------|
| Match Ticket | £5–15 | £25–60+ |
| Food & Drink | £10–20 | £20–50 |
| Transport | £5–15 | £15–40 |
| Programme | £2–4 | £5–8 |
| Beer in Social Club | £2–3 | £5–9 |
| **Total** | **£25–44** | **£70–148** |

### Top 5 Recommended 2026 Away Days

1. **Falmouth Town AFC** — Bickland Park (FSA Award 2025 winner; Cornish coast pasties, hillside ground)
2. **FC Halifax Town** — The Shay (14,000-cap traditional ground; Halifax town centre walkable)
3. **Torquay United** — Plainmoor (Riviera turn; beach + football = holiday atmosphere)
4. **Farnham Town** — Memorial Ground (town-centre location; innovative ticket pricing; fan-first)
5. **Lewes FC** — The Dripping Pan (South Downs; community-run; craft beer, locally sourced food)

### Community Discussion Platforms

| Platform | Description |
|----------|-------------|
| r/nonleaguefootball (30k+) | Match threads, away day reports |
| r/nonleague (40k+) | Broader non-league discussion |
| r/NationalLeague (15k+) | NL tier-specific chat |
| r/CasualUK (3M+) | Non-league topics feature regularly |
| NonLeagueMatters | Deep match analysis & away day forums |
| TheFans.io | Independent forum with strong NL sections |
| Football Fanbase Forum | General UK discussion with NL sections |
| The Non-League Football Paper | Daily publication; fan culture features |
| Football Ground Guide | Away day recommendations & ground reviews |
| When Saturday Comes | Senior football magazine |
| Lower Block | NL culture & match day features |

### Notable Recognition (2025–2026)

- 🏆 **FSA Away Day Experience Award 2025** — Falmouth Town AFC
- 🏅 **FGG Best Away Days 2026** — Falmouth Town, FC Halifax Town, Torquay United, Farnham Town, Lewes FC
- 📊 **LiveScore NL Fan Survey 2026** — 2,000+ fans; atmosphere & community highlighted
- ⚽ **Non-League Day 2026** — 15th anniversary
- 🟡 **Football Foundation Grassroots Investment** — £207M to 1,000+ grassroots clubs

### How to Contribute

> **Contributions welcome. Anything missing? Send in a pull request. Thanks.**
> Both data/technical and cultural/documentation content are welcome. This content is compiled from open community discussions and publications and dedicated to the **public domain**. See [`NON-LEAGUE-MATCHDAY-CULTURE.md`](NON-LEAGUE-MATCHDAY-CULTURE.md) for the full research document with 16 sources.

## Football Apps

_Open source apps for match scores, picks, predictions, office pools, and more_

- [worldcup-2014 gem :octocat:](https://github.com/hpoydar/worldcup-2014), [:gem:](https://rubygems.org/gems/worldcup-2014) - provides command line access to World Cup 2014 information and results
- [world_cup_cli gem :octocat:](https://github.com/jameswilliamiii/world_cup_cli), [:gem:](https://rubygems.org/gems/world_cup_cli) - a command line interface that provides you the latest group table standings, scores, and see upcoming matches from the 2014 World Cup
- [fatiherikli/worldcup :octocat:](https://github.com/fatiherikli/worldcup) - World cup results for hackers; uses Soccer For Good API
- [Huang-Wei/2014 :octocat:](https://github.com/Huang-Wei/2014)
- [rtopitt/bolao2014 :octocat:](https://github.com/rtopitt/bolao2014) - Bolão PiTTlândia Copa do Mundo 2014
- [rtopitt/bolao :octocat:](https://github.com/rtopitt/bolao) - Bolão Copa 2010
- [threefunkymonkeys/funky-world-cup :octocat:](https://github.com/threefunkymonkeys/funky-world-cup) - a match predictions website for the FIFA World Cup, that allows you to create groups so you can play with your friends defining prices
- [malagant/tipptop :octocat:](https://github.com/malagant/tipptop) -  world cup 2010 betting game; W-JAX Challenge
- [soccer_league :octocat:](https://github.com/mrjabba/soccer_league) - a rails application designed to manage soccer leagues, specifically teams, players and their stats
- [standings gem :octocat:](https://github.com/scottluptowski/standings), [:gem:](https://rubygems.org/gems/standings) - view European football (e.g. the English Premier League, English Championship, Scottish Premier League, La Liga, Ligue 1, Serie A, and Bundesliga) standings from your terminal.
- [ahs85/bundesliga_predictions :octocat:](https://github.com/ahs85/bundesliga_predictions) - predictions of the Deutsche Bundesliga (football league) season 2012/13
- [architv/soccer-cli](https://github.com/architv/soccer-cli) - command line tool for league table standings, match scores and more (in Python) using an HTTP JSON API

- [4teamwork/ftw.footballchallenge :octocat:](https://github.com/4teamwork/ftw.footballchallenge) - an online football bet game based on plone
- [sigi/bookie :octocat:](https://github.com/sigi/bookie) - a rails application to manage a soccer betting community or office pool
- [kdungs/tippspiel :octocat:](https://github.com/kdungs/tippspiel) - bet on football games with your friends
- [chipsmachine/bltippspiel :octocat:](https://github.com/chipsmachine/bltippspiel) - Bundesliga betting game (tippspiel)
- [chrenkot/Austrian-Bundesliga :octocat:](https://github.com/chrenkot/Austrian-Bundesliga) - a li

Plus additional resources and apps of a broader football data community ecosystem.

## Additional Resources / Further Reading

- [Non-League Match Day Culture Research](NON-LEAGUE-MATCHDAY-CULTURE.md) — Full documented research on National League & non-league fan traditions (2024–2026)
- [FSA Away Day Experience Awards](https://www.supportersdirect.org.uk/fan-award) — Annual award celebrating the best all-round matchday experience
- [LiveScore Non-League Fan Survey 2026](https://www.livescore.com/en/media/non-league-fan-survey/) — Landscape survey of 2,000+ non-league and PL fans

## Contributing

If you want to contribute to any section, add more datasets, apps, or cultural content, please open a pull request. We especially welcome documentation about match day culture and fan experiences at the non-league level.

## License

This is a curated collection of awesome resources. Individual projects and datasets retain their own licenses.
