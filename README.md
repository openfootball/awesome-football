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

- [World Cup 2026 Tour schedule dataset](https://ay-worldcup2026.zeabur.app/dataset) - all 104 fixtures with UTC kickoff times, match pages, CSV/JSONL snapshots, a free local-time JSON API, OpenAPI spec, dedicated to the public domain.

- [World Cup 2026 Player Data](https://github.com/risingtransfers/world-cup-2026-data) - all 48 squads (1363 players) with per-90 stats and AI player similarity examples. CC BY 4.0.

- [WC2026 Live Tracker](https://github.com/Krymets/wc2026) - Live scores, goals & cards by minute, group standings, knockout bracket and player stats for all 104 matches. Single HTML file, no dependencies, auto-updates via ESPN API.

- [lefProg/claudial](https://github.com/lefProg/claudial) - a small fun project that lets you see live updates for the 2026 World Cup right in your Claude Code status line.

- [TopScorers World Cup 2026](https://www.top-scorers.com/en/mundial-2026) - live top scorers, assists and the Golden Boot race for the 2026 World Cup, plus group standings, results and the full 104-match schedule. Bilingual (EN/ES), free, no signup.

## V2 -  What's News in 2022?

[**jfjelstul/worldcup**](https://github.com/jfjelstul/worldcup)

The Fjelstul World Cup Database is a comprehensive database about the FIFA World Cup created by Joshua C. Fjelstul, Ph.D. that covers all `21` World Cup tournaments (1930-2018).

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

[**somdeep/Statball**](https://github.com/somdeep/Statball)

Football (soccer) stats analyser from top 5 european leagues with data obtained from Fbref and Statsbomb.

[**probberechts/soccerdata**](https://github.com/probberechts/soccerdata)

SoccerData is a collection of wrappers over soccer data from `Club Elo`_, `ESPN`_, `FBref`_, `FiveThirtyEight`_, `Football-Data.co.uk`_, `SoFIFA`_ and `WhoScored`_. You get Pandas DataFrames with sensible, matching column names and identifiers across datasets. Data is downloaded when needed and cached locally.

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

> **New addition — celebrating the community-driven, cultural side of football.**

Non-league football (below the EFL) is some of the most passionate, welcoming, and community-oriented football in England. This section documents the match day traditions, fan experiences, and community discussions that make grassroots football special.

### Why Non-League Match Days Matter

| Factor | Non-League | Premier League |
|--------|-----------|---------------|
| Ticket | £5–£15 | £30–£70+ |
| Entry time | 10–20 min | 45+ min |
| Atmosphere | Intimate, community-driven | Commercial, distant |
| Family-friendly | ✅ Kids run free | ❌ Often restrictive |
| Volunteer-run | ✅ Community-owned | ❌ Corporate |
| Membership | ❌ Not required | ✅ Often needed |

### 13 Core Match Day Traditions

| # | Tradition | Description |
|---|-----------|-------------|
| 1 | **The Pub Signal** | Pre-match pub gatherings where fans, managers, and chairmen mingle freely before walking to the ground |
| 2 | **Intimate Grounds** | Small terraced stadiums (500–5,000) put supporters pitchside — you hear the ball hit the woodwork |
| 3 | **Freedom of the Terrace** | Stand anywhere, change ends at half-time, no barriers between you and the play |
| 4 | **The Clubhouse** | Every ground has its own social hub — cheap drinks, pie & mash, fans and players mingle freely |
| 5 | **Pie, Mash & Gravy** | The "Footy Scran" movement — proper stadium dining with local partnerships, £3–4 for a legendary pie |
| 6 | **Physical Programme** | Paper programmes for a couple of pounds — local history, manager notes, every penny supports the club |
| 7 | **Volunteer Spirit** | Fans maintain pitches, steward matches, and run clubs as community enterprises |
| 8 | **Local Rivalries** | Neighbour-vs-neighbour derbies woven into community identity — the football equivalent of a village cricket match |
| 9 | **Chants & Songs** | Locally written, organic songs born from the stands — multi-generational tradition with local references |
| 10 | **Family Inclusion** | Kids run free, relaxed atmosphere, deliberately family-friendly — no corporate deterrents |
| 11 | **Conference Legacy** | The 1979–2004 Football Conference era established a culture of independence and self-governance |
| 12 | **Non-League Day** | Annual open-doors event encouraging all football fans to visit their local non-league side |
| 13 | **Post-Match Socialising** | The clubhouse stays open for post-match analysis, debate, and camaraderie |

### The 3 A's of Non-League Culture

- **Affordability** — A full matchday for under £10; season for 20 away games ≈ £300
- **Accessibility** — No membership needed; walk up, pay on gate, enter in 10–20 minutes
- **Accountability** — Clubs are community-run; fans know the chairman; volunteers steward; this is the Conference legacy

### 8 Golden Tips for New Fans

1. Attend away games — the true ambassador experience
2. Get a season ticket — same seat, same neighbors, community built over time
3. Engage in digital discussions — forums and fan sites deepen understanding
4. Join a supporters' group — travel packages, meet-and-greets, exclusive events
5. Collect memorabilia — retro kits, signed balls, physical programme collecting
6. Take part in pre-match rituals — the pub, the chant, the walk — form community bonds
7. Volunteer at your club — stewarding, refreshments, pitch maintenance
8. Celebrate Non-League Day — annual event for all football fans to explore grassroots

### Community Discussion Platforms

| Platform | Type | What Fans Discuss |
|----------|------|-------------------|
| [r/nonleaguefootball](https://www.reddit.com/r/nonleaguefootball) | Reddit (30k+) | Groundhopping, family stories, away day reports |
| [r/nonleague](https://www.reddit.com/r/nonleague) | Reddit (40k+) | Broad non-league culture and community |
| [r/NationalLeague](https://www.reddit.com/r/NationalLeague) | Reddit (15k+) | National League match day experiences |
| [r/CasualUK](https://www.reddit.com/r/CasualUK) | Reddit (3M+) | Casual fan experiences, "best away days" threads |
| [NonLeagueMatters](https://www.nonleaguematters.co.uk) | Forum | Away day guides, ground ratings |
| [Nonleaguezone.co.uk](https://www.nonleaguezone.co.uk) | Forum | Away day guides, programme collecting |
| [The Non-League Football Paper](https://www.thenonleaguefootballpaper.com) | Publication + Online | Culture features, "Perfect Matchday" guide |
| [Football Ground Guide](https://footballgroundguide.com) | Publication + Website | "Best Away Days" reviews, ground data |
| [When Saturday Comes](https://www.wsc.co.uk) | Print + Online | "Why more fans are turning to non-League" (Feb 2025) |
| [TheFans.io](https://www.thefans.io) | App | Live stats, ground reviews, groundhopping |
| [Footbeen.com](https://www.footbeen.com) | App | Ground hopping, reviews, photo archives |
| [Football Fanbase Forum](https://www.footballfanbase.co.uk) | Forum | Fan perspectives, match day discussions |
| [FSA Awards](https://www.fsa.org.uk) | Organisation | Away Day Experience Awards (2025) |

### Notable Recognition (2025–2026)

| Award / Feature | Organisation | Details |
|----------------|-------------|---------|
| 🏆 Away Day Experience 2025 Overall | FSA | **Falmouth Town AFC** (Southern League D1 South) |
| 🏆 Away Day Experience 2025 | FSA | **FC Halifax Town**, **Torquay United**, **Lewes FC** |
| 📰 "The Perfect Matchday" guide | Non-League Football Paper (Feb 2026) | Five essentials: Footy Scran, social clubs, programmes, digital, terrace freedom |
| 📰 "Why more fans are turning to non-League" | When Saturday Comes (Feb 2025) | Attendance boom at Steps 3+, cultural draw of grassroots |
| 📰 "Best Away Days in Non-League" | Football Ground Guide (Mar 2026) | Ground-level reviews of 5 top venues |

### Top 5 Recommended Grounds to Visit

| Ground | Club | League | Why Visit |
|--------|------|--------|-----------|
| Bickland Park | Falmouth Town AFC | Southern League D1 South | FSA 2025 winner; Cornish pasties, hillside setting, incredible hospitality |
| The Shay | FC Halifax Town | National League Premier | 14,000 capacity; proper Football League feel; great town access |
| Plainmoor | Torquay United | National League South | English Riviera setting; traditional compact ground |
| The Dripping Pan | Lewes FC | Isthmian League Premier | Foot of South Downs; locally sourced food; craft beer |
| Memorial Ground | Farnham Town | Southern League D1 South | Town-centre location; innovative ticketing; quality food |

### Fan Voices

> *"You're made to feel part of the family"* — r/nonleaguefootball
> *"The atmosphere is intimate, affordable, and refreshingly honest"* — The Non-League Football Paper, 2026
> *"For the price of one PL programme, you can go to 10 non-league grounds"* — r/CasualUK
> *"No anally-retentive stewarding... A meet-up, a beer & a sense of community"* — r/nonleaguefootball

### Cost Comparison

| Level | Ticket | Attendance | Season (20 away) |
|-------|--------|------------|-------------------|
| National League | £10–£15 | 1,000–5,000 | ~£300 |
| NL N/S | £8–£12 | 500–3,000 | ~£240 |
| Steps 3–4 | £5–£10 | 200–1,500 | ~£200 |
| Steps 5–7 | £3–£7 | 50–800 | ~£140 |
| **Premier League** | **£30–£70+** | — | **£1,500–£3,000+** |

### Recommended Reading

1. [**"The Perfect Matchday"**](https://www.thenonleaguefootballpaper.com) — The Non-League Football Paper (Feb 2026) — Five essentials of non-league match day culture
2. [**"Why more fans are turning to non-League"**](https://www.wsc.co.uk) — When Saturday Comes (Feb 2025) — Analysis of the attendance boom
3. [**"Best Away Days in Non-League"**](https://footballgroundguide.com) — Football Ground Guide (Mar 2026) — Top 5 ground-level reviews
4. [**"Fan Culture in the National League North"**](https://energeo-project.eu) — ShuttleOne Network / Energeo (2025) — Deep dive into NPL North fan culture
5. [**"Boosting your National League Fan Experience"**](https://www.thenonleaguefootballpaper.com) — The Non-League Football Paper (2026) — 7 golden tips
6. [**"How Non-League Has Grown in Popularity"**](https://www.nonleagueinsider.co.uk) — Non League Insider (2024) — Drivers of the non-league boom
7. [**"National League Guide"**](https://www.footballfanbase.co.uk) — Football FanBase — Structure, promotion, and supporter culture

### Contributing to This Section

This section is part of the awesome-football project, which is dedicated to the **public domain**. We welcome contributions of:

- **Data**: Attendance statistics, ground data, cost comparisons
- **Documentation**: Match day traditions, fan stories, cultural analysis
- **Links**: New community platforms, publications, apps, awards
- **Corrections**: Updates to existing facts, new sources, broken links

**How to contribute:** Send in a pull request! The project README says: *"Contributions welcome. Anything missing? Send in a pull request. Thanks."*

Community discussion platforms are especially welcome — if you know of a new forum, app, or publication covering non-league match day culture, add it!

---

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

---

## Meta

**License**

The awesome list is dedicated to the public domain. Use as you please with no restrictions whatsoever.

**Questions? Comments?**

Yes, you can. More than welcome.
See [Help & Support »](https://github.com/openfootball/help)
