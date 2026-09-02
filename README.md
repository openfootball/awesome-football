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
[Kaggle](https://www.kaggle.com/datasets/davidcariboo/player-scores), 
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

> Fan community discussions, match day traditions, and cultural experiences from England's National League and wider non-league pyramid.

### The "3 A's" Framework

| Pillar | Non-League | Premier League |
|---|---|---|
| **Affordability** | £5–£15 tickets; ~£300 for 20 away | £30–£100+ tickets; £1,500–£3,000+ season |
| **Accessibility** | Walk-on gate, 20 min before kick-off | Book in advance; 45+ min queues |
| **Accountability** | Volunteer-run; chairman knows your name | Anonymous corporate ownership |

### 13 Core Match Day Traditions

1. 🍺 **The Pub Signal** — Pre-match pub gatherings, multi-generational singing rituals
2. 🏟️ **Intimate Grounds** — 500–5,000 capacity; you can hear the manager's instructions
3. 🧍 **Freedom of the Terrace** — Open standing; change ends at half-time
4. 🏠 **The Clubhouse/Social Club** — Volunteer-run, £2–3 pints, fans & officials mingle
5. 🥧 **Pie, Mash & Gravy** — £3–4 local bakery pies ("Footy Scran")
6. 📰 **The Physical Programme** — £2–3 paper collectibles that fund club finances
7. 🤝 **Volunteer Spirit** — Community-owned; fans steward, serve, and sit on committees
8. 🏴 **Local Rivalries** — Generational, geographic derbies; "friendly fire"
9. 🎵 **Chants & Songs** — Organic, locally-written, multi-generational
10. 👨‍👩‍👧‍👦 **Family Inclusion** — £7 family tickets; relaxed, welcoming atmosphere
11. 🏛️ **The Conference Legacy** — Community-first ethos from 1979–2004 era
12. 🚪 **Non-League Day** — Annual open-doors recruitment event (Feb 2026: 15th anniversary)
13. 🌙 **Post-Match Socialising** — 4–6 hour post-match rituals in clubhouse and pub

### Fan Sentiment Highlights

> *"Walking into a non-league ground for the first time, I felt like I'd walked into someone's living room. Everyone said hello."* — r/nonleaguefootball

> *"Nobody clocks you in. You just turn up. That's the point."* — r/nonleaguefootball

> *"The chairman knows your name. The player shakes your hand."* — Football Fanbase Forum

> *"In the Championship, you're a customer. In non-league, you're a member."* — The Non-League Football Paper

### Community Platforms

- **Reddit**: [r/nonleaguefootball](https://www.reddit.com/r/nonleaguefootball) (30k+), [r/nonleague](https://www.reddit.com/r/nonleague) (40k+), [r/NationalLeague](https://www.reddit.com/r/NationalLeague) (15k+), [r/CasualUK](https://www.reddit.com/r/CasualUK) (3M+)
- **Forums**: [NonLeagueMatters](https://www.nonleaguematters.co.uk/forums/), [Nonleaguezone.co.uk](https://www.nonleaguezone.co.uk/), [Football Fanbase Forum](https://www.footballfanbase.com/), [TheFans.io](https://thefans.io/), [Footbeen.com](https://www.footbeen.com/)
- **Publications**: [The Non-League Football Paper](https://www.thenonleaguefootballpaper.com/), [Football Ground Guide](https://footballgroundguide.com/), [When Saturday Comes](https://www.wsc.co.uk/)

### Notable Recognition

| Award | Year | Details |
|---|---|---|
| FSA Away Day Experience Awards | 2025 | Falmouth Town AFC recognised for outstanding visitor experience |
| Football Ground Guide "Best Away Days" | 2026 | Falmouth, Halifax, Torquay, Farnham Town, Lewes top the list |
| LiveScore NL Fan Survey | 2026 | 55% of PL fans open to attending NL matches |
| Non-League Day | 2026 | 15th anniversary of the annual open-doors event |

📖 Full research document: [NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)

## Football Apps

_Open source apps for match scores, picks, predictions, office pools, and more_