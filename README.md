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

> Storytelling and community — how fans experience the beautiful game beyond the data.

This project is now expanding to include the **C — Culture** dimension of football. Here is what we know about non-league and lower-league match day culture, compiled from open community discussions and publications (2024–2026).

### Cost Comparison: Non-League vs Premier League

| Expense | Non-League | Premier League |
|---------|-----------|---------------|
| Match ticket (home) | £8–18 | £25–100+ |
| Programme | £2–3 | £5–7 |
| Pie &amp; drink | £4–6 | £12–18 |
| Away day travel + entry | £12–27 | £50–148 |
| **Total per match day** | **£12–25** | **£50–148** |
| **Cost advantage** | **4–8× cheaper** | — |

### The 3 A's of Non-League Football

| Principle | Description |
|-----------|-------------|
| **Affordability** | 4–8× cheaper than PL. A full match day costs £12–27 vs £50–148. |
| **Accessibility** | Walk up, pay at the turnstile, find your spot. No barriers. |
| **Accountability** | You're known by the stewards, players, and manager. Not a customer — a community member. |

### 13 Core Match Day Traditions

| Tradition | Description |
|-----------|-------------|
| 🍺 **The Pub Signal** | A specific pub is the unofficial meetup point before kick-off. Every club has one. |
| 🚶 **Walk to the Ground** | Scarves held high, singing the club anthem on the walk to the ground. |
| 🎫 **Turnstile Ritual** | The physical act of paying at the turnstile — a moment of transition from everyday life to match day. |
| 🥧 **Pie &amp; Gravy** | Legendary steak and ale pies, often from local bakeries, with creamy mash and rich gravy. |
| 🏠 **The Social Club** | A welcoming hub where fans, club officials, and sometimes players mingle freely over cheap drinks. |
| 🟢 **The Terraces** | Standing with freedom of movement. No assigned seats, no barriers. Change ends at half-time. |
| 🎙️ **Manager's Chat** | A single volunteer-operated microphone — intimate, unpolished, charming. |n| 🍻 **Pub Finish** | The pub becomes the post-match debrief hub. Win or lose, conversations carry on over pints. |
| 🚌 **Away Day Reception** | Some clubs go the extra mile for visiting supporters — welcome packs, dedicated away sections. |
| 🤝 **Community Connection** | Clubs are deeply embedded in their local communities. Match days are communal events. |
| 📰 **Physical Programme** | A couple of pounds for a paper souvenir with local history, manager notes, and player interviews. |
| 🔥 **DIY Atmospherics** | Fans bring their own percussion — drinks drums, tambourines, thunder flash. |
| 🔄 **The Loyalty Cycle** | Season tickets, every home game, travelling for away days, passing loyalty to the next generation. |

### Key Statistics at a Glance

| Metric | Non-League | Premier League |
|--------|-----------|---------------|
| Avg away day cost | £12–27 | £50–148 |
| Fans attending in person | 73% | 21% |
| PL fans open to NL (2026) | 55% (up from 49%) | — |
| NL fans who care about results | 23% | 69% |
| r/nonleaguefootball growth | ~40% since 2024 (30k+) | — |
| PL funding to NL + grassroots | £230.6M (2026) | — |
| Non-League Day 2026 | 15th anniversary (28 Mar) | — |

### Community Discussion Platforms

| Platform | Members | Link |
|----------|---------|------|
| r/nonleaguefootball | 30,000+ | [Link](https://reddit.com/r/nonleaguefootball) |
| r/nonleague | 40,000+ | [Link](https://reddit.com/r/nonleague) |
| r/NationalLeague | 15,000+ | [Link](https://reddit.com/r/NationalLeague) |
| r/CasualUK | 3,000,000+ | [Link](https://reddit.com/r/CasualUK) |

**Specialist Publications:** The Non-League Football Paper, Football Ground Guide, When Saturday Comes, Lower Block, Energeo

**Forums:** NonLeagueMatters, TheFans.io, Football Fanbase Forum, FanBanter

### Fan Quote Highlight

> *"Non-league football forges a connection you simply don't find in the top divisions. It has nothing to do with glory or riches. It's about belonging."*  
> — The Non-League Football Paper

### Top 5 Recommended 2026 Away Days

| Club | Ground | League | Why Go? |
|------|--------|--------|---------|
| Falmouth Town AFC | Bickland Park | Southern League (L8) | FSA Away Day Experience Award 2025 winner. Cornish pasties, hillside setting. |
| FC Halifax Town | The Shay | National League | "Football League feel" (14k capacity). Great pubs in Halifax town centre. |
| Torquay United | Plainmoor | National League South | English Riviera setting. Beaches, seaside pubs, holiday feel. |
| Farnham Town | Memorial Ground | Isthmian League | Town-centre location. Fan-first: innovative pricing, quality food. |
| Lewes FC | The Dripping Pan | National League South | Scenic South Downs. Locally sourced food, craft beer. One of Britain's most scenic grounds. |

### 📚 Articles & Guides

- [The Perfect Matchday: A Beginner's Guide to the Non-League Experience](https://www.thenonleaguefootballpaper.com/guest-posts/604687/the-perfect-matchday-a-beginners-guide-to-the-non-league-experience/) (Feb 2026)
- [Passion Beyond the Premier League: Non-League Football Fan Engagement](https://www.thenonleaguefootballpaper.com/guest-posts/478864/passion-beyond-the-premier-league-non-league-football-fan-engagement/) (Feb 2024)
- [Best Away Days in Non-League: Top 5 Ranked](https://footballgroundguide.com/news/best-away-days-in-non-league-football-our-top-5-ranked-from-national-league-to-step-4.html) (Mar 2026)
- [What is Football Terrace Culture?](https://lowerblock.com/articles/what-is-football-terrace-culture/) (Jan 2025)
- [Fan Culture in the National League North: A Deep Dive](https://energeo-project.eu/fan-culture-in-the-national-league-north-a-deep-dive/) (2025)
- [Boosting Your National League Fan Experience: 7 Golden Tips](https://www.thenonleaguefootballpaper.com/guest-posts/443731/boosting-your-national-league-fan-experience-7-golden-tips/) (Aug 2023)

### 📄 Full Research Document

For the complete research document with all sections — including the Perfect Match Day Sequence timeline, detailed Fan Sentiment Highlights with source attribution, full Cost Comparison, Regional Variations (North, Midlands, South/SW, London, Scotland), Community Discussion Platforms Directory, Notable Recognition (2025–2026), and a Full Source Bibliography (17 entries) — see **[NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)**.

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


-
[4teamwork/ftw.footballchallenge :octocat:](https://github.com/4teamwork/ftw.footballchallenge) - an online football bet game based on plone
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
