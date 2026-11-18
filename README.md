## Pro-Pacer
Race Day Elevation & Pacing Planner

A Python-based race strategy and pacing optimization tool designed to calculate realistic, mile-by-mile target splits based on course elevation profiles and an athlete's target base pace.

Developed as a semester project for Application Development I.

## Project Overview

Runners—especially those competing on hilly terrain—often face significant challenges with pacing strategy on race day. Attempting to maintain a static pace up steep inclines leads to premature exhaustion and lactic acid build-up, while failing to capitalize on descents can result in missed goal times.

The Race Day Elevation & Pacing Planner takes the guesswork out of race strategy:

Elevation Profile Analysis: Processes course elevation data mile-by-mile to determine localized slope gradients.

Physiological Gradient Weighting: Dynamically adjusts pace targets using physics-based hill effort modeling (adding time for uphill climbs and banking time on descents).

Target Normalization: Mathematically scales raw adjusted splits so the overall finished race time precisely matches the runner's overall target pace.

Course Repository & Custom Imports: Includes a built-in catalog of local Georgia races and supports custom GPX map uploads.

File I/O Parsing & Export:

Parses standard XML/GPX course files from platforms like Garmin Connect, Strava, and MapMyRun.

Generates printable, formatted .csv pace cards for athletes and coaches.

## Target Audience

Everyday Runners: Athletes training for 5Ks, 10Ks, half-marathons, or marathons looking for a smart, hill-adjusted pacing strategy.

Running Coaches & Local Clubs: Coaches generating quick, customized split charts and physical pace cards for their teams based on specific race courses.


