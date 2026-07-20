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


## ⚽ Football Culture & Fan Experiences

_New in 2026 — documenting the unique match day culture and community traditions of non-league football._

### The 3 A's: Why Non-League Match Days Are Different

| Aspect | Non-League | Premier League |
|--------|------------|----------------|
| **Affordability** | £25–44 per away day | £70–148 per away day |
| **Accessibility** | Walk-on gates, no ticket lotteries | Ticket lotteries, membership queues |
| **Accountability** | Chairman next to you, manager in the bar at full time | Decision-makers behind closed doors |

NL is **4–8× cheaper** than the PL — and 73% of NL fans attend in person vs just 21% of PL fans.

### 13 Core Match Day Traditions

1. 🍺 **The Pub Signal** — Scarf on the doorknob, 90 min before kick-off
2. 🚶 **The Walk to Ground** — Pre-match stroll with banter
3. 🎟️ **The Turnstile Ritual** — Friendly nod from the volunteer steward
4. 🥧 **Pie, Mash & Gravy** — The undisputed king of "footy scran"
5. 🍻 **The Social Club** — Volunteer-run, sponsorship-free pints
6. 🗣️ **The Terraces** — Standing where you like, chanting freely
7. 🎙️ **The Manager's Half-Time Chat** — Managers address the crowd from the tunnel
8. 🍵 **Post-Match Digestion** — Lingering to soak up the atmosphere
9. 🏪 **The Pub Finish** — Debating the result with pundit intensity
10. 🤝 **Away Day Reception** — Home fans welcoming opponents with hospitality
11. 👥 **Community Connection** — Players and managers know fans by name
12. 🔄 **The Loyalty Cycle** — Following through promotion, relegation, everything
13. 🏟️ **The 12th Man Spirit** — Volunteer stewards, groundsmen, bar staff who are fans first

### Key Statistics

| Metric | Value |
|--------|-------|
| NL fans attending in person | **73%** (PL: 21%) |
| NL fans who care about results | **23%** (PL: 69%) |
| PL fans open to non-league | **55%** (up from 49% in 2025) |
| r/nonleaguefootball members | **30,000+** |
| Non-League Day 2026 | **15th** anniversary (28th March) |
| PL funding to NL + grassroots (2026) | **£230.6M** |

### Fan Sentiment

> "It's about the community, not the result. You come for the people, you stay for the football." — r/nonleaguefootball

> "The manager was in the bar at full time having a pint with us. You can't get that at Stamford Bridge." — The Non-League Football Paper

> "Non-league football forges a connection you simply don't find in the top divisions. It has nothing to do with glory or riches. It's about belonging." — The Non-League Football Paper

### Community Discussion Platforms

| Platform | Focus |
|----------|-------|
| [r/nonleaguefootball](https://www.reddit.com/r/nonleaguefootball/) (30k+) | Primary match day discussion hub |
| [r/nonleague](https://www.reddit.com/r/nonleague/) (40k+) | Broader non-league including National League |
| [r/NationalLeague](https://www.reddit.com/r/NationalLeague/) (15k+) | Top tier of non-league |
| [r/NonLeagueReddit](https://www.reddit.com/r/NonLeagueReddit/) | English non-league, lower pyramid |
| [r/CasualUK](https://www.reddit.com/r/CasualUK/) | Non-league experience threads |
| NonLeagueMatters forums | National League discussion threads |
| The Football Fanbase Forum | General UK football including non-league |
| The Football Forum | Conference/National League message board |
| Nonleaguezone | ProBoards for National League |

### Notable Recognition (2025–2026)

- 🏆 FSA Away Day Experience of the Year 2025: Falmouth Town AFC
- ⚽ FSA Away Day Experience 2024-25: Kidsgrove Athletic
- 📋 FSA Away Day Experience 2023-24: Salisbury FC
- 🏅 FGG Best Away Days 2026: Falmouth, FC Halifax, Torquay, Farnham Town, Lewes FC

### Top 5 Recommended 2026 Away Days

1. 🏆 **Falmouth Town AFC** (Bickland Park) — FSA award winner; hillside ground; Cornish pasties; holiday atmosphere
2. **FC Halifax Town** (The Shay) — 14,000-capacity; Football League feel; walkable town centre
3. **Torquay United** (Plainmoor) — English Riviera; beach + football; lively terrace culture
4. **Farnham Town** (Memorial Ground) — Rare town-centre location; innovative pricing; quality food
5. **Lewes FC** (The Dripping Pan) — South Downs setting; locally sourced food; craft beer

### Fan Community Research Sources

- The Non-League Football Paper — Daily fan culture features
- Football Ground Guide — Away day recommendations & ground reviews
- When Saturday Comes — "The Great Return" narrative
- LiveScore NL Fan Survey 2026 — 2,000+ respondents
- FSA Away Day Experience Awards — Annual recognition
- Energeo — Fan Culture in the National League North
- Lower Block — Terrace culture features
- Verve Magazine — Fan survey analysis

Full research document: see [NON-LEAGUE-MATCHDAY-CULTURE.md](./NON-LEAGUE-MATCHDAY-CULTURE.md)

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
- [chrenkot/Austrian-Bundesliga :octocat:](https://github.com/chrenkot/Austrian-Bundesliga) - a lib for users to find, check and book Austrian Bundesliga matches
- [archy42/bundes-manager :octocat:](https://github.com/archy42/bundes-manager) - a small tippspiel-like (known in Germany as Rundfunk) app which calculates the Bundesliga table, the current and any other past one
- [oback/analyse :octocat:](https://github.com/oback/analyse) - analyse football (soccer) match statistics using data from FBref

- [abaiii168/world-cup-2026-tour-match-schedule :octocat:](https://github.com/abaiii168/world-cup-2026-tour-match-schedule) - World Cup 2026 fixtures with a free JSON API and calendar downloads

- [Krymets/wc2026 :octocat:](https://github.com/Krymets/wc2026) - Live scores, goals & cards by minute for all 104 WC2026 matches

- [lefProg/claudial :octocat:](https://github.com/lefProg/claudial) - see live updates for the 2026 World Cup in your Claude Code status line


## Notes

### No longer available

- [Rudeltippen :octocat:](https://github.com/svenkubiak/Rudeltippen) - a football betting game based on the Ninja Framework and Twitter Bootstrap
- [ericsaupe/world-c](https://github.com/ericsaupe/world-c)

### Football Data

- [jokecamp/FootballData :octocat:](https://github.com/jokecamp/FootballData) - a hodgepodge of JSON and CSV football data also in this list under Football Datasets
- [llimllib/soccerdata :octocat:](https://github.com/llimllib/soccerdata) - a collection of soccer results also in this list under Football Datasets


## Meta

- :octocat: [List of awesome-lists](https://github.com/sindresorhus/awesome)
- :gem: [awesome-ruby list](https://github.com/markets/awesome-ruby)