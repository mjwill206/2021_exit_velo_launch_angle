
# 2021 Exit Velocities & Launch Angles 

#### (as of 7/29/2021)

I completed a quick examination of the relationship between exit velocities and launch angles for qualified batters during the 2021 MLB season through July 28th, 2021. 

## Data:
The data was retrieved from Baseball Savant, using only batting data for qualified batter up to July 29th for the 2021 season.

## EDA:

![plot](/plot.png)

|    | full_name    |   exit_velocity_avg |   launch_angle_avg | slash_line          |   b_home_run |
|---:|:-------------|--------------------:|-------------------:|:--------------------|-------------:|
| 62 | Adam Duvall  |                90.3 |               24   | .228/.276/.478/.755 |           22 |
| 71 | Raimel Tapia |                86.5 |               -3.1 | .286/.34/.385/.725  |            5 |

|     | full_name      |   exit_velocity_avg |   launch_angle_avg | slash_line          |   b_home_run |
|----:|:---------------|--------------------:|-------------------:|:--------------------|-------------:|
|  54 | Aaron Judge    |                95.9 |               10   | .283/.377/.52/.898  |           21 |
| 118 | David Fletcher |                82.5 |                7.8 | .305/.328/.379/.708 |            2 |

## Results:
There is a positive relationship between average exit velocities and launch angles. This is intuitive - one would think that if you hit the ball harder on average that the angle at which the ball leaves the bat would be greater.

Some interesting notes:
- Yankees' slugger Aaron Judge has the highest average exit velocity (95.9 mph), while Angels' David Fletcher has the lowest (82.5).
- There's no "Coors Effect" for the Rockies' Raimel Tapia. He not only owns the lowest launch angle; he is the only qualified batter with a *negative* average launch angle (-3.1 degrees).
- The Braves' re-acquired Adam Duvall ahead of the trade deadline, owner of the league leading average launch angle (24 degrees).
