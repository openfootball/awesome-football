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
- [World Cup 2026 Tour schedule dataset](https://ay-worldcup2026.zeabur.app/dataset) - all 104 fixtures with UTC kickoff times, match pages, CSV/JSONL snapshots, a free local-time JSON API, OpenAPI spec, ICS calendar feed, and [Hugging Face](https://huggingface.co/datasets/abaiii168/world-cup-2026-tour-match-schedule) / [Kaggle](https://www.kaggle.com/datasets/ayworldcup2026/world-cup-2026-tour-match-schedule) mirrors.

- [World Cup 2026 Player Data](https://github.com/risingtransfers/world-cup-2026-data) - all 48 squads (1363 players) with per-90 stats and AI player similarity examples. CC BY 4.0.

- [WC2026 Live Tracker](https://github.com/Krymets/wc2026) - Live scores, goals & cards by minute, group standings, knockout bracket and player stats for all 104 matches. Single HTML file, no dependencies, auto-updates via ESPN API.

- [lefProg/claudial](https://github.com/lefProg/claudial) - a small fun project that lets you see live updates for the 2026 World Cup right in your Claude Code status line.

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
`ESPN`_, `FBref`_, `FiveThirtyEight`_, `Football-Data.co.uk`_, `SoFIFA`_ and `WhoScored`_. You get Pandas DataFrames with sensible, matching column names and identifiers across datasets. Data is downloaded when needed and cached
locally. To learn how to install, configure and use SoccerData, see the
`Quickstart guide <https://soccerdata.readthedocs.io/en/latest/usage.html>`__. For documentation on each of the supported
data sources, see the `example notebooks <https://soccerdata.readthedocs.io/en/latest/datasources/>`__ and `API reference <https://soccerdata.readthedocs.io/en/latest/reference/>`__.













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

_A curated collection of resources on non-league and National League match day culture, traditions, and community experiences in English football._

See the dedicated research document: **[NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)** for the full summary.

### Why Non-League Match Days Matter

England's National League and wider non-league pyramid -- covering Steps 1-7 of the English football system -- includes **800+ clubs** across tiers from the National League (5th tier) down to county leagues. These clubs represent a unique cultural phenomenon: grassroots, community-driven football that has been revitalising local communities since the 1979 Football Conference era. Here is an overview of what makes the non-league match day experience distinctive.

#### Core Match Day Traditions

- **The Pub Signal** -- Pre-match gatherings at local pubs where fans, chairmen, and even managers mingle
- **Intimate Grounds** -- Small terraced stadiums (typically 500-5,000 capacity) putting supporters pitchside, creating an unmatched, immersive atmosphere
- **Freedom of the Terrace** -- No assigned seats; you can stand wherever you like and even switch ends at half-time to follow the action
- **The Clubhouse / Social Club** -- A pre-match community hub where fans, club officials, and sometimes players mingle freely over cheap drinks. This is not corporate hospitality -- it is a place of genuine belonging.
- **The Physical Programme** -- A collectible souvenir for a couple of pounds that directly supports club finances and preserves local history
- **Non-League Day** -- Annual event (during international breaks) encouraging higher-division supporters to visit their local non-league side

#### Food & Culinary Culture

The iconic **"Footy Scran"** tradition is a cornerstone of the non-league experience. Local bakeries serve legendary steak and ale pies, often accompanied by creamy mash and rich gravy. A proper non-league pie for PS3-4 with a bacon roll will often surpass anything found in a Premier League stadium. The food is a point of local pride and identity, reflecting the regional character of each ground.

#### Volunteer Spirit & Community Ownership

Many non-league clubs are sustained entirely by volunteers -- fans steward, tend the bar, maintain the pitch, and drive the club forward. Community ownership models (via Supporters Direct / Fans United) give supporters a formal role in club governance. Fans regularly volunteer weekends to repaint stands, lay turf, and improve facilities, creating a genuine sense of shared ownership.

#### Cost & Accessibility

Non-league tickets are typically PS5-15, making football genuinely accessible for families and supporters on all budgets. A full season of 20 away matches might cost PS300 -- compared to a single Premier League away day that can exceed that. No membership schemes, no ticket lotteries, no premium pricing -- just walk up and go.

#### Match Day Atmosphere

No PA announcers, no giant screens, no corporate boxes -- just pure football. The absence of commercial polish creates an authentic, passionate atmosphere. Every goal feels like a monumental event; every clean sheet is celebrated like a World Cup win. Players walk through the same exit as fans after the match, and can be chatted with in the ground-side clubhouse or car park.

#### Local Identity & Rivalries

Non-league derbies are deeply personal -- geographically close clubs with community-rooted rivalries where the towns themselves take pride. Club songs and chants are organic and local, reflecting neighbourhood identity rather than copied from the top flight.

#### The Conference Legacy

The 1979-2004 Football Conference era established a culture of independence and self-governance that still permeates the modern non-league pyramid -- a philosophy that prioritises the sport and community over commercial pressures. The **National League System** encompasses 800+ clubs across Steps 1-7, with the National League (Step 1) serving as the fifth tier of English football, below the Premier League, Championship, League One, and League Two.

#### Modern Digital Integration

Despite the old-school atmosphere, modern non-league fans are increasingly tech-savvy:
- Checking live stats on phones during the match
- Following "as it stands" league tables at half-time
- Blending grassroots tradition with digital engagement -- podcasts, social media, live-tweeting
- Using apps like **TheFans.io** to track grounds and connect with the community

The result is a hybrid culture: old-school atmosphere with modern connectivity.

#### Where Fans Discuss Match Day Culture Online

| Source | Description |
|--------|-------------|
| [r/nonlagefootball](https://www.reddit.com/r/nonleaguefootball/) | Groundhopping culture, family-friendly atmosphere stories, match day vlogs |
| [r/nonlage](https://www.reddit.com/r/nonleague/) | Broader non-league discussion, culture, and community |
| [r/NationalLeague](https://www.reddit.com/r/NationalLeague/) | National League-specific match day experiences, neutral fan guides |
| [r/CasualUK](https://www.reddit.com/r/CasualUK/) | Casual fan experiences and non-league recommendations |
| [Nonleaguezone.co.uk](https://www.nonleaguezone.co.uk/) | Away day guides, derby coverage, programme collecting forums |
| [NonLeagueMatters forums](https://www.nonleaguematters.co.uk/forums/) | Away day guides, derby coverage, community discussions |
| [Football Ground Guide](https://footballgroundguide.com/) | Best away days in non-league football, detailed ground guides |
| [Downhill Second Half / Club 27 blog](https://downhillsecondhalf.com/) | Independent non-league coverage and match day features |
| [TheFans.io](https://thefans.io/) | Groundhopping app and UK guide for beginners |
| [Footbeen.com](https://footbeen.com/) | National League and non-league groundhopping guides |

#### Notable Recognition

- **FSA Away Day Experience Award 2025**: Falmouth Town, FC Halifax Town, Torquay United, Lewes FC
- **"Perfect Matchday" guide** (The Non-League Football Paper, Feb 2026): Documents the seven essentials -- social club, food culture, programmes, terrace freedom, and digital integration
- **WSC February 2025 editorial**: "Why more fans are turning to non-League's affordable community culture" -- documents the attendance boom and modern appeal

#### Recommended Reading

| # | Resource | Description |
|---|----------|-------------|
| 1 | [The Perfect Matchday: A Beginner's Guide](https://www.thenonleaguefootballpaper.com/guest-posts/604687/the-perfect-matchday-a-beginners-guide-to-the-non-league-experience/) | The seven essentials of the non-league matchday |
| 2 | [Passion Beyond the Premier League](https://www.thenonleaguefootballpaper.com/guest-posts/478864/passion-beyond-the-premier-league-non-league-football-fan-engagement/) | Non-league fan engagement strategies |
| 3 | [Best Away Days in Non-League Football](https://footballgroundguide.com/news/best-away-days-in-non_league-football-our-top-5-ranked-from-national-league-to-step-4.html) | Top 5 ranked away days from National League to Step 4 |
| 4 | [Fan Culture in the National League North](https://shuttleone.network/fan-culture-and-community-engagement-in-the-national-league-north/) | Community identity and traditional-digital blend |
| 5 | [Why More Fans Are Turning to Non-League](https://www.wsc.co.uk/stories/editorial-why-more-fans-are-turning-to-non_league-affordable-community-culture/) | Editorial on the non-league attendance boom |
| 6 | [How Non-League Has Grown in Popularity](https://www.nonleagueinsider.com/leagues/how-non-league-has-grown-in_popularity/) | Coverage of non-league growth |
| 7 | [The Beginner's Guide to Groundhopping in the UK](https://thefans.io/blog/groundhopping-guide-uk-2/) | How to start groundhopping, first 5 grounds |
| 8 | [Non-league groundhopping: why the lower pyramid is the real experience](https://footbeen.com/blog/non_league-groundhopping-lower-league-football) | Cost comparison, food, atmosphere, and the real rewards |
| 9 | [National League Groundhopping Guide](https://footbeen.com/blog/national-league-groundhopping-guide) | Planning tips for National League day trips |
| 10 | [Football Fanbase Forum](https://www.footballfanbase.com/forum/) | Match day experience discussions |

## Football Apps

_Open source apps for match scores, picks, predictions, office pools, and more_

- [worldcup-2014 gem :octocat:](https://github.com/hpoydar/worldcup-2014), [:gem:](https://rubygems.org/gems/worldcup-2014) - provides command line access to World Cup 2014 information and results
- [world_cup_cli gem :octocat:](https://github.com/jameswilliamiii/world_cup_cli), [:gem:](https://rubygems.org/gems/world_cup_cli) - a command line interface that provides you the latest group table standings, scores, and see upcoming matches from the 2014 World Cup

- [fatiherikli/worldcup :octocat:](https://github.com/fatiherikli/worldcup) - World cup results for hackers; uses Soccer For Good API
- [Huang-Wei/2014 :octocat:](https://github.com/Huang-Wei/2014)
- [rtopitt/bolao2014 :octocat:](https://github.com/rtopitt/bolao2014) - Bolao PiTTlandia Copa do Mundo 2014
- [rtopitt/bolao :octocat:](https://github.com/rtopitt/bolao) - Bolao Copa 2010
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


## Meta

**License**

The awesome list is dedicated to the public domain. Use as you please with no restrictions whatsoever.

**Questions? Comments?**

Yes, you can. More than welcome.
See [Help & Support »](https://github.com/openfootball/help)