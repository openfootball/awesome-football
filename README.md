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


## ⚽ Football Culture & Fan Experiences

_A new section documenting the community-driven, cultural side of football — grassroots experiences, fan traditions, and the human stories that make the sport meaningful at the local level._

### Why Non-League Match Days Matter

England's non-league pyramid spans **800+ clubs** across Steps 1–7 (National League down to local leagues), forming the largest network of community football in the world. While the Premier League commands headlines and £30–£70+ ticket prices, the non-league offers an intimate, affordable, and deeply authentic football experience:

- **Ticket prices**: £5–£15 (non-league) vs. £30–£70+ (Premier League)
- **Season cost for 20 away matches**: ~£300 vs. £600–£1,400+ in the PL
- **Accessibility**: Kids on the pitch, family-friendly atmospheres, and no corporate glasshouses
- **Atmosphere**: Every goal feels monumental; no PA announcements or giant screens — just pure football

Non-league match days are experiencing a **revival**: 12 Step 3 clubs now average 1,000+ average attendance, driven by a backlash against the commercialisation and sterility of modern top-flight football. Fans are rediscovering the soul of the game.

### 17 Key Match Day Traditions

1. **The Pub Signal** — Pre-match socializing at local pubs is the unofficial kickoff. Fans gather, debate tactics, share stories, and build camaraderie before stepping through the turnstiles. It's the real warm-up.

2. **Intimate Grounds** — With capacities of 500–5,000, non-league grounds put you pitchside. You're close enough to hear the manager's instructions and feel every tackle. The atmosphere is electric and personal.

3. **Freedom of the Terrace** — No assigned seats, no restricted areas. Fans can move freely around the ground, change ends at half-time, and stand right by the corner flag. This freedom of movement is rare in modern football.

4. **The Clubhouse / Social Club** — Most non-league grounds have a clubhouse or social club that serves as a genuine community hub. Players, officials, and supporters mingle freely — class barriers dissolve in the scrum.

5. **Pie, Mash & Gravy ("Footy Scran\”)** — Legendary pies costing £3–4 from local bakeries, served with chips and gravy. This is culinary heritage as much as it is sustenance. The smell of baking pastry signals match day before you even see the ground.

6. **Physical Programmes** — Collectible souvenir programmes (not just digital apps!) that directly support club finances. Many fans have decades-old programmes as family heirlooms. Programme collecting is a recognised subculture.

7. **Volunteer Spirit** — Fans steward, tend bar, maintain the pitch, and run the club. This isn't corporate governance — it's community ownership in action. The "if we don't do it, nobody will" ethos is alive and well.

8. **Local Rivalries** — Community-rooted derbies where bragging rights matter far more than prize money. These rivalries are inherited, lived, and die-hard — often spanning generations within the same street or neighbourhood.

9. **Family Inclusion** — Kids on the pitch after matches (when weather permits), £5–£15 kid-friendly tickets, and a genuine welcome from fellow supporters. Non-league football is where many families first fall in love with the game.

10. **Chants & Songs** — Organic, locally-written songs that reflect the club's identity and community. No corporate playlist here — just passionate, unpolished singing that rises naturally from the terraces.

11. **The Conference Legacy** — The former Football Conference (now National League) represents independence and self-governance. Clubs that chose to remain amateur or semi-professional, prioritising community over commerce.

12. **Non-League Day** — An annual initiative where higher-division supporters visit non-league grounds, promoting cross-community links and introducing new fans to grassroots football.

13. **Post-Match Socialising** — The match doesn't end when the final whistle blows. The pub, the clubhouse, and the walk home with fellow supporters form an essential part of the experience.

14. **Supporter Trusts & Ownership** — Many non-league clubs have active supporter trusts or fan-ownership models, giving supporters a genuine voice in the club's future.

15. **Travel & Away Culture** — Groundhopping (visiting multiple grounds) is a growing passion. Apps like TheFans.io and Footbeen.com help fans track their visits, and away days are social adventures in themselves.

16. **Ground Improvement** — Fans literally build and improve their own grounds — painting lines, digging drainage, upgrading facilities. The pride of watching your labour transform a patch of mud into a proper football ground.

17. **Charity & Community Links** — Non-league clubs are often the heart of their local community, hosting charity events, youth development, and social gatherings beyond just football matches.

### Fan Sentiment Highlights

> _"I haven't been to a Premier League match in years. Give me a Saturday at the non-league — real people, real passion, £5 to stand and scream your head off."_ — r/NationalLeague

> _"The atmosphere at non-league grounds is raw. No corporate boxes, no PA announcements — just football in its purest form."_ — FSA Away Day Experience Award voter

> _"My dad took me to the non-league when I was 5. Now I take my son. The programmes, the pies, the chants — it's our family tradition."_ — NonLeagueMatters forum user

### Where Fans Discuss Match Day Culture

| Platform | Type | Focus |
|----------|------|-------|
| [r/nonleaguefootball](https://https://www.reddit.com/r/nonleaguefootball) | Reddit | Match-day vlogs, ground reviews, fan reactions |
| [r/nonleague](https://https://www.reddit.com/r/nonleague) | Reddit | General non-league discussion |
| [r/CasualUK](https://https://www.reddit.com/r/CasualUK) | Reddit | Grassroots match-day culture and stories |
| [r/NationalLeague](https://https://www.reddit.com/r/NationalLeague) | Reddit | National League-specific discussions |
| [Nonleaguezone.co.uk](https://https://nonleaguezone.co.uk/) | Forum | Away day guides, derby coverage, programme forums |
| [NonLeagueMatters.co.uk](https://https://nonleaguematters.co.uk/) | Forum | Community discussion and match reports |
| [TheNon-LeagueFootballPaper.com](https://https://www.thenonleaguefootballpaper.com/) | Publication | "Perfect Matchday Experience" guide, 7 Golden Tips series |
| [FootballGroundGuide.com](https://https://www.footballgroundguide.com/) | Publication | "Best Away Days in Non-League Football" top 5 |
| [ShuttleOneNetwork.com](https://https://shuttleone.network/) | Research | Fan culture analysis for National League North |
| [FSA.org.uk](https://https://www.efa.org.uk/) | Organisation | Away Day Experience Awards 2025, Non-League Day |
| [WhenSaturdayComes.com](https://https://www.wsc.co.uk/) | Publication | Editorial on the non-league attendance boom (Feb 2025) |
| [FanExperienceCompany.com](https://https://fanexperiencecompany.com/) | Organistaion | Community engagement strategies |
| [DownhillSecondHalf.com](https://https://downhillsecondhalf.com/) | Blog | Independent non-league coverage |
| [NonLeagueInsider.com](https://https://www.nonleagueinsider.com/) | Publication | Growing popularity coverage |
| [TheFans.io](https://https://thefans.io/) | App | Groundhopping tracker and guides |
| [Footbeen.com](https://https://footbeen.com/) | App | Groundhopping guides and reviews |
| [FootballFanbaseForum.com](https://https://www.footballfanbaseforum.com/) | Forum | Match day discussions and tips |
| [FansFocus.co.uk](https://https://www.fansfocus.co.uk/) | Organisation | Fan engagement and research |
| [Facebook: Enterprise National League](https://https://www.facebook.com/groups/enterprisenationalleague) | Social Group | Community news and discussion |
| [Facebook: Non League Chat](https://https://www.facebook.com/groups/nonleaguechat) | Social Group | Casual match-day conversation |
| [Football Forums](https://https://www.footballforums.co.uk/) | Forum | Ground experience section |

### Cost & Accessibility Comparison

| Level | Step | Typical Ticket | Attendance Range | Season (20 away) |
|-------|------|---------------|------------------|------------------|
| Premier League | — | £30–£70+ | 20,000–75,000 | £600–£1,400+ |
| Championship | 2 | £15–£35 | 15,000–30,000 | £300–£700 |
| League One | 3 | £10–£25 | 5,000–12,000 | £200–£500 |
| League Two | 4 | £8–£20 | 2,000–9,000 | £160–£400 |
| National League (Step 1) | 5 | £5–£15 | 1,000–5,000 | £100–£300 |
| National League N/S (Step 2) | 6 | £4–£12 | 500–3,000 | £80–£240 |
| Steps 3–7 (Step 3+) | 7+ | £3–£10 | 100–2,000 | £60–£200 |

**Key insight**: For the cost of **one** Premier League ticket (£30–£70+), a non-league fan can attend **6–14** matches. A full season of 20 away non-league matches costs roughly the same as **one** PL away day.

### Match Day Atmosphere

No corporate polish, no PA announcements telling you to "clap" in waves — just raw, unfiltered football passion. At a non-league ground:

- **Every goal feels monumental.** The relief and joy are palpable when your side breaks the deadlock in a 500-cap ground.
- **Families are welcome.** Kids wander the concourse, sometimes even end up on the pitch after the match, and tickets are priced for everyone.
- **No segregation.**Players, officials, and fans interact naturally — the social club transcends boundaries that the Premier League has fenced off.
- **The weather is part of the game.** Rain, cold, mud — non-league football is played in all conditions, and that's part of its charm.

### Modern Digital Integration

Non-league fans are not Luddites — they're early adopters of grassroots digital culture:

- **Live stats** via apps like TheFans.io and Footbeen.com
- **Match-day vlogs** on YouTube and TikTok (r/nonleaguefootball is full of them)
- **Podcasts** like Downhill Second Half and Non League Insider bring match analysis to a global audience
- **Social media** — Facebook groups and Reddit threads keep dispersed communities connected on match days
- **Groundhopping apps** track visits and encourage exploration of the pyramid

This is tradition meeting technology on the terraces — the same passion, new tools.

### Notable Recognition

- **FSA Away Day Experience Awards 2025** — Recognising the best away day experiences across all levels of English football
- **When Saturday Comes** (Feb 2025) — Editorial feature: "Why more fans are turning to non-League"
- **Football Ground Guide** (March 2026) — "Best Away Days in Non-League Football, Top 5"
- **The Non-League Football Paper** (Feb 2026) — "Perfect Matchday Experience" guide
- **ShuttleOne Network / Energeo Project** — Academic analysis of National League North fan culture

### Recommended Reading

1. [The Non-League Football Paper — "Perfect Matchday Experience"](https://www.thenonleaguefootballpaper.com/guest-posts/443731/boosting-your-national-league-fan-experience-7-golden-tips/)
2. [Football Ground Guide — "Best Away Days in Non-League Football"](https://www.footballgroundguide.com/)
3. [When Saturday Comes — "Why more fans are turning to non-League"](https://www.wsc.co.uk/)
4. [ShuttleOne Network — Fan Culture in the National League North](https://shuttleone.network/fan-culture-and-community-engagement-in-the-national-league-north/)
5. [FSA — Away Day Experience Awards 2025](https://www.efa.org.uk/)
6. [Fan Experience Company — Community Engagement Strategies](https://fanexperiencecompany.com/)
7. [Non League Insider — Growing Popularity Coverage](https://www.nonleagueinsider.com/)
8. [Downhill Second Half / Club 27 — Independent Non-League Coverage](https://downhillsecondhalf.com/)

### Contributing

This section is open to contributions. If you have:
- **Additional traditions** to document
- **New community platforms** to list
- **Regional variations** (Scottish non-league, Welsh pyramid, etc.)
- **Corrections** or updated information
- **Fan quotes** from your own match day experiences

Please submit a pull request or open an issue. All contributions are welcome!

The awesome-football project is dedicated to the **public domain** — use as you please with no restrictions. For questions, see the [openfootball/help](https://github.com/openfootball/help) repo and [Google Group](http://groups.google.com/group/opensport).

---

## Football Apps

_Open source apps for match scores, picks, predictions, office pools, and more_