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

[jfjelstul/worldcup](https://github.com/jfjelstul/worldcup)

The Fjelstul World Cup Database is a comprehensive database about the FIFA World Cup created by Joshua C. Fjelstul, Ph.D. that covers all `21` World Cup tournaments (1930-2018). An update with data on the 2022 World Cup in Qatar will be available soon. The database includes `27` datasets (approximately 1.1 million data points) that cover all aspects of the World Cup.

[JaseZiv/worldfootballR](https://github.com/JaseZiv/worldfootballR)

This package is designed to allow users to extract various world football results and player statistics from the following popular football (soccer) data sites:

- FBref
- [Transfermarkt](https://www.transfermarkt.com/)
- [Understat](https://understat.com/)
- [Fotmob](https://www.fotmob.com/)

Since the release of `v0.5.3`, the library now supports very rapid loading of pre-collected data through the use of `load_` functions.

[dcaribou/transfermarkt-datasets](https://github.com/dcaribou/transfermarkt-datasets)

this project aims for three things:

1. Acquire data from transfermarkt website using the [trasfermarkt-scraper](https://github.com/dcaribou/transfermarkt-scraper).
2. Build a **clean, public football (soccer) dataset** using data in 1.
3. Automatate 1 and 2 to **keep these assets up to date** and publicly available on some well-known data catalogs.

Checkout this dataset also in: 
[Kaggle](https://www.kaggle.com/davidcariboo/player-scores), 
[data.world](https://data.world/dcereijo/player-scores),
[streamlit](https://transfermarkt-datasets.herokuapp.com/),
[awesome-public-datasets](https://github.com/awesomedata/apd-core/blob/master/core/Sports/Transfermarkt-Datasets.yml)

[somdeep/Statball](https://github.com/somdeep/Statball)

Football (soccer) stats analyser from top 5 european leagues with data obtained from Fbref and Statsbomb.

Fbref : https://fbref.com/en/comps/Big5/Big-5-European-Leagues-Stats

Statsbomb : https://statsbomb.com/

[probberechts/soccerdata](https://github.com/probberechts/soccerdata)

SoccerData is a collection of wrappers over soccer data from `Club Elo`_, `ESPN`_, `FBref`_, `FiveThirtyEight`_, `Football-Data.co.uk`_, `SoFIFA`_ and `WhoScored`_. You get Pandas DataFrames with sensible, matching column names and identifiers across datasets. Data is downloaded when needed and cached locally.

To learn how to install, configure and use SoccerData, see the `Quickstart guide <https://soccerdata.readthedocs.io/en/latest/usage.html>`__. For documentation on each of the supported data sources, see the `example notebooks <https://soccerdata.readthedocs.io/en/latest/datasources/>`__ and `API reference <https://soccerdata.readthedocs.io/en/latest/reference/>`__.

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

_New! Community-driven documentation on match day traditions, fan culture, and the non-league experience. National League & wider non-league coverage for 2026._

This section documents the rich match day culture, traditions, and community experiences of England's National League and wider non-league pyramid — from the everyday rituals that define a Saturday afternoon to the awards and recognition that celebrate the best of grassroots football.

### The 3 A's of Non-League Football

| Principle | What It Means |
|-----------|---------------|
| **Affordability** | A full away day costs £25–44 (vs £70–148 in the Premier League) — a 4–8× saving |
| **Accessibility** | Walk-on gates, no ticket lotteries, no membership queues — just turn up |
| **Accountability** | The chairman sits next to you; the manager is in the bar at full time |

Non-league football is 4–8× cheaper than the Premier League, thriving on intimacy rather than scale. With 73% of non-league fans attending in person (vs 21% of PL fans) and only 23% caring primarily about results (vs 69% of PL fans), the non-league experience is about community, atmosphere, and belonging — not just the scoreline.

### The 13 Traditions That Define Non-League Match Days

1. **The Pub Signal** — Informal pre-match gathering at the local pub
2. **The Walk to the Ground** — Communal stroll through town streets building anticipation
3. **The Turnstile Ritual** — Paper programme and ticket at the turnstile — analog football at its last stand
4. **The Pie, Mash & Gravy** — The culinary centrepiece, often from local bakeries
5. **The Social Club / Clubhouse** — Where fans, officials, and players mingle freely
6. **The Terraces** — Standing where you like, changing ends at half-time, no barriers
7. **The Manager's Half-Time Chat** — Personal, immediate tactical discussion with the crowd
8. **The Post-Match Digestion** — Lingering on the terraces after the final whistle
9. **The Pub Finish** — The after-game pints where the real debate happens
10. **The Away Day Reception** — Clubs going the extra mile for visiting supporters
11. **The Community Connection** — Clubs that *are* communities, not just based in them
12. **The Loyalty Cycle** — Following through thick and thin, season after season
13. **The 12th Man Spirit** — Dedicated volunteer stewards, groundsmen, and bar staff who are fans first

### Fan Voices

> *"Walk into any non-league ground on a Saturday afternoon and you'll see it: handshakes at the gate, familiar nods at the bar, and someone talking tactics over a pint of bitter."* — The Non-League Football Paper, 2025

> *"Non-league football forges a connection you simply don't find in the top divisions. It has nothing to do with glory or riches. It's about belonging."* — The Non-League Football Paper, 2025

> *"The intimacy of non-league is what you don't get anywhere else. You stand on the sidelines watching a game and you feel like you're a part of it."* — William King, Club MD, Hampton & Richmond FC

> *"You don't have to wait on a season ticket list or win a raffle to get to see your team play. You just turn up."* — The Non-League Football Paper, 2025

> *"I actually think the smaller teams are more entertaining than the Premier League. I've watched FC United and AFC Wimbledon and there's nothing like it."* — Eidur Gudjohnsen, Chelsea legend

### Key Stats at a Glance

| Metric | Value |
|--------|-------|
| Average non-league away day cost | £25–44 |
| Average Premier League away day cost | £70–148 |
| Non-league is ___times cheaper___ | 4–8× |
| Non-league fans attending in person | 73% (vs 21% for PL fans) |
| PL fans open to non-league (2026) | 55% (up from 49% in 2025) |
| Only care about the result | 23% of NL fans vs 69% of PL fans |
| Non-league fans choosing club for local ties | 42% vs 13% hereditary in Pro football |
| r/nonleaguefootball members | 30,000+ (up 40%+ since 2024) |
| Non-League Day 2026 | 15th anniversary (28th March) |
| Record NL weekly crowds (pre-pandemic) | Nearly 65,000 (2022) |
| National League Trust annual investment | £1.2M from PL & PFA |

### Notable Recognition (2025–2026)

| Award | Winner | Year |
|-------|--------|------|
| FSA Away Day Experience of the Year | **Falmouth Town AFC** (Bickland Park, Cornwall) | 2025 |
| FSA Away Day Experience Awards | Annual recognition of best all-round matchday experience | 2025 |
| FGG Best Away Days #1 | Falmouth Town — Cornish coast, pasties, hillside ground | 2026 |
| FGG Best Away Days #2 | FC Halifax Town — The Shay, classic terrace culture | 2026 |
| FGG Best Away Days #3 | Torquay United — Plainmoor, English Riviera | 2026 |
| FGG Best Away Days #4 | Farnham Town — Memorial Ground, supporter-first innovation | 2026 |
| FGG Best Away Days #5 | Lewes FC — The Dripping Pan, South Downs scenery | 2026 |
| LiveScore NL Fan Survey | 10-year high attendance in NL South & Isthmian Premier | 2026 |

### Recommended 2026 Away Days

1. **Falmouth Town** (Bickland Park) — FSA Award winner, Cornish coast pasties, hillside ground with brilliant vantage points
2. **FC Halifax Town** (The Shay) — 14,000-capacity classic old ground, Halifax town centre nearby, proper football vibe
3. **Torquay United** (Plainmoor) — The English Riviera, beaches and seaside pubs, traditional compact ground
4. **Farnham Town** (Memorial Ground) — Town-centre location, quality food, innovative ticket pricing, model for supporter-first football
5. **Lewes FC** (The Dripping Pan) — At the foot of the South Downs, locally sourced food, craft beer, non-league done differently

### Where Supporters Discuss Match Days

| Platform | Focus | URL |
|----------|-------|-----|
| r/nonleaguefootball | General non-league discussion | [reddit.com/r/nonleaguefootball](https://www.reddit.com/r/nonleaguefootball) |
| r/nonleague | Broader non-league | [reddit.com/r/nonleague](https://www.reddit.com/r/nonleague) |
| r/NationalLeague | National League (Step 1) | [reddit.com/r/NationalLeague](https://www.reddit.com/r/NationalLeague) |
| NonLeagueMatters | Dedicated non-league forum | [nonleaguematters.co.uk](https://www.nonleaguematters.co.uk) |
| TheFans.io | Football fan forum | [thefans.io](https://thefans.io) |
| Football Fanbase Forum | Community discussions | [footballfanbase.com](https://www.footballfanbase.com) |
| Non League Chat (FB) | Largest non-league FB group | [facebook.com/groups/nonleaguechat](https://www.facebook.com/groups/nonleaguechat) |

### Recommended Reading

- **[The Perfect Matchday: A Beginner's Guide to the Non-League Experience](https://www.thenonleaguefootballpaper.com/guest-posts/604687/the-perfect-matchday-a-beginners-guide-to-the-non-league-experience/)** — The Non-League Football Paper, 2026 (cover-from-pub-signal-to-terraces-to-pub-finish)
- **[Best Away Days in Non-League: Our Top 5](https://footballgroundguide.com/news/best-away-days-in-non-league-football-our-top-5-ranked-from-national-league-to-step-4.html)** — Football Ground Guide, 2026 (Falmouth, Halifax, Torquay, Farnham, Lewes)
- **[The Magic of Non-League](https://pa-training.shorthandstories.com/the-magic-of-non-league/)** — PA Training, 2025 (Hampton & Richmond FC community inclusion, Movember sponsorship, attendances)
- **[Why is non-league more popular after the pandemic?](https://www.mancunianmatters.co.uk/sport/17012022-why-is-non-league-more-popular-after-the-pandemic/)** — Mancunian Matters, 2022 (price, quality, matchday experience, lockdown impact)
- **[LiveScore NL Fan Survey](https://www.livescore.com/en/media/non-league-fan-survey/)** — LiveScore, 2026 (55% of PL fans open to non-league, 73% attend in person)
- **[Non-League Football in the UK](https://vergemagazine.co.uk/non-league-football-in-the-uk-livescore-survey-reveals-why-fans-love-the-grassroots-game/)** — Verge Magazine, 2026 (community-driven fandom, hereditary vs local ties, visibility gap)

### Full Research Document

For the complete deep dive — including regional variations, full cost comparison tables, expanded Fan Sentiment Highlights with 15+ source citations, detailed away day profiles, and a full post-pandemic resurgence analysis — see:

[:scroll: **NON-LEAGUE-MATCHDAY-CULTURE.md**](NON-LEAGUE-MATCHDAY-CULTURE.md)

<details>
<summary><b>📋 Quick peek: The Perfect Match Day Timeline</b></summary>

| Time | Phase | Experience |
|------|-------|------------|
| **11:00** | The Pub Signal | Match day begins — team news debated over a pint |
| **11:30** | The Walk to the Ground | Communal stroll through familiar streets |
| **12:00** | Turnstile Ritual | Buy programme, stamp ticket, first pint |
| **12:30** | The Social Club | Pie, mash, and gravy; warm-up entertainment |
| **13:00** | Kick-off | 90 minutes of pure, unfiltered football |
| **14:45** | Half-Time | Manager's chat, tactical debate, swap ends |
| **15:15** | Second Half | The drama unfolds |
| **15:45** | The Pub Finish | After-game pints, post-match analysis |
| **17:00** | The Walk Home | Already looking forward to next Saturday |

</details>

## Football Apps

_Open source apps for match scores, picks, predictions, office pools, and more_

- [worldcup-2014 gem :octocat:](https://github.com/hpoydar/worldcup-2014), [:gem:](https://rubygems.org/gems/worldcup-2014) - provides command line access to World Cup 2014 information and results
- [world_cup_cli gem :octocat:](https://github.com/jameswilliamiii/world_cup_cli), [:gem:](https://rubygems.org/gems/world_cup_cli) - a command line interface that provides you the latest group table standings, scores, and see upcoming matches from the 2014 World Cup
- [fatiherikli/worldcup :octocat:](https://github.com/fatiherikli/worldcup) - World cup results for hackers; uses Soccer For Good API
- [Huang-Wei/2014 :octocat:](https://github.com/Huang-Wei/2014)
- [rtopitt/bolao2014 :octocat:](https://github.com/rtopitt/bolao2014) - Bolão PiTTlândia Copa do Mundo 2014
- [rtopitt/bolao :octocat:](https://github.com/rtopitt/bolao) - Bolão Copa 2010
- [threefunkymonkeys/funky-world-cup :octocat:](https://github.com/threefunkymonkeys/funky-world-cup) - a match predictions website for the FIFA World Cup
- [malagant/tipptop :octocat:](https://github.com/malagant/tipptop) -  world cup 2010 betting game
- [soccer_league :octocat:](https://github.com/mrjabba/soccer_league) - a rails application designed to manage soccer leagues
- [standings gem :octocat:](https://github.com/scottluptowski/standings), [:gem:](https://rubygems.org/gems/standings) - view European football standings from your terminal
- [architv/soccer-cli](https://github.com/architv/soccer-cli) - command line tool for league table standings, match scores and more
- [4teamwork/ftw.footballchallenge :octocat:](https://github.com/4teamwork/ftw.footballchallenge) - an online football bet game
- [sigi/bookie :octocat:](https://github.com/sigi/bookie) - a rails application to manage a soccer betting community
- [kdungs/tippspiel :octocat:](https://github.com/kdungs/tippspiel) - bet on football games with your friends
- [chipsmachine/bltippspiel :octocat:](https://github.com/chipsmachine/bltippspiel) - Bundesliga betting game
- [chrenkot/Austrian-Bundesliga :octocat:](https://github.com/chrenkot/Austrian-Bundesliga) - a live scoreboard plugin for the Austrian league
- [sortiz /soccer_cli :octocat:](https://github.com/sortiz/soccer_cli) - CLI to check football results

## Football Data

_Connectors, scrapers, and broadcasting services_

- [openfootball/countries :octocat:](https://github.com/openfootball/countries)
- [openfootball/competitions :octocat:](https://github.com/openfootball/competitions)
- [openfootball/config :octocat:](https://github.com/openfootball/config)
- [openfootball/events :octocat:](https://github.com/openfootball/events)
- [openfootball/geo :octocat:](https://github.com/openfootball/geo)
- [openfootball/goals :octocat:](https://github.com/openfootball/goals)
- [openfootball/lineups :octocat:](https://github.com/openfootball/lineups)
- [openfootball/matches :octocat:](https://github.com/openfootball/matches)
- [openfootball/players :octocat:](https://github.com/openfootball/players)
- [openfootball/stages :octocat:](https://github.com/openfootball/stages)
- [openfootball/standings :octocat:](https://github.com/openfootball/standings)
- [openfootball/var :octocat:](https://github.com/openfootball/var)
- [openfootball/languages :octocat:](https://github.com/openfootball/languages)
