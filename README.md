## CRAN Task View: Sports Analytics

                                                                                                                         
--------------- ------------------------------------------------------------------------------------------------------   
**Maintainer:** Ben Baumer                                                                                               
**Contact:**    ben.baumer at gmail.com                                                                                  
**Version:**    2021-09-17                                                                                               
**URL:**        [https://CRAN.R-project.org/view=Sports Analytics](https://CRAN.R-project.org/view=Sports%20Analytics)   

<div>

This CRAN Task View contains a list of packages useful for sports
analytics, grouped by sport.

Contributions are always welcome, and encouraged. The source file for
this particular task view file resides in a GitHub repository (see
below) so that pull requests are possible.

**Baseball**

  - Historial baseball data is available through the
    [Lahman](https://cran.r-project.org/package=Lahman) package, which contains
    season-level data for Major League Baseball going back to 1871.
  - [retrosheet](https://cran.r-project.org/package=retrosheet) facilitates
    downloading game log, team IDs, rosters, and play-by-play and other
    files from [Retrosheet.org](http://wwws.retrosheet.org/) , and
    returning the results as data frames. Local caching can be employed
    to improve efficiency. Note that the play-by-play data returned
    comes directly from the event files and is not parsed (i.e.,
    [Chadwick](https://github.com/chadwickbureau/chadwick) is not
    bundled).
  - [pitchRx](https://cran.r-project.org/package=pitchRx) provides access to
    pitch-level data through the Major League Baseball Advanced Media
    API.
  - [mlbstats](https://cran.r-project.org/package=mlbstats) provides functions for
    vector-based computation of many baseball statistics, both
    traditional and sabermetric. This should not be confused with
    [mlbstatsR](https://cran.r-project.org/package=mlbstatsR) which provides an
    interface to websites such as MLB.com, ESPN.com, and
    Baseball-Reference.com.
    [mlbstatsR](https://cran.r-project.org/package=mlbstatsR) can download IDs and
    stats for players and team, as well as MLB logos.
  - [baseballDBR](https://cran.r-project.org/package=baseballDBR) leverages the
    backend database functionality of
    [dplyr](https://cran.r-project.org/package=dplyr) to build local databases that
    mirror the data contained in
    [Lahman](https://cran.r-project.org/package=Lahman). Like
    [mlbstats](https://cran.r-project.org/package=mlbstats), it also includes
    functions to compute baseball statistics, but on data frames rather
    than vectors.

**Basketball**

  - [BAwiR](https://cran.r-project.org/package=BAwiR) is a collection of tools to
    analyze basketball data, with focus on data scraping and
    visualization.
  - [AdvancedBasketballStats](https://cran.r-project.org/package=AdvancedBasketballStats)
    provides functions to calculate and analyze basketball statistics
    for players, teams, lineups (quintets), and plays.
  - [uncmbb](https://cran.r-project.org/package=uncmbb) contains data on University
    of North Carolina (at Chapel Hill) Men's Basketball Results since
    the 1949-50 season.
  - [BasketballAnalyzeR](https://cran.r-project.org/package=BasketballAnalyzeR)
    accompanies the book [Basketball Data Science With Applications in
    R](https://www.routledge.com/Basketball-Data-Science-With-Applications-in-R/Zuccolotto-Manisera/p/book/9781138600799)
    . This package includes data and functions to analyze and visualize
    basketball data.
  - [NBAloveR](https://cran.r-project.org/package=NBAloveR) is an R interface to
    access basketball data from [Basketbal
    Reference](https://www.basketball-reference.com) API. This package
    also contains functions to help users with analyzing basketball
    data.
  - [SpatialBall](https://cran.r-project.org/package=SpatialBall) helps with spatial
    analysis of NBA data, in particular, generating offensive and
    defensive shot charts for teams, players, and seasons.

**Football**

  - [nflfastR](https://cran.r-project.org/package=nflfastR) contains functions to
    efficiently scrape NFL play-by-play data from 1999 to present.
    Similar to [nflscrapR](https://cran.r-project.org/package=nflscrapR), but much
    faster.
  - [fflr](https://cran.r-project.org/package=fflr) contains functions for accessing
    ESPN raw fantasy football data from the ESPN fantasy football API
    and formatting the raw data.
  - [ffsimulator](https://cran.r-project.org/package=ffsimulator) allows users to
    simulate fantasy football seasons using bootstrap simulations.
    Simualtions are based on historical rankings and data from the
    package [nflfastR](https://cran.r-project.org/package=nflfastR). In addition,
    functions for computing optimal lineups and aggregating results are
    provided.
  - [ffscrapr](https://cran.r-project.org/package=ffscrapr) API Client for Fantasy
    Football League Platforms
  - [nfl4th](https://cran.r-project.org/package=nfl4th) Functions to Calculate
    Optimal Fourth Down Decisions in the National Football League. Data
    on 4th downs is collected from [NFL](https://www.nfl.com/) and
    [ESPN](https://www.espn.com/) .
  - [nflseedR](https://cran.r-project.org/package=nflseedR) The package contains
    functions for ranking NFL teams based on the complex NFL tie
    breaking rules. Includes division ranking, playoff seeding, and
    draft order.
  - [gsisdecoder](https://cran.r-project.org/package=gsisdecoder) High Efficient
    Functions to Decode NFL Player IDs. For use in nflfastR pacakge.

**Hockey**

  - [hockeyR](https://cran.r-project.org/package=hockeyR) The package contains
    functions to load raw NHL play-by-play data from
    [NHL.com](https://nhl.com) . Additionally, the package contains
    functions for scraping
    [www/hockey-reference.com](https://www.hockey-reference.com)
    including standings, player stats, and jersey number history.
  - [NHLData](https://cran.r-project.org/package=NHLData) The package contains
    scores from NHL games dating back to 1917. Data are stored one
    season at a time and contains scores for every game during a
    particular season.

**Soccer**

  - European soccer data is available through the
    [engsoccerdata](https://cran.r-project.org/package=engsoccerdata) package, which
    contains match results for English and other European soccer leagues
    dating back to 1871.
  - [socceR](https://cran.r-project.org/package=socceR) provides functions for
    evaluating soccer predictions and simulating results from soccer
    matches and tournament.
  - [fbRanks](https://cran.r-project.org/package=fbRanks) helps with estimating team
    strengths and rankings using time dependent Poisson regression and
    data on number of goals scored.
  - [ggsoccer](https://cran.r-project.org/package=ggsoccer) provides functions for
    visualizing soccer event data in
    [ggplot2](https://cran.r-project.org/package=ggplot2).
  - [qqr](https://cran.r-project.org/package=qqr) is a collection of Brazilian
    Soccer Championship data on match statistics since 2014.
  - [footballpenaltiesBL](https://cran.r-project.org/package=footballpenaltiesBL)
    contains data and plotting functions for analyzing penalty kicks in
    the German Men's Bundesliga from 1963-64 to 2016-17.

**Chess**

  - [chess](https://cran.r-project.org/package=chess) is an opinionated wrapper for
    R around [python-chess](https://github.com/niklasf/python-chess) .
    It reads and writes [PGN
    files](https://en.wikipedia.org/wiki/Portable_Game_Notation) and
    SVGs of game boards.
  - [stockfish](https://cran.r-project.org/package=stockfish) is an R package that
    implements the UCI open communication protocol and ships with
    [Stockfish](https://github.com/official-stockfish/Stockfish) , a
    popular, open source, powerful chess engine written in C++.
  - Like [chess](https://cran.r-project.org/package=chess),
    [bigchess](https://cran.r-project.org/package=bigchess) reads and writes PGN
    files. And like [stockfish](https://cran.r-project.org/package=stockfish),
    [bigchess](https://cran.r-project.org/package=bigchess) provides an API to the
    UCI chess engines. [bigchess](https://cran.r-project.org/package=bigchess) is
    also able to read multiple game files at once without copying to
    RAM.

**Swimming**

  - [SwimmeR](https://cran.r-project.org/package=SwimmeR) reads swimming results in
    a variety of formats and returns results in tidy data frame. It also
    includes functions for coverting times between short-course yards
    (SCY), short-course meters (SCM), and long-course meters (LCM).

**Australian Rules Football**

  - [fitzRoy](https://cran.r-project.org/package=fitzRoy) is a package for scraping
    and processing Australian Football League (AFL) data.
    [fitzRoy](https://cran.r-project.org/package=fitzRoy) provides access to
    publicly data sources such as [AFL
    Tables](https://afltables.com/afl/afl_index.html) , [Footy
    Wire](https://www.footywire.com) , and [The
    Squiggle](https://squiggle.com.au) .

**Cricket**

  - [yorkr](https://cran.r-project.org/package=yorkr) provides functions for
    analyzing statistics of cricket players and teams based on
    [Cricsheet](https://cricsheet.org) data.
  - [cricketr](https://cran.r-project.org/package=cricketr) is a collection of tools
    for analyzing cricket performances of players and teams based on
    [ESPN Cricinfo
    Statsguru](https://stats.espncricinfo.com/ci/engine/stats) data.

**Volleyball**

  - [volleystat](https://cran.r-project.org/package=volleystat) contains match
    statistics from the German Volleyball Bundesliga from 2013-14 to
    2018-19. Data were extracted from the league
    [homepage](www.volleyball-bundesliga.de) .

**GPS Tracking**

  - [trackeR](https://cran.r-project.org/package=trackeR) and
    [trackeRapp](https://cran.r-project.org/package=trackeRapp) provide tools for
    analyzing running, cycling and swimming data from GPS-enabled
    tracking devices within R. These two packages allow users to tidy
    and explore data from workouts and competitions.

**General**

  - [teamcolors](https://cran.r-project.org/package=teamcolors) provides color
    palettes, [ggplot2](https://cran.r-project.org/package=ggplot2) themes,
    [xaringan](https://cran.r-project.org/package=xaringan) themes, and logos for
    professional teams across a variety of sports and leagues.
  - [colorr](https://cran.r-project.org/package=colorr) contains color palettes for
    professional sports teams in the EPL, MLB, NBA, NHL, and NFL.
  - [nbacolorpalettes](https://cran.r-project.org/package=nbacolorpalettes) creates
    color palettes based on NBA team jerseys. This was inspired by the
    Wes Anderson package.
  - [aRbs](https://cran.r-project.org/package=aRbs) contains functions for finding
    arbitrage opportunities in sports betting websites. Data are
    collected through [www.oddschecker.com](https://www.oddschecker.com)
  - [mvglmmRank](https://cran.r-project.org/package=mvglmmRank) contains functions
    for building multivariate generlized mixed models for ranking teams
    in sports.
  - The goal of the
    [SportsAnalytics](https://cran.r-project.org/package=SportsAnalytics) package is
    to provide infrastructure to perform general sports analytics.
    However, currently it appears to be incomplete and currently only
    contains a few data sets and functions.
  - [TouRnament](https://cran.r-project.org/package=TouRnament) contains two
    functions: 1) Creating league tables based on results and 2)
    Creating a match schedule for a league.
  - [piratings](https://cran.r-project.org/package=piratings) computes pi ratings as
    described in [Constantinou and Fenton
    (2013)](https://www.degruyter.com/document/doi/10.1515/jqas-2012-0036/html)
    .
  - [sportyR](https://cran.r-project.org/package=sportyR) contains functions for
    creating [ggplot2](https://cran.r-project.org/package=ggplot2) represntations of
    sports playing surfaces pursuant to rule-book specifications. This
    is particularly useful for plotting player tracking data.

</div>

### CRAN packages:

  - [AdvancedBasketballStats](https://cran.r-project.org/package=AdvancedBasketballStats)
  - [aRbs](https://cran.r-project.org/package=aRbs)
  - [baseballDBR](https://cran.r-project.org/package=baseballDBR)
  - [BasketballAnalyzeR](https://cran.r-project.org/package=BasketballAnalyzeR)
  - [BAwiR](https://cran.r-project.org/package=BAwiR)
  - [bigchess](https://cran.r-project.org/package=bigchess)
  - [chess](https://cran.r-project.org/package=chess)
  - [colorr](https://cran.r-project.org/package=colorr)
  - [cricketr](https://cran.r-project.org/package=cricketr)
  - [engsoccerdata](https://cran.r-project.org/package=engsoccerdata)
  - [fbRanks](https://cran.r-project.org/package=fbRanks)
  - [fflr](https://cran.r-project.org/package=fflr)
  - [ffscrapr](https://cran.r-project.org/package=ffscrapr)
  - [ffsimulator](https://cran.r-project.org/package=ffsimulator)
  - [fitzRoy](https://cran.r-project.org/package=fitzRoy)
  - [footballpenaltiesBL](https://cran.r-project.org/package=footballpenaltiesBL)
  - [ggsoccer](https://cran.r-project.org/package=ggsoccer)
  - [gsisdecoder](https://cran.r-project.org/package=gsisdecoder)
  - [hockeyR](https://cran.r-project.org/package=hockeyR)
  - [Lahman](https://cran.r-project.org/package=Lahman)
  - [mlbstats](https://cran.r-project.org/package=mlbstats)
  - [mlbstatsR](https://cran.r-project.org/package=mlbstatsR)
  - [mvglmmRank](https://cran.r-project.org/package=mvglmmRank)
  - [nbacolorpalettes](https://cran.r-project.org/package=nbacolorpalettes)
  - [NBAloveR](https://cran.r-project.org/package=NBAloveR)
  - [nfl4th](https://cran.r-project.org/package=nfl4th)
  - [nflfastR](https://cran.r-project.org/package=nflfastR)
  - [nflseedR](https://cran.r-project.org/package=nflseedR)
  - [NHLData](https://cran.r-project.org/package=NHLData)
  - [piratings](https://cran.r-project.org/package=piratings)
  - [pitchRx](https://cran.r-project.org/package=pitchRx)
  - [qqr](https://cran.r-project.org/package=qqr)
  - [retrosheet](https://cran.r-project.org/package=retrosheet)
  - [socceR](https://cran.r-project.org/package=socceR)
  - [SpatialBall](https://cran.r-project.org/package=SpatialBall)
  - [SportsAnalytics](https://cran.r-project.org/package=SportsAnalytics)
  - [sportyR](https://cran.r-project.org/package=sportyR)
  - [stockfish](https://cran.r-project.org/package=stockfish)
  - [SwimmeR](https://cran.r-project.org/package=SwimmeR)
  - [teamcolors](https://cran.r-project.org/package=teamcolors)
  - [TouRnament](https://cran.r-project.org/package=TouRnament)
  - [trackeR](https://cran.r-project.org/package=trackeR)
  - [trackeRapp](https://cran.r-project.org/package=trackeRapp)
  - [uncmbb](https://cran.r-project.org/package=uncmbb)
  - [volleystat](https://cran.r-project.org/package=volleystat)
  - [yorkr](https://cran.r-project.org/package=yorkr)

### Related links:

  - CRAN Task View: [SportsAnalytics](SportsAnalytics.html)
  - [GitHub repository for this Task
    View](https://github.com/beanumber/ctv-sportsanalytics)
