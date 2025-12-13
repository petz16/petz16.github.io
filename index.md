These are ideas I have for future data analyses/visualizations, focusing primarily on advanced metrics in baseball (MLB) and basketball (NCAAW).

Data Sources and Project Ideas


### 1. **MLB Hitter Metrics** ([Batter-stats-2025](https://baseballsavant.mlb.com/leaderboard/custom?year=2025&type=batter&filter=&min=q&selections=pa%2Ck_percent%2Cbb_percent%2Cwoba%2Cxwoba%2Csweet_spot_percent%2Cbarrel_batted_rate%2Chard_hit_percent%2Cavg_best_speed%2Cavg_hyper_speed%2Cwhiff_percent%2Cswing_percent&chart=false&x=pa&y=pa&r=no&chartType=beeswarm&sort=xwoba&sortDir=desc), [exit_velocity](https://baseballsavant.mlb.com/leaderboard/statcast), [bat-tracking](https://baseballsavant.mlb.com/leaderboard/bat-tracking))
* **Description:** Comprehensive 2025 season stats for batters, featuring expected metrics (<span title="Expected Weighted On-Base Average. Uses Statcast data (like exit velocity and launch angle) to estimate the offensive value of a batter's contact, independent of defensive play.">**xwoba**</span>), contact quality (<span title="The percentage of batted balls hit with a launch angle between 8° and 32°, maximizing the chance for a hit.">**sweet_spot_percent**</span>, <span title="Barrel Batted Ball Rate. The percentage of batted balls classified as a Barrel, the ideal combination of exit velocity and launch angle for maximum damage.">**barrel_batted_rate**</span>), and detailed Bat Tracking metrics (e.g., <span title="The average speed of the bat's head at the moment of impact.">**avg_bat_speed**</span>, hard_swing_rate).
* **Project Idea:** Investigate the value of Bat Speed. Correlate <span title="The average speed of the bat's head at the moment of impact.">**avg_bat_speed**</span> and <span title="The percentage of batted balls hit at 95 MPH or greater.">**hard_hit_percent**</span> with actual outcomes (<span title="Weighted On-Base Average. A metric that weighs the value of each outcome (walk, single, double, etc.) based on its run-producing value.">**woba**</span>).

### 2. **MLB Pitch Tempo Analysis** ([pitch_tempo](https://baseballsavant.mlb.com/leaderboard/pitch-tempo))
* **Description:** Data focused on the pace of play for pitchers, including median seconds between pitches in empty and on-base situations, and frequency of 'hot', 'warm', or 'cold' tempo classifications.
* **Project Idea:** Analyze the impact of the Pitch Clock rule change. Does a slower median tempo correlate with higher walk rates (<span title="Walk Percentage. The number of walks divided by the number of plate appearances.">**bb_percent**</span>) or lower strikeout rates (<span title="Strikeout Percentage. The number of strikeouts divided by the number of plate appearances.">**k_percent**</span>)?

### 3. **MLB Batting Stance Metrics** ([batting-stance](https://baseballsavant.mlb.com/visuals/batting-stance))
* **Description:** Data providing average physical metrics related to a batter's stance and setup, such as foot separation (avg_foot_sep) and stance angle (avg_stance_angle).
* **Project Idea:** See if specific stance characteristics (e.g., greater foot separation or a more open/closed angle) correlate with improved contact quality (<span title="The percentage of batted balls hit with a launch angle between 8° and 32°, maximizing the chance for a hit.">**sweet_spot_percent**</span> or reduced <span title="Whiff Percentage. The number of swings that result in a miss divided by the total number of swings.">**whiff rate**</span>).

### 4. **NCAAW Tournament Data** ([ncaa-womens-basketball-tournament-history](https://fivethirtyeight.com/features/louisiana-tech-was-the-uconn-of-the-80s/))
* **Description:** A record of the NCAA Women's Basketball Tournament performance (Seeding, Conf. W/L, Tourney Finish).
* **Project Idea:** Calculate and visualize the average tournament round reached for every seed number ($\text{1}$ through $\text{16}$) over the history of the tournament.


## Where's Schueller?

<iframe src="my_plot.html" width="100%" height="600" style="border:none;">
  <p>Your browser does not support iframes.</p>
</iframe>


## [Completed Final Project for CS 215](https://github.com/petz16/CS-215-Final)
* Final project examining new baseball statistic vs. fastball velocity

