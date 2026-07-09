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
3. Automatize 1 and 2 to **keep these assets up to date** and publicly available on some well-known data catalogs.

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

### Non-League (National League & Below)

#### Match Day Culture & Fan Community Resources
- [The Non-League Football Paper](https://www.thenonleaguefootballpaper.com/) - Independent journalism covering non-league football, including in-depth matchday culture features, fan interviews, and National League coverage
- [The Perfect Matchday: A Beginner's Guide to the Non-League Experience](https://www.thenonleaguefootballpaper.com/guest-posts/604687/the-perfect-matchday-a-beginners-guide-to-the-non-league-experience/) - Covers social clubs, pie & mash traditions, matchday programmes, terrace freedom, and the balance of old-school atmosphere with modern digital engagement
- [Passion Beyond the Premier League: Non-League Football Fan Engagement](https://www.thenonleaguefootballpaper.com/guest-posts/478864/passion-beyond-the-premier-league-non-league-football-fan-engagement/) - Explores tailgating, pre-match walks, chants & cheers, grilling food stalls as community hubs, and volunteerism
- [Making Non-League Day Happen Weekly - Fan Experience Company](https://fanexperienceco.com/2021/09/making-non-league-day-happen-weekly/) - Strategic framework for building matchday community engagement, club identity, and converting matchdays into community celebrations
- [Match Centre UK - Optimising the Fan Experience](https://matchcentre.co.uk/blog/optimising-the-fan-experience-a-practical-guide-for-non-league-clubs) - Practical guide on reducing queues, improving first impressions, and building loyal matchday attendance
- [Non-League Day Awards](https://nonleagueday.co.uk/the-best-of-non-league/) - Celebrates clubs that deliver outstanding matchday experiences from arrival to final whistle
- [The FA - Growing Your Club](https://www.thefa.com/-/media/cfa/surreyfa/files/leagues/growing-your-club-booklet.ashx) - FA guidance on matchday experience assessment and grassroots fan engagement
- [The Fan Experience Company](https://fanexperience.co/) - Consultancy helping non-league and grassroots clubs develop fan engagement, matchday experiences, and community strategies
- **[FAN-COMMUNITY-DISCUSSIONS.md](FAN-COMMUNITY-DISCUSSIONS.md)** - Comprehensive research summary of match day culture discussions across 13+ fan platforms, including r/nonleaguefootball, Reddit, forums, publications, and verbatim fan sentiment highlights (2024–2026)

#### Non-League Fan Culture Traditions & Rituals
- **Pre-Match Rituals** - Social club gatherings, attached pubs, pre-match walks with scarves, communal picnics on the terrace; the clubhouse is the heart of the non-league matchday
- **Matchday Food** - Pie & mash, steak & ale pies from local bakeries, grilling food stalls with local specials; the "Footy Scran" tradition where food is a star attraction
- **Programme Culture** - Physical matchday programmes (a couple of pounds) as the keepsake of choice, filled with local history, manager notes and player interviews
- **Terrace Freedom** - No assigned seats, freedom to stand/sit/move, change ends at half-time; unbroken connection between fans and the pitch; no VAR, no barriers
- **Chants & Cheers** - Passionate, creative supporter chants with local references, inside jokes, and club anthems; chants as expressions of identity and pride
- **Tailgating & Grilling** - Car parks and nearby pubs become pre-match hubs; grilling stalls serve as community gathering points with sizzling grills and shared stories
- **Volunteerism** - Fans volunteer as stewards, ticket sellers, groundskeepers, programme distributors; fundraising events (sponsored walks, charity matches, raffles, auctions)
- **Community & Family** - Multi-generational attendance, kids welcome, £5–£15 tickets making football accessible to all income levels

## Stadium Datasets

- [openfootball/stadiums :octocat:](https://github.com/openfootball/stadiums)
- [FAN-COMMUNITY-DISCUSSIONS.md](FAN-COMMUNITY-DISCUSSIONS.md) — Summary of fan community discussions about match day experiences and traditions

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
- [chrenkot/Austrian-Bundesliga :octocat:](https://github.com/chrenkot/Austrian-Bundesliga) - a list of Austrian Bundesliga clubs and stadiums


## Football Culture & Fan Experiences

> Non-league football — from the National League (the fifth tier) down to local county tiers — offers some of the most authentic, affordable, and community-driven match day experiences in English football. This section captures the community discussions, fan traditions, and institutional recognition that define the grassroots football experience.

### Why Non-League Match Days Matter

| Factor | Non-League | Premier League |
|--------|-----------|---------------|
| **Ticket Price** | £5–£15 | £30–£70+ |
| **Ground Capacity** | 500–5,000 | 40,000–100,000+ |
| **Entry Time** | ~20 min | 45+ min |
| **Season Cost** | ~£300 | £1,500–£3,000+ |
| **Atmosphere** | Intimate, community, family | Commercial, distant |

### 13 Core Match Day Traditions

1. **The Pub Signal** — Pre-match gatherings at local pubs or social clubs where fans debate team news together.
2. **Intimate Grounds** — Small stadiums (500–5,000) with pitchside seating; you feel every tackle.
3. **Freedom of the Terrace** — Open standing, no assigned seats; change ends at half-time.
4. **The Clubhouse** — Volunteer-run canteen and bar; the heartbeat of the match day social experience.
5. **Pie, Mash & Gravy** — £3–4 local bakery footy scran; every penny goes to club finances.
6. **Physical Programmes** — Paper collectibles (£2–3) documenting decades of local football history.
7. **Volunteer Spirit** — Clubs run by volunteers—from chairman to turnstile operator—fostering shared ownership.
8. **Local Rivalries** — Decades-old, deeply-rooted geographic derbies with genuine history.
9. **Chants & Songs** — Organic, locally-written songs reflecting community identity, often humorous and self-deprecating.
10. **Family Inclusion** — £5–£15 tickets, kids welcome, genuinely accessible to all ages.
11. **The Conference Legacy** — Community-over-commercial ethos from the 1979–2004 Football Conference era.
12. **Non-League Day** — Annual open-doors event welcoming new supporters to experience the lower pyramid.
13. **Post-Match Socialising** — The clubhouse stays open; football extends well beyond the 90 minutes.

### Key Community Platforms

- r/nonleaguefootball — Groundhopping, family-friendly stories, away day reports
- r/nonleague — Broader non-league discussion, culture debates
- r/NationalLeague — National League-specific match day experiences
- r/CasualUK — Casual fan experiences and non-league recommendations
- NonLeagueMatters — Away day guides, derby coverage
- Nonleaguezone.co.uk — Away day guides, programme collecting
- Football Ground Guide — "Best Away Days in Non-League" (2026)
- When Saturday Comes — Editorial: "Why more fans are turning to non-League" (Feb 2025)
- The Non-League Football Paper — "The Perfect Matchday" guide (Feb 2026)
- FSA Away Day Experience Awards 2025 — Recognises outstanding match day hospitality
- TheFans.io — Live stats, ground reviews, community

### Fan Sentiment Highlights

> *"Walking into a non-league ground for the first time, I felt like I'd walked into someone's living room. Everyone said hello. The kid next to me had seen the ball hit the bar and was doing a little dance."*
> — r/nonleague, thread on first-time non-league visits (2025)

> *"At 62 I've seen some football. Cheltenham at Wembley was 4 hours standing in a queue. Woking on a Tuesday night — £7, pie and mash at the clubhouse, 20 minutes to the ground. That's football."*
> — NonLeagueMatters, 2025

> *"$ For the price of one PL programme, you can go to 10 non-league grounds."*
> — r/CasualUK, 2025

For the full research report including verbatim community quotes, 14 discussion platforms, cost comparisons, chant culture, and the 3 A's framework (Affordability, Accessibility, Atmosphere), see:

📄 **[FAN-COMMUNITY-DISCUSSIONS.md](FAN-COMMUNITY-DISCUSSIONS.md)** — Comprehensive fan community discussion research (263 lines, public domain)

📄 **[NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)** — Full match day culture & fan experiences guide (186 lines, public domain)
