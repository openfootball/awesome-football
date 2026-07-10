Awesome Series @ Planet Open Data

[World (Countries, Cities, Codes, ...)](https://github.com/planetopendata/awesome-world) • \
[Football (Clubs, Players, Stadiums, ...)](https://github.com/planetopendata/awesome-football) • \
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


## ⚽ Football Culture & Fan Experiences

A curated collection of community voices, match day traditions, and fan-driven resources from England's National League and wider non-league pyramid — the grassroots heart of the beautiful game.

### Why Non-League Match Days Matter

Non-league football is where the sport is lived most intimately. Over 800 clubs span steps 1–7 of the National League System, from the 50,000-capacity National League down to county leagues. Match days here are defined by accessibility, community, and traditions that are vanishingly rare in the professional game.

**Cost & Accessibility:**
| Tier | Typical Ticket Price | Away Day Cost (20 Matches) |
|------|---------------------|---------------------------|
| National League (Step 1) | £8–£15 | £160–£300 |
| National League North/South (Step 2) | £5–£12 | £100–£240 |
| Step 3–4 | £3–£10 | £60–£200 |
| Premier League | £30–£70+ | £600–£1,400+ |

### 12 Key Match Day Traditions

1. **The Pub Signal** — Pre-match socializing at the local pub. The "pub signal" is the unofficial start of match day: fans gather, analyse formations, and walk to the ground together.
2. **Intimate Grounds** — Capacity 500–5,000. You're close enough to hear the crunch of a tackle and the keeper's shouts. No view is bad.
3. **Freedom of the Terrace** — No assigned seats, no restricted areas. Fans "change ends" at half-time to stay behind the attacking goal. Standing, singing, and proximity define the experience.
4. **The Clubhouse / Social Club** — The beating heart of non-league. A welcoming hub where fans, officials, and players mingle. Handshakes at the gate, a pint of bitter, and tactics discussed over the bar. Much of the social life of a village revolves around this building.
5. **Pie, Mash & Gravy ("Footy Scran")** — The culinary centrepiece. Many clubs partner with local bakeries for legendary steak and ale pies (£3–4). The "Footy Scran revolution" has elevated stadium food to gourmet quality while staying rooted in local heritage.
6. **The Physical Programme** — A collectible souvenir in an increasingly digital world. For a couple of pounds you get local history, manager notes, and player interviews. Every penny supports the club's finances.
7. **Volunteer Spirit** — Fans steward the bar, maintain the pitch, lay the corner flags, and drive the minibus. This shared-ownership ethic is what makes non-league clubs feel like they belong to the community rather than a boardroom.
8. **Local Rivalries** — Community-rooted derbies with decades of history. Not manufactured by broadcasters but born from geography: township vs. township, neighbouring valleys, adjacent streets.
9. **Family Inclusion** — Kids on the pitch at half-time, £5–£15 ticket prices, no VIP barriers. Non-league is often the first introduction to football for entire families.
10. **Chants & Songs** — Organic, locally-written songs that evolve match by match. You won't find these on Spotify — they live in the terraces and drift out onto the pitch.
11. **The Conference Legacy** — The old Football Conference (now National League) instilled a culture of independence and self-governance. Clubs take pride in running themselves, often through supporter trusts and elected boards.
12. **Non-League Day** — An annual initiative where higher-division supporters are encouraged to visit a non-league ground. Recognised by the FA and FSA, it has helped draw new fans into the grassroots game.

### Fan Sentiment Highlights

> *"Walk into any non-league ground on a Saturday afternoon and you'll see it: handshakes at the gate, familiar nods at the bar, and someone talking tactics over a pint of bitter."* — The Non-League Football Paper (Jul 2025)

> *"You're not watching football on a screen. You're living it."* — The Non-League Football Paper

> *"They've seen their team thrashed five-nil on a wet Tuesday in February, and still been there the next Saturday."* — The Non-League Football Paper

> *"Sometimes you don't need ten cameras, a worldwide broadcast, and players made of money in order to enjoy the game. Sometimes you just need a muddy pitch, a dodgy pie, and a family of a team."* — The Non-League Football Paper

> *"Why I started this: I got priced out of top-flight football and ended up falling back in love with the game at non-league grounds. The community, the characters, the unpredictability—it's just a better day out."* — NonLeagueMatters Forums

### Where Fans Discuss Match Day Culture

- **r/nonleaguefootball** (Reddit) — Dedicated subreddit for non-league discussion and groundhopping
- **r/nonleague** (Reddit) — General non-league football community
- **r/NationalLeague** (Reddit) — Specific to England's 5th tier
- **r/CasualUK** (Reddit) — Broad discussion including non-league culture
- **NonLeagueMatters** (nonleaguematters.co.uk) — Forum for non-league debate, match reports, and match day experiences
- **Nonleaguezone.co.uk** — Away day guides, derby coverage, and programme collecting forums
- **The Non-League Football Paper** (thenonleaguefootballpaper.com) — Independent publication featuring match day guides and fan culture features
- **Football Ground Guide** (footballgroundguide.com) — Ground guides and "Best Away Days in Non-League"
- **TheFans.io** — Groundhopping app and community
- **Footbeen.com** — Football groundhopping blog and guide
- **FSA (Football Supporters Association)** — FSA Away Day Experience Awards, Non-League Day campaigns
- **When Saturday Comes** — Long-running football magazine with regular non-league coverage
- **Downhill Second Half** — Independent non-league blog
- **Club 27 Blog** — Non-league football commentary
- **ShuttleOne Network / Energeo Project** — Fan culture analysis for National League North

### Notable Recognition

- **FSA Away Day Experience Awards 2025** — Recognised clubs including Falmouth Town, FC Halifax Town, Torquay United, and Lewes FC for outstanding match day experiences
- **When Saturday Comes** (Feb 2025) — Editorial on the non-league attendance boom, with 12 Step 3 clubs already averaging 1,000+ spectators
- **The Non-League Football Paper** (Feb 2026) — "The Perfect Matchday: A Beginner's Guide to the Non-League Experience"

### Recommended Reading

- [The Perfect Matchday: A Beginner's Guide to the Non-League Experience](https://www.thenonleaguefootballpaper.com/guest-posts/604687/the-perfect-matchday-a-beginners-guide-to-the-non-league-experience/) — The Non-League Football Paper (Feb 2026)
- [From the Clubhouse to the Pitch: What Makes Non-League Fans So Loyal?](https://www.thenonleaguefootballpaper.com/guest-posts/582587/from-the-clubhouse-to-the-pitch-what-makes-non-league-fans-so-loyal/) — The Non-League Football Paper (Jul 2025)
- [Ever Tried a Mystery Non-League Matchday?](https://www.nonleaguematters.co.uk/forums/threads/ever-tried-a-mystery-non-league-matchday-here%E2%80%99s-our-story.18003/) — NonLeagueMatters Forums
- [Non-League Football Clubs: Boost Fan Experience & Matchday Revenue](https://matchcentre.co.uk/blog/optimising-the-fan-experience-a-practical-guide-for-non-league-clubs) — Match Centre UK
- [Ever Tried a Mystery Non-League Matchday? Here's Our Story!](https://www.nonleaguematters.co.uk/forums/threads/non-league-day-novelty-worn-off.15648/) — NonLeagueMatters Forums
- [Football Ground Guide: Best Away Days in Non-League Football](https://footballgroundguide.com) — Away day guides
- [When Saturday Comes — Non-League Attendance Boom](https://wsc.co.uk) — Editorial coverage
- [FSA Away Day Experience Awards 2025](https://thefsa.co.uk) — Awards and recognition

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

- [soccer_league :octocat:](https://github.com/mrjabba/soccer_league) - a rails application designed to manage soccer leagues, specifically teams and their stats
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
