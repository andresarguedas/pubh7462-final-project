
<!-- README.md is generated from README.Rmd. Please edit that file -->

# PubH 7462 Final Project

<!-- badges: start -->
<!-- badges: end -->

**Evolution of Major League Baseball from the Dead Ball Era to Post
Steroid Era, 1871-2021**

Andres Arguedas

Anthony Johnson

Eric Connor

**Project Proposal**

***Purpose***

As diehard baseball fans, we have become interested in the development
and progress of the play in Major League Baseball. The game is currently
played much differently than decades ago, and has been innovated to suit
the tastes of today’s youth. Many fans have become increasingly
concerned about the pace of play, and the play in the postseason. This
concern of pace of play consists of a large number of pitching changes
throughout games in the modern game.

***Data Source***

Data was collected from Retrosheet, an organization that tracks
individual Major League Baseball game statistics. These data consist of
225,631 individual game data (regular season and postseason) from
1871-2021. Primary variables of this study are reported at the
individual game level, and include (among other variables):

-   Date

-   Home and visiting team

-   Ballpark

-   Attendance

-   Final score

-   Umpires

-   Pitcher statistics (number used, earned runs, walks, wild pitches,
    winning pitcher, etc.)

-   Batting statistics (at-bats, hits, doubles, triples, home runs,
    runs, etc.)

-   Defensive statistics (putouts, assists, errors, etc.)

-   Managers

-   Starting players

-   Regular season vs. Postseason game

***Research Questions***

-   **Question 1:** Did the number of pitchers used in a game increase
    over time (both between seasons and within seasons)?

    -   We would just have one plot be interactive with a trend line and
        individual points for a recent single season. We will also plot
        the average number of pitchers used for each season from 1871 to
        now (when there is enough data to do this).

-   **Question 2:** Do different umpires/ballparks/teams have more
    runs/K/walks than others in the 21st century?

    -   An interactive table will be created with the desired
        information, so the user can filter and sort ballparks according
        to the desired statistic, and represent these values using
        meaningful color scales.

-   **Question 3:** What day of the week is there the highest batting
    average? Is this different between weekdays and weekends? What about
    across months? Does this behavior also apply to home runs or total
    runs in a game?

    -   For this case different interactive plots will be created, one
        for each statistic of interest, which the user can choose
        between to compare their behavior. This can also be made into a
        Dashboard putting together these plots for comparing individual
        days vs. months.

-   **Question 4:** How has the game evolved between regular season play
    and the postseason? These questions will consist of time of game,
    home and away team game statistics, and home-field advantage or win
    probability, based on whether the games are regular season or
    postseason.

    -   A series of R plotly figures will be created to allow for an
        interactive interface to view various information per year. In
        addition, an R flexdashboard may be created to allow viewers
        multiple displays of the innovation of MLB throughout the year.

***Group members’ contributions:***

1.  Data cleaning and manipulation: Eric Connor

2.  Overall website construction: Andres Arguedas

3.  Static plot creation: Anthony Johnson

4.  Interactive plot creation: Eric Connor

5.  Dashboard creation: Anthony Johnson

6.  Finalizing website, plot, and dashboard graphic design: Andres
    Arguedas
