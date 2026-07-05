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
- [World Cup 2026 Tour schedule dataset](https://ay-worldcup2026.zeabur.app/dataset) - all 104 fixtures with UTC kickoff times, match pages, CSV/JSONL snapshots, a free local-time JSON API, OpenAPI spec, ICS calendar feed, and [Hugging Face](https://huggingface.datasets/abaiii168/world-cup-2026-tour-match-schedule) / [Kaggle](https://www.kaggle.com/datasets/ayworldcup2026/world-cup-2026-tour-match-schedule) mirrors.
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

SoccerData is a collection of wrappers over soccer data from `Club Elo`,
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

*The intangible heart of the beautiful game — community culture across the National League and wider non-league pyramid.*

Non-league football (Steps 1–7, 800+ clubs) offers some of the most passionate and authentic match day experiences in world football — intimate grounds, affordable tickets, and genuine community connection. This section documents match day culture, traditions, and fan communities alongside the repo's data focus.

### The 3 A's of Non-League Culture

- **Affordability**: £5–£15 tickets vs £30–£70+ PL; season tickets ~£160–£300 vs £1,000+
- **Accessibility**: Just walk in — no corporate barriers or membership walls
- **Accountability**: Fans can chat directly with chairmen and managers; match stewards are volunteers from the community

### 12 Key Match Day Traditions

1. **The Social Club** — Welcoming clubhouse hubs where fans mingle freely
2. **Pre-Match Pub Rituals** — Traditional congregation points anchoring local identity
3. **Pie, Mash & Gravy** — Legendary stadium food; the "Footy Scran" revolution brings gourmet options
4. **Physical Programmes** — £2–£3 collectible souvenirs that directly support club finances
5. **Freedom of the Terrace** — Stand anywhere, change ends at half-time; no assigned seats
6. **Volunteer Spirit** — Fans maintain pitches, steward matches, and build shared ownership
7. **Intimate & Historic Grounds** — From Sheffield FC's Sandgate (1860) to stacked terraces
8. **Ancient Local Derbies** — Sheffield FC vs Hallam FC (1860), the world's oldest derby
9. **Chants & Songs** — Raw, organic supporter singing
10. **Generational Traditions** — Families spanning decades in the same stand
11. **Non-League Day** — Annual initiative bridging the football pyramid
12. **Digital Integration** — Modern tech-savvy fans within historic grassroots atmosphere

### Where Fans Discuss Match Day Culture

| Community | URL |
|-----------|-----|
| r/nonleaguefootball | https://www.reddit.com/r/nonleaguefootball/ |
| r/NationalLeague | https://www.reddit.com/r/NationalLeague/ |
| NonLeagueMatters | https://www.nonleaguematters.co.uk/ |
| The Football Forum | https://www.thebigfather.co.uk/forums/23-football-discussion/ |
| The Non-League Football Paper | https://www.thenonleaguefootballpaper.com/ |
| When Saturday Comes | https://www.wsc.co.uk/ |
| FSA | https://www.thefsa.org.uk/ |

### Fan Voices

> "Football is no longer about being just another face in a crowd of 60,000 — it's about standing on a terrace and feeling part of something real." — *When Saturday Comes*, March 2025

> "The clubs that really matter to fans are the ones where you can chat to the chairman over a pint." — *Football Ground Map*, 2025

### Cost & Attendance Comparison

| Level | Avg Ticket | Season | Crowd |
|-------|-----------|--------|-------|
| NL Step 1 | £8–£15 | £180–£300 | 2k–5k |
| Steps 2–3 | £5–£12 | £150–£250 | 1.5k–4k |
| Steps 4–5 | £5–£10 | £100–£200 | 500–2k |
| PL | £30–£100+ | £1,200–£3,000+ | 30k–75k |

Twelve Step 3 clubs now average over 1,000 — rising PL prices and global focus have driven fans back to local community clubs (WSC, Feb 2025).

### Recommended Reading

1. [The Perfect Matchday — NLFP (Feb 2026)](https://www.thenonleaguefootballpaper.com/guest-posts/604687/the-perfect-matchday-a-beginners-guide-to-the-non-league-experience/)
2. [7 Golden Tips — NLFP (Aug 2023)](https://www.thenonleaguefootballpaper.com/guest-posts/443731/boosting-your-national-league-fan-experience-7-golden-tips/)
3. [Fan Culture — ShuttleOne Network](https://shuttleone.network/fan-culture-and-community-engagement-in-the-national-league-north/)
4. [Why More Fans Turn to Non-League — WSC (Feb 2025)](https://www.wsc.co.uk/stories/editorial-why-more-fans-are-turning-to-non-leagues-affordable-community-culture/)
5. [Best Away Days — FGN (Mar 2026)](https://www.footballgroundguide.com/news/best-away-days-in-non-league-football-our-top-5-ranked-from-national-league-to-step-4.html)
6. [The Magic of Non-League — PA Training (2026)](https://pa-training.shorthandstories.com/the-magic-of-non-league/index.html)

### Contributing

Per the repo's principle: **"Contributions welcome. Anything missing? Send in a pull request."** Text-based cultural additions are welcome alongside datasets and apps.

## Football Apps