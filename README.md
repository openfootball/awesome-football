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

---

## ⚽ Football Culture & Fan Experiences

> All content is dedicated to the **public domain** — free to use, share, and build upon.

A comprehensive look at the traditions, experiences, and community discussions that define **National League** and wider non-league football match days — compiled from Reddit, specialist publications, and community forums (2024–2026). Details & full research: [`NON-LEAGUE-MATCHDAY-CULTURE.md`](NON-LEAGUE-MATCHDAY-CULTURE.md).

### The 3 A's of Non-League Football

| Principle | What It Means | PL Equivalent |
|---|---|---|
| **Affordability** | Full match day £10–25 (4–8× cheaper) | £50–148+ |
| **Accessibility** | Walk-on gates, no lotteries, just turn up | Ticket lotteries, membership requirements |
| **Accountability** | Chairman next to you, manager in the bar | VIP boxes, corporate distancing |

### 13 Core Match Day Traditions

1. 🍺 **The Pub Signal** — Fans gather at a local pub, often with club banners and pre-match chants. The pub serves as the unofficial meeting point and ritual starting point.
2. 🚶 **The Walk to the Ground** — A communal stroll to the stadium, often through the heart of the local community, stopping for pies and pints along the way.
3. 🏟️ **The Turnstile Ritual** — Entering the ground together, often through manual turnstiles, as a shared experience of anticipation.
4. 🥞 **The Pie, Mash & Gravy** — The iconic non-league match day meal: a hot pie from the club caterer, washed down with gravy and mushy peas.
5. 🏠 **The Social Club / Clubhouse** — Many non-league clubs have affiliated social clubs where fans gather before and after matches for food, drinks, and conversation.
6. 🏟️ **The Terraces** — Standing on the terraces, close to the pitch, with a real sense of proximity to the action.
7. 📢 **The Manager's Half-Time Chat** — Managers often mingle with fans at half-time, reinforcing the intimate community connection.
8. 👋 **The Away Day Reception** — Non-league away supporters are rarely hostile; rival fans often share a drink and mutual respect after the final whistle.
9. 🔄 **The Loyalty Cycle** — Generational support: grandparents bring grandchildren, creating lasting traditions and lifelong fandom.
10. 🛝 **The Community Connection** — Non-league clubs are deeply embedded in their localities; the club is a community hub, not just a sporting entity.
11. 🍻 **The Pub Finish** — The match day doesn't end at 90 minutes; it finishes at the pub, often with extended discussion over drinks.
12. 🧹 **Groundskeeping Pride** — Fans take visible pride in well-maintained pitches, tidy stands, and a clean, welcoming ground.
13. 🤝 **The 12th Man Spirit** — Volunteer-run operations mean fans double as stewards and programme sellers. Everyone knows everyone.

### Where Fans Discuss Match Days

| Platform | Members | Focus |
|---|---|---|
| [r/nonleaguefootball](https://reddit.com/r/nonleaguefootball) | 30,000+ | Match reports, away day experiences & fan culture discussions |
| [r/nonleague](https://reddit.com/r/nonleague) | 40,000+ | Broader non-league discussion including National League |
| [r/NationalLeague](https://reddit.com/r/NationalLeague) | 15,000+ | National League & National League North community |
| [r/CasualUK](https://reddit.com/r/CasualUK) | 3,000,000+ | Frequently features non-league away day recommendations |
| [NonLeagueMatters](https://nationalleague.co.uk) | Long-running | Forum with dedicated National League discussion threads |
| [FootballFanbase Forum](https://footballfanbase.com) | — | Community discussions on clubs, match days & fan culture |
| [TheFans.io](https://thefans.io) | — | Fan community platform connecting football supporters |

### Fan Sentiment (2024–2026)

- *"Non-league football forges a connection you simply don't find in the top divisions. It has nothing to do with glory or riches. It's about belonging."* — The Non-League Football Paper
- *"55% of Premier League fans are now open to attending non-league matches."* — LiveScore NL Fan Survey 2026
- *"It's about belonging, not glory."* — Community consensus

### Key Stats

| Metric | Non-League | Premier League |
|---|---|---|
| Match ticket | £5–15 | £30–100+ |
| Full match day cost | £10–25 | £50–148+ |
| Average stadium capacity | 500–3,000 | 20,000–60,000+ |
| Distance to ground (typical) | Walking distance | Car/journey required |
| Fan–player interaction | Common (pub, social club) | Rare (VIP/ticket office) |
| Post-match socialising | Pub, social club, grilling | Locked in car park |

### Non-League Match Day Experience Articles & Guides

- [The Perfect Matchday: A Beginner's Guide to the Non-League Experience](https://www.thenonleaguefootballpaper.com/guest-posts/604687/the-perfect-matchday-a-beginners-guide-to-the-non-league-experience/) — A comprehensive guide to the authentic, affordable, and intimate non-league match day
- [Passion Beyond the Premier League: Non-League Football Fan Engagement](https://www.thenonleaguefootballpaper.com/guest-posts/478864/passion-beyond-the-premier-league-non-league-football-fan-engagement/) — How non-league fans infuse every match day with passion and a sense of belonging
- [Fan Culture in the National League North: A Deep Dive](https://energeo-project.eu/fan-culture-in-the-national-league-north-a-deep-dive/) — Exploring the raw forms of football fandom in the lower leagues
- [The Magic of Non-League](https://pa-training.shorthandstories.com/the-magic-of-non-league/) — Stories from the non-league pyramid, including Non-League Day initiatives
- [Boosting Your National League Fan Experience: 7 Golden Tips](https://www.thenonleaguefootballpaper.com/guest-posts/443731/boosting-your-national-league-fan-experience-7-golden-tips/) — Practical tips for immersing yourself in non-league match day traditions
- [Growing a fan base as a Non-League football club in 2026](https://sports.yahoo.com/articles/growing-fan-non-league-football-111704723.html) — How clubs can grow attendances through community ties and unforgettable match day experiences
- [The Matchday Experience: Why Atmosphere Still Drives Attendance](https://fanbaseclub.com/theclubhouse/matchday-experience-drives-attendance) — How clubs like Dulwich Hamlet built followings through the match day environment
- [Non-League Football Clubs: Boost Fan Experience & Matchday Revenue](https://matchcentre.co.uk/blog/optimising-the-fan-experience-a-practical-guide-for-non-league-clubs) — Practical guide for clubs to transform their fan experience
- [National League Guide: Structure, Promotion And Clubs](https://www.footballfanbase.com/national-league-complete-guide/) — Complete guide covering fan culture and the English football pyramid

### Top 5 2026 Recommended Away Days

| # | Club | Ground | League | Why Visit? |
|---|---|---|---|---|
| 1 | **Falmouth Town AFC** | Bickland Park | Southern League Div 1 South (L8) | FSA Away Day Winner 2025; Cornish pasties; hillside views; holiday-like atmosphere |
| 2 | **FC Halifax Town** | The Shay | National League Premier (L5) | 14,000 capacity; Football League feel; walkable town centre; loudest crowd in non-league |
| 3 | **Torquay United** | Plainmoor | National League South (L6) | English Riviera; beach + football; lively terrace culture and coastal getaway |
| 4 | **Farnham Town** | Memorial Ground | Isthmian League Div 1 South (L7) | Rare town-centre location; innovative pricing; quality food; fan-first approach |
| 5 | **Lewes FC** | The Dripping Pan | Isthmian League Div 1 South (L7) | South Downs setting; community-run; equality initiatives; craft beer |

### Breaking Insulation Gap — Non-League Perception Gap

- **4 in 10** Premier League fans cannot name their local non-league club — the single biggest barrier to attendance
- **55%** of PL fans are now open to attending non-league (up from 49%)
- The biggest incentive for first-time attendance: **an invitation from a friend or family member**
- [Non-League Day 2026](https://www.thenationalleague.org.uk/) — 15th Anniversary (28th March 2026), featuring £230.6M in PL funding to NL + grassroots football

---

## Football Apps

_Open source apps for match scores, picks, predictions, office pools, and more_
