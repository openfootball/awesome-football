Awesome Series @ Planet Open Data

[World (Countries, Cities, Codes, ...)](https://github.com/planetopendata/awesome-world) • 
[Football (Clubs, Players, Stadiums, ...)](https://github.com/planetopendata/awesome-football) • 
[SQLite (Tools, Books, Schemas, ...)](https://github.com/planetopendata/awesome-sqlite)


# Awesome Football - Open Datasets & Open Source Apps

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

SoccerData is a collection of wrappers over soccer data from `Club Elo`_, `ESPN`_, `FBref`_, `FiveThirtyEight`_, `Football-Data.co.uk`_, `SoFIFA`_ and `WhoScored`_. You get Pandas DataFrames with sensible, matching column names
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

Contributions welcome! This section documents the culture, traditions, and community experiences around National League and wider non-league football match days.

> **The 3 A's of Non-League:** Affordability, Accessibility, Accountability — the cornerstones that make grassroots football uniquely welcoming.

### Cost Comparison

| Match Day Expense | Non-League (NL) | Premier League (PL) |
|---|---|---|
| Match ticket | £5–15 | £30–100+ |
| Full match day | £12–27 | £50–148+ |
| Away day (20 matches) | £250–500 | £1,000–2,960 |

Non-league is **4–8× cheaper** than the Premier League.

### 13 Core Match Day Traditions

1. 🍺 **The Pub Signal** — Pre-match pub gathering where the atmosphere builds
2. 🚶 **The Walk to the Ground** — Stroll through familiar streets with fellow supporters
3. 🎟️ **The Turnstile Ritual** — Walk-on gates, no pre-booking or membership required
4. 🍗 **The Pie, Mash & Gravy** — Sacred stadium pies, often from local bakeries
5. 🏠 **The Social Club / Clubhouse** — Welcoming hub where fans, officials & players mingle
6. 🏟️ **The Terraces** — Freedom of movement; change ends at half-time
7. 📋 **The Matchday Programme** — £2–3 physical souvenir supporting club finances
8. 📢 **The Manager's Half-Time Chat** — Volunteer-operated, intimate & unpolished
9. 🍻 **The Pub Finish** — Post-match discussion over a drink
10. 🚌 **The Away Day Reception** — Clubs welcoming visiting supporters
11. 🤝 **The Community Connection** — Community programmes addressing social issues
12. 🔄 **The Loyalty Cycle** — Generational commitment to the club
13. 📱 **The Digital Bridge** — Mobile-first fans live-tailing stats at rural grounds

### Key Statistics

| Metric | Non-League | Premier League |
|---|---|---|
| Fans attending in person | 73% | 21% |
| Fans who care about results | 23% | 69% |
| PL fans open to NL (2026) | 55% (up from 49%) | — |
| r/nonleaguefootball growth | ~40% since 2024 | — |
| Longest English league away day | Truro → Gateshead (914 miles) | — |

### Fan Quote Highlight

> *"Non-league football forges a connection you simply don't find in the top divisions. It has nothing to do with glory or riches. It's about belonging."* — The Non-League Football Paper

### Community Discussion Platforms

- [r/nonleaguefootball](https://www.reddit.com/r/nonleaguefootball/) (30k+ members)
- [r/nonleague](https://www.reddit.com/r/nonleague/) (40k+ members)
- [r/NationalLeague](https://www.reddit.com/r/NationalLeague/) (15k+ members)
- [NonLeagueMatters Forums](https://www.nonleaguematters.co.uk/forums/)
- [TheFans.io](https://thefans.io/)
- [FootballFanbase Forum](https://www.footballfanbase.com/)
- [FanBanter](https://www.fanbanter.com/)

### Notable Recognition (2025–2026)

- **FSA Away Day Experience Award 2025** — Falmouth Town AFC
- **FGG Best Away Days 2026** — Falmouth Town, FC Halifax Town, Torquay United, Farnham Town, Lewes FC
- **Non-League Day 2026** — 15th anniversary
- **PL funding to NL + grassroots** — £230.6M total

### Top 5 Recommended 2026 Away Days

1. **Falmouth Town** (FSA 2025 Winner — Cornish charm, hillside ground, pasties)
2. **FC Halifax Town** (The Shay — 14k capacity, "Football League" feel)
3. **Torquay United** (Plainmoor — English Riviera, beach + football weekend)
4. **Farnham Town** (Town-centre, innovative pricing, craft beer)
5. **Lewes FC** (Dripping Pan — South Downs, locally sourced food, inclusive)

### Articles & Guides

- [The Perfect Matchday](https://www.thenonleaguefootballpaper.com/guest-posts/604687/the-perfect-matchday-a-beginners-guide-to-the-non-league-experience/) — The Non-League Football Paper (Feb 2026)
- [Boosting Your National League Fan Experience: 7 Golden Tips](https://www.thenonleaguefootballpaper.com/guest-posts/443731/boosting-your-national-league-fan-experience-7-golden-tips/) — The Non-League Football Paper (Aug 2023)
- [Passion Beyond the Premier League](https://www.thenonleaguefootballpaper.com/guest-posts/478864/passion-beyond-the-premier-league-non-league-football-fan-engagement/) — The Non-League Football Paper (Feb 2024)
- [Best Away Days in Non-League Football](https://footballgroundguide.com/news/best-away-days-in-non-league-football-our-top-5-ranked-from-national-league-to-step-4.html) — Football Ground Guide (Mar 2026)
- [Fan Culture in the National League North: A Deep Dive](https://energeo-project.eu/fan-culture-in-the-national-league-north-a-deep-dive/) — Energeo (2025)
- [The Great Return](https://www.when Saturday Comes.com/) — When Saturday Comes, WSC 451 (Feb 2025)
- [Away Days | Travel, Movement, and the Geography of Football Culture](https://www.lowerblock.com/) — Lower Block (Apr 2026)

### Full Research Document

📄 **[NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)** — Comprehensive research covering the 3 A's Framework, 13 Core Traditions, Perfect Match Day Sequence, Fan Sentiment Highlights, Cost Comparison, Regional Variations, Community Platforms Directory, Notable Recognition, Top 5 Away Days, The Non-League Boom, and Full Source Bibliography (15+ entries).

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
- [chrenkot/Austrian-Bundesliga :octocat:](https://github.com/chrenkot/Austrian-Bundesliga) - a little open source android app for gathering information about the austrian bundesliga
- [rodmoioliveira/football-graphs :octocat:](https://github.com/rodmoioliveira/football-graphs) - Some visualizations on passing networks
* [Last season comparison](https://compare-last-season.netlify.app), [:octocat:](https://github.com/nurgasemetey/compare-last-season) - Last season comparison tool
- [Scorewit](https://www.scorewit.com) - free daily football trivia plus computed World Cup and English top-flight reference pages, built on openfootball worldcup + england data (attribution: https://www.scorewit.com/llms.txt)
- [Matchday Passport](https://allenwu-blip.github.io/matchday-passport/) - free iOS app that turns every match you attend into a collectible passport stamp (ground, date, score, both nations' flags, a different ink per competition); fixtures across twelve competitions sync daily from [football-data.org](https://www.football-data.org) with in-app attribution, and every fixture gets a page where fans who were there share photos and video; no ads, tracking or analytics; [App Store](https://apps.apple.com/us/app/matchday-passport/id6792546917)
- [PunditBench](https://punditbench.com/?utm_source=github&utm_medium=awesome_list&utm_campaign=football_llm_benchmark) [:octocat:](https://github.com/teemula35/punditbench) - pre-registered benchmark of football forecasts from 40+ language models; picks are locked before play, source-linked, and scored afterward (18+, informational only, no tips)


## Meta

**License**

The awesome list is dedicated to the public domain. Use as you please with no restrictions whatsoever.

**Questions? Comments?**

Yes, you can. More than welcome.
See [Help & Support »](https://github.com/openfootball/help)
