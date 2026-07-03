Awesome Series @ Planet Open Data

[World (Countries, Cities, Codes, ...)](https://github.com/planetopendata/awesome-world) • [Football (Clubs, Players, Stadiums, ...)](https://github.com/planetopendata/awesome-football) • [SQLite (Tools, Books, Schemas, ...)](https://github.com/planetopendata/awesome-sqlite)

# Awesome Football   (Open Datasets & Open Source Apps)

A collection of awesome football (national teams, clubs, match schedules, players, stadiums, etc.) datasets

**Contributions welcome. Anything missing? Send in a pull request. Thanks.**

## V3 -  What's News in 2026?

### World Cup 2026
- [Onside World Cup 2026 model outputs](https://onsidearena.com/data) - model predictions (open data); per-match win/draw probabilities, champion odds (10,000-run Monte Carlo simulation) and the full 104-match schedule as CC BY 4.0 CSVs, refreshed through the tournament; includes a [public graded accuracy record](https://onsidearena.com/world-cup-2026/model-record) and a [Kaggle mirror](https://www.kaggle.com/datasets/wr0027/world-cup-2026-predictions-onside-model-outputs)
- [uanalyse World Cup 2026 predictions](https://github.com/uanalyse/world-cup-2026-predictions) - daily, timestamped forecasts published before kickoff; per-match win/draw/loss probabilities and expected goals, plus tournament probabilities (reach each stage, champion) from a 10,000-run Monte Carlo group stage with the knockout bracket solved exactly by dynamic programming (computed, not sampled). Append-only, signed CC BY 4.0 CSVs, refreshed daily through the tournament, with a live [interactive portal](https://uanalyse.co.uk/world-cup-2026). Widely used: 300+ repo clones in two weeks, plus independent bracket and Kicktipp projects building on it.
- [World Cup AI Forecast](https://worldcupaiforecast.com/) - multilingual World Cup 2026 forecast and analysis dashboard with match win probabilities, score predictions, group standings, lineup notes, completed-match backtesting, transparent [methodology](https://worldcupaiforecast.com/methodology-en.html) and [data-source notes](https://worldcupaiforecast.com/data-sources-en.html). Entertainment-only informational analytics.
- [World Cup 2026 Tour schedule dataset](https://ay-worldcup2026.zeabur.app/dataset) - all 104 fixtures with UTC kickoff times, match pages, CSV/JSONL snapshots, a free local-time JSON API, OpenAPI spec, ICS calendar feed, and [Hugging Face](https://huggingface.datasets/abaiii168/world-cup-2026-tour-match-schedule) / [Kaggle](https://www.kaggle.com/datasets/ayworldcup2026/world-cup-2026-tour-match-schedule) mirrors.
- [World Cup 2026 Player Data](https://github.com/risingtransfers/world-cup-2026-data) - all 48 squads (1363 players) with per-90 stats and AI player similarity examples. CC BY 4.0.
- [WC2026 Live Tracker](https://github.com/Krymets/wc2026) - Live scores, goals & cards by minute, group standings, knockout bracket and player stats for all 104 matches. Single HTML file, no dependencies, auto-updates via ESPN API.
- [lefProg/claudial](https://github.com/lefProg/claudial) - a small fun project that lets you see live updates for the 2026 World Cup right in your Claude Code status line.

## V2 -  What's News in 2022?

[**jfjelstul/worldcup**](https://github.com/jfjelstul/worldcup)

The Fjelstul World Cup Database is a comprehensive database about the FIFA World Cup created by Joshua C. Fjelstul, Ph.D. that covers all `21` World Cup tournaments (1930-2018). An update with data on the 2022 World Cup in Qatar will be available soon. The database includes `27` datasets (approximately 1.1 million data points) that cover all aspects of the World Cup.

[**JaseZiv/worldfootballR**](https://github.com/JaseZiv/worldfootballR)

This package is designed to allow users to extract various world football results and player statistics from the following popular football (soccer) data sites:
- FBref
- [Transfermarkt](https://www.transfermarkt.com/)
- [Understat](https://understat.com/)
- [Fotmob](https://www.fotmob.com/)

Since the release of `v0.5.3`, the library now supports very rapid loading of pre-collected data through the use of `load_` functions.

The data available for loading is stored in the `worldfootballR_data` repository. The repo can be found [here](https://github.com/JaseZiv/worldfootballR_data).

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
`WhoScored`_. You get Pandas DataFrames with sensible, matching column names and identifiers across datasets. Data is downloaded when needed and cached locally.

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

## Football Culture & Fan Experiences

_The heart and soul of English football below the professional tiers — community, tradition, and authentic matchday culture at the National League and below._

### Why Non-League Match Days Matter

The **National League** (5th tier of English football) and the wider non-league pyramid (Steps 1–7+, 800+ clubs) represent the heart of grassroots football in England. With ticket prices of £5–£15 compared to £30–£70+ in the top tier, non-league football offers an accessible, community-driven experience that professional football cannot match. In 2025, 12 Step 3 clubs averaged over 1,000 attendance per match.

### 12 Key Match Day Traditions

1. **The Pub Signal** — Pre-match gatherings at local pubs where fans, managers, and even chairmen mingle. The pub serves as the unofficial "team meeting room."
2. **Intimate Grounds** — Small terraced stadiums (500–5,000 capacity) put supporters pitchside, creating an unmatched atmosphere.
3. **Freedom of the Terrace** — No assigned seats; you can stand wherever you like and even "change ends" at half-time.
4. **The Clubhouse / Social Club** — Many grounds have an attached social club where fans, officials, and players mingle freely.
5. **Pie, Mash & Gravy ("Footy Scran")** — Legendary steak and ale pies (£3–4) served in ground-side kiosks. A ritual and core memory for supporters.
6. **The Physical Programme** — A collectible souvenir (£2–5) that directly supports club finances.
7. **Volunteer Spirit** — Clubs often run by volunteers from chairman to groundskeeper; fans sweep terraces, paint lines, and organise fundraisers.
8. **Local Rivalries** — Geographically close clubs produce community-rooted derbies that matter deeply to the towns involved.
9. **Family Inclusion** — Children often allowed onto the pitch at full-time. Free or very cheap admission for under-16s.
10. **Chants & Songs** — Organic, locally-written songs reflecting community identity, often named after local landmarks or beloved club officials.
11. **The Conference Legacy** — The 1979–2004 Football Conference era established a culture of independence and self-governance.
12. **Non-League Day** — An annual event encouraging higher-division supporters to visit their local non-league side, with FSA Away Day Experience Awards recognising the best match day experiences.

### Where Fans Discuss Match Day Culture

| Platform | What It Covers |
|----------|---------------|
| r/nonleaguefootball | Groundhopping culture, family-friendly atmosphere stories, match reports |
| r/nonleague | Broader non-league discussion, culture, and community |
| r/CasualUK | Casual fan experiences and non-league recommendations |
| r/NationalLeague | National League-specific match day experiences and neutral fan guides |
| Nonleaguezone.co.uk | Away day guides, derby coverage, programme collecting |
| NonLeagueMatters forums | National League discussion, away day guides, programme collecting |
| The Non-League Football Paper | In-depth features (Feb 2026: "Perfect Matchday Experience" guide) |
| Football Ground Guide | "Best Away Days in Non-League Football" detailed guides (March 2026) |
| ShuttleOne Network / Energeo Project | Fan culture and community engagement analysis |
| FSA (Football Supporters' Association) | Away Day Experience Awards 2025 |
| When Saturday Comes | Editorial on non-league attendance boom (Feb 2025) |
| Fan Experience Company | "Making Non-League Day Happen Weekly" guide |
| Downhill Second Half / Club 27 blog | Independent non-league match day features |
| Non League Insider | Coverage of non-league's growing popularity |
| TheFans.io | Groundhopping app and UK guide |
| Footbeen.com | National League and non-league groundhopping guides |
| Football Fanbase Forum | Match day experience discussions |
| Fans Focus (fansfocus.com) | Non-league community forums |
| Enterprise National League (Facebook) | Largest fan page for 3 National League divisions |
| Non League Chat (Facebook) | Community for news, experiences, questions |
| Football Forums | Match day experience and ground discussion |

### Notable Recognition

- **FSA Away Day Experience Award 2025 winners**: Falmouth Town, FC Halifax Town, Torquay United, Lewes FC
- **"The Perfect Matchday" guide** — The Non-League Football Paper (Feb 2026)
- **"Why more fans are turning to non-League"** — When Saturday Comes editorial (Feb 2025)
- **Football Ground Guide: "Best Away Days in Non-League Football, Top 5"** (March 2026)
- **FSA Away Day Experience Award 2024**: Multiple non-league grounds recognised

### Cost & Accessibility

| Level | Ticket Price | Typical Attendance |
|-------|-------------|-------------------|
| National League (Step 1) | £10–£15 | 1,000–5,000 |
| National League N/S (Step 2) | £8–£12 | 500–3,000 |
| Steps 3–4 (NLS, NPL) | £5–£10 | 200–1,500 |
| Steps 5–7 (regional) | £3–£7 | 50–800 |
| **Premier League / EFL comparison** | **£30–£70+** | — |

- **Season cost for 20 away matches**: ~£300 (vs £600–£1,400+ in PL/EFL)
- **Food & drink at ground**: £3–7 for a full matchday meal
- **Entry**: Walk up, pay on gate, 20 minutes before kick-off

### Match Day Atmosphere

- **No corporate polish** — no PA announcers, no giant screens, no corporate boxes
- **Pure football** — the absence of commercialisation creates an authentic, passionate atmosphere
- **Every goal feels monumental** — in a 500–600 capacity ground, a screamer genuinely feels world-class
- **Family-friendly** — kids on the pitch, relaxed atmosphere, no deterrents to newcomers

### Post-Match Socialising

The pub visit after the match — discussing what went right, what went wrong, celebrating the goals — is a key part of the ritual. The match doesn't end at the final whistle; it continues in the social space.

### Modern Digital Integration

Despite the old-school atmosphere, non-league fans are increasingly tech-savvy, blending grassroots tradition with live stats, podcasts, social media, ground-tracking apps (**TheFans.io**, **Footbeen.com**), and match-day vlogging on YouTube.

### Supporter Trusts & Club Ownership

Active supporter groups and trusts are common, often playing a formal role in club governance. Many clubs are fan-owned or community-owned through the Supporters Direct model.

### Ground Improvement & Charity Links

Fans frequently volunteer weekends to repaint stands, lay turf, or improve facilities. Non-league clubs also organise charity days, youth coaching clinics, and local outreach — often serving as the largest community institution in town.

### Recommended Reading

1. [The Non-League Football Paper — Guest Posts](https://www.thenonleaguefootballpaper.com/guest-posts/) — Match reports, fan profiles, ground guides, culture features
2. [The Perfect Matchday: A Beginner's Guide](https://www.thenonleaguefootballpaper.com/guest-posts/604687/the-perfect-matchday-a-beginners-guide-to-the-non-league-experience/) — Feb 2026
3. [Why more fans are turning to non-League](https://www.wsc.co.uk/stories/editorial-why-more-fans-are-turning-to-non_leagues-affordable-community-culture/) — WSC Editorial, Feb 2025
4. [Fan Culture in the National League North](https://shuttleone.network/fan-culture-and-community-engagement-in-the-national-league-north/) — ShuttleOne Network
5. [Making Non-League Day Happen Weekly](https://fanexperienceco.com/2021/09/making-non-league-day-happen-weekly/) — Fan Experience Company
6. [Best Away Days in Non-League Football: Top 5](https://footballgroundguide.com/news/best-away-days-in-non-league-football-our-top-5-ranked-from-national-league-to-step-4.html) — Football Ground Guide, March 2026
7. [Non League Insider — How Non-League Has Grown](https://www.nonleagueinsider.com/leagues/how-non-league-has-grown-in-popity/)
8. [FSA Away Day Experience Awards](https://www.thefsa.org.uk/campaigns/away-day-experience-awards/)
9. [Football Ground Guide — Away Days](https://footballgroundguide.com) — Stadium guides, away day tips
10. [Downhill Second Half / Club 27 blog](https://downhillsoccer.com/) — Independent non-league culture

## Football Apps

_Open source apps for match scores, picks, predictions, office pools, and more_

- [worldcup-2014 gem :octocat:](https://github.com/hpoydar/worldcup-2014), [:gem:](https://rubygems.org/gems/worldcup-2014) — provides command line access to World Cup 2014 information and results
- [world_cup_cli gem :octocat:](https://github.com/jameswilliamiii/world_cup_cli), [:gem:](https://rubygems.org/gems/world_cup_cli) — a CLI that provides latest group table standings, scores, and upcoming matches from the 2014 World Cup
- [fatiherikli/worldcup :octocat:](https://github.com/fatiherikli/worldcup) — World cup results for hackers; uses Soccer For Good API
- [Huang-Wei/2014 :octocat:](https://github.com/Huang-Wei/2014)
- [rtopitt/bolao2014 :octocat:](https://github.com/rtopitt/bolao2014) — Bolão PiTTlândia Copa do Mundo 2014
- [rtopitt/bolao :octocat:](https://github.com/rtopitt/bolao) — Bolão Copa 2010
- [threefunkymonkeys/funky-world-cup :octocat:](https://github.com/threefunkymonkeys/funky-world-cup) — a match predictions website that allows you to create groups to play with friends
- [malagant/tipptop :octocat:](https://github.com/malagant/tipptop) — world cup 2010 betting game; W-JAX Challenge
- [soccer_league :octocat:](https://github.com/mrjabba/soccer_league) — a rails application designed to manage soccer leagues, specifically teams, players and their stats
- [standings gem :octocat:](https://github.com/scottluptowski/standings), [:gem:](https://rubygems.org/gems/standings) — view European football standings from your terminal
- [ahs85/bundesliga_predictions :octocat:](https://github.com/ahs85/bundesliga_predictions) — predictions of the Deutsche Bundesliga season 2012/13
- [architv/soccer-cli](https://github.com/architv/soccer-cli) — command line tool for league table standings, match scores and more (in Python)
- [4teamwork/ftw.footballchallenge :octocat:](https://github.com/4teamwork/ftw.footballchallenge) — an online football bet game based on plone
- [sigi/bookie :octocat:](https://github.com/sigi/bookie) — a rails application to manage a soccer betting community or office pool
- [kdungs/tippspiel :octocat:](https://github.com/kdungs/tippspiel) — bet on football games with your friends
- [chipsmachine/bltippspiel :octocat:](https://github.com/chipsmachine/bltippspiel) — Bundesliga betting game (tippspiel)
- [chrenkot/Austrian-Bundesliga :octocat:](https://github.com/chrenkot/Austrian-Bundesliga) — a little open source android app for the Austrian Bundesliga
- [rodmoiolineira/football-graphs :octocat:](https://github.com/rodmoiolineira/football-graphs) — Some visualizations on passing networks
* [Last season comparison](https://compare-last-season.netlify.app), [:octocat:](https://github.com/nurgasemetey/compare-last-season) — Last season comparison tool

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

## Meta

**License**

The awesome list is dedicated to the public domain. Use as you please with no restrictions whatsoever.

**Questions? Comments?**

Yes, you can. More than welcome.
See [Help & Support »](https://github.com/openfootball/help)