Awesome Series @ Planet Open Data

[World (Countries, Cities, Codes, ...)](https://github.com/planetopendata/awesome-world) &bull; [Football (Clubs, Players, Stadiums, ...)](https://github.com/planetopendata/awesome-football) &bull; [SQLite (Tools, Books, Schemas, ...)](https://github.com/planetopendata/awesome-sqlite)

# Awesome Football   (Open Datasets & Open Source Apps)

A collection of awesome football (national teams, clubs, match schedules, players, stadiums, etc.) datasets

**Contributions welcome. Anything missing? Send in a pull request. Thanks.**

## V3 - What's News in 2026?

### World Cup 2026
- [Onside World Cup 2026 model outputs](https://onsidearena.com/data) - model predictions (open data); per-match win/draw probabilities, champion odds (10,000-run Monte Carlo simulation) and the full 104-match schedule as CC BY 4.0 CSVs, refreshed through the tournament; includes a [public graded accuracy record](https://onsidearena.com/world-cup-2026/model-record) and a [Kaggle mirror](https://www.kaggle.com/datasets/wr0027/world-cup-2026-predictions-onside-model-outputs)
- [uanalyse World Cup 2026 predictions](https://github.com/uanalyse/world-cup-2026-predictions) - daily, timestamped forecasts published before kickoff; per-match win/draw/loss probabilities and expected goals, plus tournament probabilities (reach each stage, champion) of a 10,000-run Monte Carlo group stage with the knockout bracket solved exactly by dynamic programming (computed, not sampled). Append-only, signed CC BY 4.0 CSVs, refreshed daily through the tournament, with a live [interactive portal](https://uanalyse.co.uk/world-cup-2026). Widely used: 300+ repo clones in two weeks, plus independent bracket and Kicktipp projects building on it.
- [World Cup AI Forecast](https://worldcupaiforecast.com/) - multilingual World Cup 2026 forecast and analysis dashboard with match win probabilities, score predictions, group standings, lineup notes, completed-match backtesting, transparent [methodology](https://worldcupaiforecast.com/methodology-en.html) and [data-source notes](https://worldcupaiforecast.com/data-sources-en.html). Entertainment-only informational analytics.
- [FootyTips World Cup backtest](https://github.com/tuofangzhe/footytips-worldcup-backtest) - reproducible backtest of an open Elo + Poisson (Dixon-Coles) model across all 22 World Cups (1930-2022, 964 matches): 56.6% win/draw/loss hit rate, replayed walk-forward from the CC0 [martj42 dataset](https://github.com/martj42/international_results) with no future data. ~250 lines, zero dependencies, `npm run backtest` reproduces the numbers; live 2026 picks settled publicly after each match, including the misses.
- [World Cup 2026 Tour schedule dataset](https://ay-worldcup2026.zeabur.app/dataset) - all 104 fixtures with UTC kickoff times, match pages, CSV/JSONL snapshots, a free local-time JSON API, OpenAPI spec, ICS calendar feed, and [Hugging Face](https://huggingface.com/datasets/abaiii168/world-cup-2026-tour-match-schedule) / [Kaggle](https://www.kaggle.com/datasets/ayworldcup2026/world-cup-2026-tour-match-schedule) mirrors.
- [World Cup 2026 Player Data](https://github.com/risingtransfers/world-cup-2026-data) - all 48 squads (1363 players) with per-90 stats and AI player similarity examples. CC BY 4.0.
- [WC2026 Live Tracker](https://github.com/Krymets/wc2026) - Live scores, goals & cards by minute, group standings, knockout bracket and player stats for all 104 matches. Single HTML file, no dependencies, auto-updates via ESPN API.
- [lefProg/claudial](https://github.com/lefProg/claudial) - a small fun project that lets you see live updates for the 2026 World Cup right in your Claude Code status line.
- [TopScorers World Cup 2026](https://www.top-scorers.com/en/mundial-2026) - live top scorers, assists and the Golden Boot race for the 2026 World Cup, plus group standings, results and the full 104-match schedule. Bilingual (EN/ES), free, no signup.

## V2 - What's News in 2022?

[**jfjelstul/worldcup**](https://github.com/jfjelstul/worldcup)

The Fjelstul World Cup Database is a comprehensive database about the FIFA World Cup created by Joshua C. Fjelstul, Ph.D. that covers all `21` World Cup tournaments (1930-2018). An update with data on the 2022 World Cup in Qatar will be available soon. The database includes `27` datasets (approximately 1.1 million data points) that cover all aspects of the World Cup.

[**JaseZiv/worldfootballR**](https://github.com/JaseZiv/worldfootballR)

This package is designed to allow users to extract various world football results and player statistics from the following popular football (soccer) data sites:
- FBref
- [Transfermarkt](https://www.transfermarkt.com/)
- [Understat](https://understat.com/)
- [Fotmob](https://www.fotmob.com/)

Since the release of `v0.5.3`, the library now supports very rapid loading of pre-collected data through the use of `load_` functions. The data available for loading is stored in the `worldfootballR_data` repository. The repo can be found [here](https://github.com/JaseZiv/worldfootballR_data).

[**dcaribou/transfermarkt-datasets**](https://github.com/dcaribou/transfermarkt-datasets)
this project aims for three things:
1. Acquire data from transfermarkt website using the [trasfermarkt-scraper](https://github.com/dcaribou/transfermarkt-scraper).
2. Build a **clean, public football (soccer) dataset** using data in 1.
3. Automatize 1 and 2 to **keep these assets up to date** and publicly available on some well-known data catalogs.
Checkout this dataset also in:
[Kaggle](https://www.kaggle.com/davidcariboo/player-scores), [data.world](https://data.world/dcereijo/player-scores), [streamlit](https://transfermarkt-datasets.herokuapp.com/), [awesome-public-datasets](https://github.com/awesomedata/apd-core/blob/master/core/Sports/Transfermarkt-Datasets.yml)

[**somdeep/Statball**](https://github.com/somdeep/Statball)
Football (soccer) stats analyser from top 5 european leagues with data obtained from Fbref and Statsbomb.
Fbref : https://fbref.com/en/comps/Big5/Big-5-European-Leagues-Stats
Statsbomb : https://statsbomb.com/

[**probberechts/soccerdata**](https://github.com/probberechts/soccerdata)
SoccerData is a collection of wrappers over soccer data from `Club Elo_`, `ESPN_`, `FBref_`, `FiveThirtyEight_`, `Football-Data.co.uk_`, `SoFIFA_` and `WhoScored_`. You get Pandas DataFrames with sensible, matching column names and identifiers across datasets. Data is downloaded when needed and cached locally. To learn how to install, configure and use SoccerData, see the `Quickstart guide <https://soccerdata.readthedocs.io/en/latest/usage.html>`__. For documentation on each of the supported data sources, see the `example notebooks <https://soccerdata.readthedocs.io/en/latest/datasources/>`__ and `API reference <https://soccerdata.readthedocs.io/en/latest/reference/>`__.

## V1 - Before 2022

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

Non-league football (the National League and the wider pyramid below it) has a rich, distinctive matchday culture shaped by community ownership, affordability, and intimate supporter access. This section documents the **community-driven, cultural side of football** — grassroots experiences, fan traditions, and the human stories that make the sport meaningful.

### Why Non-League Match Days Matter

Non-league football spans the National League (5th tier) down through the National League System and to local county leagues. With over 800 clubs and grounds typically seating 500–5,000 spectators, the non-league match day offers: **authentic community connection, affordable access, and volunteer-driven traditions**.

| | Non-League | Premier League |
|---------|-----------|---------------|
| Match ticket | £5–£15 | £30–£70+ |
| Food & drink | £3–£7 | £8–£20+ |
| Season (20 away) | ~£300 | £600–£1,400+ |

**Key traditions include:**
- The Pub Signal — Pre-match gatherings at local pubs where fans debate team news
- Intimate Grounds — Small terraces putting supporters pitchside
- Freedom of the Terrace — No assigned seats; move freely to follow your team
- The Clubhouse — Pre-match social clubs where fans and officials mingle
- Pie, Mash & Gravy — The iconic "Footy Scran" culinary tradition
- Physical Programme — Collectible souvenirs supporting club finances
- Volunteer Spirit — Community-owned clubs sustained by fan volunteers
- Local Rivalries — Community-rooted derbies spanning generations
- Family Inclusion — Children on the pitch, affordable tickets for all
- Chants & Songs — Organic, locally-written songs
- The Conference Legacy — 1979–2004 era of independence and self-governance
- Non-League Day — Annual awareness event during international breaks

See the full research document **[NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)** for detailed analysis, sources, and recommendations.

### The 13 Pillars of Non-League Match Day Culture

1. **The Pub Signal** — Pre-match gatherings at local pubs near the ground
2. **Intimate Grounds** — Small stadiums where nowhere is far from the pitch
3. **Freedom of the Terrace** — Open standing, free movement, change ends at half-time
4. **The Clubhouse / Social Club** — Volunteer-run, affordable, family atmosphere
5. **Footy Scran (Pie, Mash & Gravy)** — Legendary local food and "bakehouse food revolution"
6. **Physical Programme** — Paper programmes as souvenirs, supporting club finances
7. **Volunteer Spirit** — The entire match day operation runs on community volunteers
8. **Walkabouts & Groundsman Chats** — Pitch perimeter walks and chatting with the groundsman
9. **Teashop Culture** — Volunteer-run teashops as social hubs pre- and post-match
10. **Shared Taxi & Coach Networks** — Organised away-day travel via Facebook/WhatsApp groups
11. **The Code of Conduct** — Unwritten rules about parking, residents, and "guest obligation"
12. **Local Rivalries** — Decades-old, deeply-rooted geographic derbies
13. **Non-League Day** — Annual event opening doors to new supporters (#NLD)

### Community Discussion Platforms

- **Reddit:** [r/NationalLeague](https://www.reddit.com/r/NationalLeague/) · [r/nonleague](https://www.reddit.com/r/nonleague/) · [r/nonleaguefootball](https://www.reddit.com/r/nonleaguefootball/) · [r/CasualUK](https://www.reddit.com/r/CasualUK/)
- **Forums:** [Nonleaguezone.co.uk](https://www.nonleaguezone.co.uk/) · [TheFans.io](https://thefans.io/) · [Footbeen.com](https://footbeen.com/) · [The Football Forum](https://thefootballforum.com/)
- **Publications:** [The Non-League Football Paper](https://www.thenonleaguefootballpaper.com/) · [Football Ground Guide](https://www.footballgroundguide.com/) · [When Saturday Comes](https://wsc.co.uk/) · [Non League Insider](https://nonleagueinsider.co.uk/)
- **Projects & Orgs:** [ShuttleOne Network](https://shuttleone.co.uk/) · [FSA](https://www.thefsa.org.uk/) · [Fan Experience Company](https://fanexperiencecompany.co.uk/)
- **Groundhopping Apps:** [TheFans.io](https://thefans.io/) · [Footbeen.com](https://footbeen.com/) · [Groundhopping.org](https://groundhopping.org/)
- **Social Groups:** [Facebook: Enterprise National League](https://www.facebook.com/groups/1416019845294619/)

### Notable Recognition

- **FSA Away Day Experience Award 2025:** Falmouth Town AFC (Bickland Park), FC Halifax Town (The Shay), Torquay United (Plainmoor), Lewes FC (The Dripping Pan)
- **FSA Away Day Experience Award 2024:** Recognised clubs for exceptional community matchday hosting
- **"Perfect Matchday" guide** (The Non-League Football Paper, Feb 2026)
- **"Why more fans are turning to non-League"** (When Saturday Comes editorial, Feb 2025)
- **Best Away Days in Non-League Football** (Football Ground Guide, March 2026)

### Fan Sentiment Highlights

> "The Premier League is a product. Non-league football is football." — Footbeen.com
> "Once you've experienced it, the Premier League starts to feel like watching a concert through a phone screen." — Footbeen.com
> "No two grounds feel the same, because no two grounds were built to the same corporate specification." — Football Ground Guide

---

## Football Apps

_Open source apps for match scores, picks, predictions, office pools, and more_