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
- [chrenkot/Austrian-Bundesliga :octocat:](https://github.com/chrenkot/Austrian-Bundesliga) - a little open source android app (but with a great name)
- [lukebakken/scorepusher](https://github.com/lukebakken/scorepusher) - a simple scoreboard for football/soccer matches
- [cweinhaas/gcalc](https://github.com/cweinhaas/gcalc) - a python-based football pool calculator
- [jakeguten/footballpool](https://github.com/jakeguten/footballpool) - a Football Pool implementation (v. of large pool)
- [jkehler/footy-predictor](https://github.com/jkehler/footy-predictor) - a simple ELO-based football pool predictor
- [telepathKat/footypool](https://github.com/telepathKat/footypool) - Football H2H Pool
- [nickknowlton/footy](https://github.com/nickknowlton/footy) - a Football Pool predictor for CSV files
- [m18759/datasets_scripts](https://github.com/m18759/datasets_scripts) - transfer data from Transfermarkt
- [jamescarroll/footballpool](https://github.com/jamescarroll/footballpool) - another football pool implementation
- [lowzero/football-pool](https://github.com/lowzero/football-pool) - football predictions in python
- [milakiss/forthright](https://github.com/milakiss/forthright) - a small tool to help manage football (soccer) pools
- [dschreiber/gcalc](https://github.com/dschreiber/gcalc) - python-based football pool calculator
- [bertrandbricout/scorebook](https://github.com/bertrandbricout/scorebook) - a simple score app based on football
- [dcaribou/transfermarkt-scraper](https://github.com/dcaribou/transfermarkt-scraper) - transfermarkt website scraper

## ⚽ Football Culture & Fan Experiences

> Non-league football offers an authentic, affordable, and community-driven match day experience that is worth celebrating alongside the project's data and technology resources. This section highlights key research and community discussions about match day culture in the National League and wider non-league pyramid.

A detailed research document — **[NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)** — covers all 13 traditions, cost comparisons, regional variations, the match day ritual sequence, and a curated reading list. A summary of key points follows.

### The 3 A's of Non-League Football

| Dimension | Non-League | Premier League |
|-----------|-----------|---------------|
| **Affordability** | £5–£15 tickets; pie & pint ~£5–£7; programmes £2–£3 | £30–£100+ tickets; £1,500–£3,000+ for 20 away days |
| **Accessibility** | Walk-on gate, 20 min before kick-off; small terraced grounds (500–5,000) | Book in advance; 45+ min queues; large distant stadiums |
| **Accountability** | Volunteer-run; chairman knows your name; fans steward and serve | Anonymous corporate ownership; market-driven pricing |

### 13 Core Match Day Traditions

1. **The Pub Signal** — Pre-match pub gatherings where the community converges
2. **Intimate Grounds** — Small terraced stadiums (500–5,000) with pitchside proximity
3. **Freedom of the Terrace** — Open standing, change ends at half-time, no assigned seats
4. **The Clubhouse / Social Club** — Volunteer-run canteen/bar, £2–3 pints, fans mingle as equals
5. **Pie, Mash & Gravy ("Footy Scran")** — £3–4 legendary local bakery pies, every penny to the club
6. **Physical Programme** — Paper collectibles (£2–3) with local history, direct financial support
7. **Volunteer Spirit** — Community-owned operations, fans steward and serve
8. **Local Rivalries** — Deep-rooted geographic derbies with centuries of history
9. **Chants & Songs** — Organic, locally-written, multi-generational
10. **Family Inclusion** — Kids roam freely, £7 family tickets, relaxed atmosphere
11. **The Conference Legacy (1979–2004)** — Community-over-commercialism founding ethos
12. **Non-League Day** — Annual open-doors events during international breaks
13. **Post-Match Socialising** — 4–6 hour match day rituals, clubhouse stays open beyond full-time

### Key Fan Sentiment

> *"Walking into a non-league ground for the first time, I felt like I'd walked into someone's living room. Everyone said hello."* — r/nonleaguefootball

> *"For the price of one PL programme, you can go to 10 non-league grounds."* — r/CasualUK

> *"Nobody clocks you in. You just turn up. That's the point."* — r/nonleaguefootball

### Notable Recognition (2025–2026)

- **FSA Away Day Experience Award 2025**: Falmouth Town AFC
- **Football Ground Guide "Best Away Days 2026"**: Falmouth Town, Halifax Town, Torquay United, Farnham Town, Lewes FC
- **NFP "The Perfect Matchday" guide** (Feb 2026)
- **When Saturday Comes**: "Why more fans are turning to non-League" (Feb 2025)
- **LiveScore Survey 2026**: 55% of PL fans open to attending non-league matches

### Community Discussion Platforms

| Platform | Audience |
|----------|----------|
| r/nonleaguefootball (30k+) | Non-league supporters |
| r/nonleague (40k+) | Broader non-league community |
| r/NationalLeague (15k+) | National League fans |
| r/CasualUK (3M+) | Casual football culture |
| NonLeagueMatters | Forum |
| Football Fanbase Forum | Forum |
| TheFans.io | Forum |
| The Non-League Football Paper | Publication |
| Football Ground Guide | Publication |
| When Saturday Comes | Publication |

### Where to Explore Further

A comprehensive research document covering all 13 traditions, the non-league pyramid structure, cost comparisons, regional variations, the match day ritual sequence, and a curated reading list is available in **[NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)**.

See also **[FOOTBALL-CULTURE-AND-FAN-EXPERIENCES.md](FOOTBALL-CULTURE-AND-FAN-EXPERIENCES.md)** for the full summary with open data gaps, golden tips, and contribution guidance.

---

## Meta

- [How to Contribute](CONTRIBUTING.md)
- [openfootball/help](https://github.com/openfootball/help)
- [GitHub Topic: football](https://github.com/topics/football)
- [Planet Open Data @ planetopendata](https://github.com/planetopendata)

---

*This project is dedicated to the public domain. See [UNLICENSE](UNLICENSE) if present.*