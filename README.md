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


## Football Culture & Fan Experiences

_Open data on non-league match day culture, fan traditions, and community experiences from England's National League and the wider non-league pyramid._

- **[NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)** — Comprehensive research summary: 12 key traditions, 19+ community discussion sources, cost comparison table, fan sentiment highlights, recommended reading, and standalone research document

### 12 Key Match Day Traditions
| # | Tradition | Description |
|---|---|---|
| 1 | The Pub Signal | Pre-match gathering at local pub — the informal kickoff signal for the day |
| 2 | Intimate Grounds | Never more than 50m from the pitch; hear tackles, see facial expressions |
| 3 | Freedom of the Terrace | Stand anywhere, change ends at half-time, no assigned seats or barriers |
| 4 | The Clubhouse / Social Club | Community social hub where fans, officials, and players mingle freely |
| 5 | Pie & Mash ("Footy Scran") | Local bakeries and burger vans serve the best football food for £3–£6 |
| 6 | Physical Programme | £2–£4 programmes with local history, manager notes, and player interviews |
| 7 | Volunteer Spirit ("12th Man") | Volunteers maintain pitches, floodlights, and event setup at their local grounds |
| 8 | Walkabouts & Groundsman Chats | Pitch perimeter walks before kickoff and chats with the groundsman |
| 9 | Teashop Culture | Volunteer-run teashops that serve as social hubs pre- and post-match |
| 10 | Shared Taxi & Coach Networks | Organised away-day travel via Facebook/WhatsApp groups builds camaraderie |
| 11 | Code of Conduct | Unwritten rules about parking, respecting residents, and the "guest obligation" |
| 12 | Non-League Day & Local Rivalries | Annual events + deeply embedded neighbourhood pride and derby culture |

### Where Fans Discuss Match Day Culture
- **Reddit**: [r/nonleaguefootball](https://www.reddit.com/r/nonleaguefootball/) · [r/nonleague](https://www.reddit.com/r/nonleague/) · [r/NationalLeague](https://www.reddit.com/r/NationalLeague/) · [r/CasualUK](https://www.reddit.com/r/CasualUK/)
- **Forums**: [Nonleaguezone.co.uk](https://www.nonleaguezone.co.uk/) · [NonLeagueMatters.co.uk](https://www.nonleaguematters.co.uk/) · [The Football Forum](https://thefootballforum.com/)
- **Publications**: [The Non-League Football Paper](https://www.thenonleaguefootballpaper.com/) · [Football Ground Guide](https://www.footballgroundguide.com/) · [When Saturday Comes](https://wsc.co.uk/) · [Non League Insider](https://nonleagueinsider.co.uk/)
- **Projects**: [ShuttleOne Network / Energeo Project](https://shuttleone.co.uk/) · [FSA (Football Supporters' Association)](https://www.thefsa.org.uk/) · [Fan Experience Company](https://fanexperiencecompany.co.uk/)
- **Groundhopping Apps**: [TheFans.io](https://thefans.io/) · [Footbeen.com](https://footbeen.com/) · [Groundhopping.org](https://groundhopping.org/)
- **Social**: [Facebook: Enterprise National League](https://www.facebook.com/groups/1416019845294619/)

### Cost Comparison: Non-League vs Premier League
| Aspect | Non-League (£15–£30/day) | Premier League (£100–£300+/day) |
|---|---|---|
| Ticket | £10–£20 | £50–£300+ |
| Food & drink | £3–£6 | £8–£15+ |
| Programme | £2–£4 | £5–£8 |
| Away journey | £5–£15 | £20–£100+ |
| Membership required? | No | Often yes |
| Booking | Walk up / turnstile | Online ballot / Ticketmaster |

### Notable Recognition
- **FSA Away Day Experience Award 2025**: Falmouth Town, FC Halifax Town, Torquay United, Lewes FC
- **FSA Away Day Experience Award 2024**: Recognised clubs with exceptional supporter experiences
- **Non-League Day**: Annual event (next: 28 March 2026) encouraging top-flight fans to visit non-league grounds

### Recommended Reading
1. [The Perfect Matchday: A Beginner's Guide — The Non-League Football Paper](https://www.thenonleaguefootballpaper.com/guest-posts/604687/the-perfect-matchday-a-beginners-guide-to-the-non-league-experience/)
2. [Non-league groundhopping: why the lower pyramid is the real experience — Footbeen.com](https://footbeen.com/blog/non-league-groundhopping-lower-league-football)
3. [The Beginner's Guide to Groundhopping in the UK — TheFans.io](https://thefans.io/blog/groundhopping-guide-uk-beginners-2/)
4. [The Ultimate Non-League Groundhopping Guide — WDSportz](https://wdsportz.com/the-ultimate-non-league-groundhopping-guide-where-to-start/)
5. [Why more fans are turning to non-league — When Saturday Comes](https://wsc.co.uk/)
6. [Fan Banter: Why non-league is winning over fans](https://fanbanter.co.uk/fans-explain-why-more-and-more-are-now-turning-to-non-league-instead-of-watching-the-higher-levels/)

**[See full standalone research document → NON-LEAGUE-MATCHDAY-CULTURE.md](NON-LEAGUE-MATCHDAY-CULTURE.md)**


## Football Apps

_Open source apps for match scores, picks, predictions, office pools, and more_
