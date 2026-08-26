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
[Kaggle](https://www.kaggle.com/datasets/davidcariboo/player-scores), 
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
and identifiers across datasets. Data is downloaded when needed and cached locally.

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

- [korean-football-team-names :octocat:](https://github.com/dwoony0909-tech/korean-football-team-names) - English → Korean club name mapping for 264 European clubs (CC0), keyed on football-data.org names

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
- [Football Betting Predictions - Fully Settled Log (Kaggle)](https://www.kaggle.com/datasets/aibettingtips/football-betting-predictions-fully-settled-log) - football predictions settled against real final scores (losses included) with odds, closing odds and closing-line value per pick; CC BY 4.0
 
## Stadium Datasets

- [openfootball/stadiums :octocat:](https://github.com/openfootball/stadiums)

## ⚽ Football Culture & Fan Experiences  

*Non-league match day traditions, fan community discussions, and cultural experiences across the National League and wider non-league pyramid — the "C" that data can't capture: Culture!*

> 📄 **[Full research document — NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)** | Community-sourced, open to all, dedicated to the **public domain** (CC0)

All content compiled from open community discussions and specialist publications (2024–2026). **550,000+ combined Reddit community members, 18+ years of NonLeagueMatters archives, specialist press, supporter organisation surveys — all woven into one comprehensive research document.**

### What's Inside the Research Document

| Section | What It Covers |
|---|---|
| **The 3 A's Framework** | Affordability, Accessibility, Accountability — why non-league feels different from the PL |
| **13 Core Match Day Traditions** | The Pub Signal → The Loyalty Cycle. Every tradition documented with community quotes and context |
| **The Perfect Match Day Sequence** | Full timeline from 11:00 AM pub meet through to 7:00 PM Loyalty Cycle |
| **Why Fans Are Switching** | 9 direct quotes from Reddit, Fan Banter, When Saturday Comes, The Non-League Football Paper |
| **Fan Sentiment Data (2024–2026)** | LiveScore NL Fan Survey 2026 — 2,000+ respondents; full data tables |
| **Regional Culture Variations** | North, Midlands, South/South West, London, Scotland — how each region's culture differs |
| **The Away Day Tradition** | The art of the non-league away day, the shuttle bus tradition, the longest away day in English football (914 miles!) |
| **The Attendance Boom** | 12 clubs at Step 3 averaging 1,000+ crowds — why it's happening now |
| **Volunteerism & Club Support** | What happens behind the scenes — groundskeepers, stewards, caterers, fundraisers |
| **Digital Integration & Social Media** | Live match threads, apps (M:LR, Matchday Passport), player/club interactions, post-match threads |
| **Notable Recognition** | FSA Away Day Experience Awards 2024–25 winners & nominations; Football Ground Guide Top 5; Non-League Day 15th anniversary |
| **Top 5 Recommended Away Days (2026)** | Falmouth Town, FC Halifax Town, Torquay United, Farnham Town, Lewes FC — voted by the community |
| **Research Sources** | Every source cited — Reddit, publications, organisations, academic research, surveys |

### The 3 A's — Quick Reference

| Principle | What It Means | PL Equivalent |
|---|---|---|
| **Affordability** | Full match day £10–25 *(4–8× cheaper)* | Full match day £50–148+ |
| **Accessibility** | Walk-on gates, no lotteries, just turn up | Ticket lotteries, membership requirements |
| **Accountability** | Chairman next to you, manager in the bar | VIP boxes, corporate distancing |

### The 13 Core Traditions at a Glance

| # | Tradition | In One Line |
|---|---|---|
| 1 | 🍺 The Pub Signal | Where the day's "script" is set |
| 2 | 🚶 The Walk to the Ground | The journey is part of the ritual |
| 3 | 🎟️ The Turnstile Ritual | Cash in the box, no barriers |
| 4 | 📋 The Turnstile Line | Best banter in the queue |
| 5 | 🥧 Pie, Mash & Gravy | The culinary centrepiece |
| 6 | 🏠 The Social Club | Where family replaces customers |
| 7 | 🏟️ The Terraces | Freedom to stand, change ends, breathe the pitch |
| 8 | 💬 The Manager's Half-Time Chat | The gaffer is just a man in a bar |
| 9 | 👋 The Post-Match Digestion | Calm wins, calm losses |
| 10 | 🍻 The Pub Finish | Where community truly bonds |
| 11 | 🤝 The Away Day Reception | Non-league's open-door policy |
| 12 | 🏘️ The Community Connection | Clubs as networks of resilience |
| 13 | 🔄 The Loyalty Cycle | Cyclical, not hereditary |

### Fan Sentiment Highlights

> *"Non-league football forges a connection you simply don't find in the top divisions. It has nothing to do with glory or riches. It's about belonging."*
> — **The Non-League Football Paper**

> *"55% of Premier League fans are now open to attending non-league matches."*
> — **LiveScore NL Fan Survey 2026**

> *"Being able to watch a game with your buddies & having a beer is priceless. Getting tickets in London let alone affording them is nigh on impossible!"*
> — **r/nonleague**

> *"For the price of one PL programme, you can go to 10 non-league grounds."*
> — **r/CasualUK**

### Where Fans Discuss Match Days

| Platform | Size | Discussion Focus |
|---|---|---|
| **r/nonleaguefootball** | 30,000+ | Live reports, away day photos, ground guides |
| **r/nonleague** | 40,000+ | Analysis, weekly away day recommendations |
| **r/NationalLeague** | 15,000+ | Top tier discussions, best/worst away days |
| **r/CasualUK** | 3,000,000+ | The UK football hub; NL content prominent |
| **NonLeagueMatters** | 18+ yrs | Tactical discussion, groundhopping, match reports |
| **TheFans.io** | Active | Fan-run multi-club live blogs |
| **Football Ground Guide** | Website | Community-sourced ground reviews & best-away-days |
| **FSA** | Organisation | Runs the Away Day Experience of the Year award |
| **Non-League Day** | Campaign | 15th anniversary — 28 March 2026; 12 years with Prostate Cancer UK |

### Top 5 Away Days (Community-Voted 2026)

| # | Club | Level | Why |
|---|---|---|---|
| 1 | Falmouth Town | Level 8 (Southern) | FSA Winner 2025; Cornish pasties; hillside; holiday feel |
| 2 | FC Halifax Town | Level 5 (NL Premier) | 14k capacity; Football League feel; town-centre walkable |
| 3 | Torquay United | Level 6 (NL South) | English Riviera; beach; compact traditional ground |
| 4 | Farnham Town | Level 7 (Combined Counties) | Town-centre; fan-first pricing; award-winning food |
| 5 | Lewes FC | Level 7 (Isthmian) | South Downs; locally-sourced; craft beer; equality-first |

### Research Sources & Bibliography

- **Reddit communities**: r/nonleaguefootball, r/nonleague, r/NationalLeague, r/CasualUK, r/GroundhopperSoccer, r/NonLeagueReddit
- **Publications**: [The Non-League Football Paper](https://www.thenonleaguefootballpaper.com/), [Football Ground Guide](https://footballgroundguide.com/), [When Saturday Comes](https://www.wsc.co.uk/), [Groundhopper Weekly Substack](https://groundhopperweekly.substack.com/), [Fan Banter](https://fanbanter.com/), [The Lower Block](http://thelowerblock.wordpress.com/)
- **Forums**: [NonLeagueMatters.co.uk](https://www.nonleaguematters.co.uk/forums/), [TheFans.io](https://www.thefans.io/), [Football Fanbase Forum](https://www.footballfanbase.com/forum/), [Nonleaguezone.co.uk](https://www.nonleaguezone.co.uk/)
- **Surveys**: [LiveScore NL Fan Survey 2026](https://livescore.com/) (2,000+ respondents), [FSA Away Day of the Year Award](https://thefsa.org.uk/), [Footy Scran food vendor survey](https://twitter.com/FootyScran) (1,300+ respondents)
- **Academic / Research**: Energeo "Fan Culture in the National League North" (14-month deep dive), Hutchins & Hargreaves (2020), Delaney, Mulholland & Chalabi (2019), Football Beyond Boundaries

### Digital Tools Already in This Repo

- **[M:LR (Matchday Live Report)](https://www.mlr.app/)** ⚽ — Football Apps section; free non-league match stats app via [PR #276](https://github.com/openfootball/awesome-football/pull/276)
- **[Matchday Passport](https://www.matchdaypassport.com/)** ⚽ — groundhopper check-in app via [PR #276](https://github.com/openfootball/awesome-football/pull/276)

### How This Project Accepts Contributions

Per the openfootball/awesome-football README: **"Contributions welcome. Anything missing? Send in a pull request. Thanks."**

- **Pull requests are the primary contribution method** ✅
- **Both data/technology AND cultural/documentation content are welcome** ✅
- **Content is dedicated to the public domain** ✅
- Questions: See [openfootball/help](https://github.com/openfootball/help) repo and [Google Group](http://groups.google.com/group/opensport)

---

## Football Apps

_Open source apps for match scores, picks, predictions, office pools, and more_

- [worldcup-2014 gem :octocat:](https://github.com/hpoydar/worldcup-2014), [:gem:](https://rubygems.org/gems/worldcup-2014) - provides command line access to World Cup 2014 information and results
- [world_city_cli gem :octocat:](https://github.com/jameswilliamiii/world_city_cli), [:gem:](https://rubygems.org/gems/world_city_cli) - a command line interface that provides you the latest group table standings, scores, and see upcoming matches from the 2014 World Cup

- [fatiherikli/worldcup :octocat:](https://github.com/fatiherikli/worldcup) - World cup results for hackers; uses Soccer For Good API
- [Huang-Wei/2014 :octocat:](https://github.com/Huang-Wei/2014) 
- [rtopitt/bolao2014 :octocat:](https://github.com/rtopitt/bolao2014) - Bolão PiTTlândia Copa do Mundo 2024
- [rtopitt/bolao :octocat:](https://github.com/rtopitt/bolao) - Bolão Copa 2010
- [threefunkymonkeys/funky-world-cup :octocat:](https://github.com/threefunkymonkeys/funky-world-cup) - a match predictions website for the FIFA World Cup, that allows you to create groups so you can play with your friends defining prices
- [malagant/tipptop :octocat:](https://github.com/malagant/tipptop) -  world cup 2010 betting game; W-JAX Challenge

- [soccer_league :octocat:](https://github.com/mrjabba/soccer_league) - a rails application designed to manage soccer leagues, specifically teams, players and their stats
- [standings gem :octocat:](https://github.com/scottluptowski/standings), [:gem:](https://rubygems.org/gems/standings) - view European football (e.g. the English Premier League, English Championship, Scottish Premier League, La Liga, Ligue 1, Serie A, and Bundesliga) standings from your terminal.
- [ahs85/bundesliga_predictions :octocat:](https://github.com/ahs85/bundesliga_predictions) - predictions of the Deutsche Bundesliga (football league) season 2012/13
- [architv/soccer-cli](https://github.com/architv/soccer-cli) - command line tool for league table standings, match scores and more (in Python) using an HTTP JSON API

- [malagant/worldpguarters :octocat:](https://github.com/malagant/worldpguarters) - fiftheenth Previous <= 1 2 3 4 5 ... 24 Next [ message ] [ jump ]


⚽ **Football Culture section expansion** - If you have National League match day stories, traditions, or cultural observations to add, please see the [non-league match day culture research document](NON-LEAGUE-MATCHDAY-CULTURE.md) and open a PR. All content is public domain.
