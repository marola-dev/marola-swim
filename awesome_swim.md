# awesome_swim

Free and open source projects for swimming: tracking, training plans, competition data,
technique analysis, pools, swim spots, tides and currents. Surveyed on 2026-11-12 for
marola-swim. The diving list is [awesome_dive.md](awesome_dive.md).

## Method

1. **Search.** About 55 queries to GitHub's repository search API (`search/repositories`) on
   2026-11-12: the topics `swimming`, `swim`, `open-water-swimming`, `swimming-pool`,
   `triathlon`, `tides`, `tide`, `tidal`, and keywords for swim workouts and logs, meet files
   (Hy-Tek, Lenex, SDIF, SwimRankings), stroke detection and lap counting, open water, pool
   control and chemistry, bathing water quality, tide prediction, rip currents, lifeguards and
   drowning. Two web searches looked for projects outside GitHub.
2. **Filter.** A project stays when it serves swimmers, its code is public, and it declares a
   licence the OSI or FSF lists as free. "Swim" is a crowded word: the SWIM gossip protocol,
   swimlane diagrams, FAA SWIM, STM8 SWIM and swimmer plots went out.
3. **Verify.** Licence, language, last push, stars and archived state of each GitHub row were
   read again from the same API on 2026-11-12. Where the API returned no licence, the
   repository's `LICENSE`, `README`, `DESCRIPTION` or `package.json` was read; the Source
   column says which.
4. **Describe.** Each description paraphrases the project's own GitHub description or page.
   No project was installed or run for this survey.

"Last activity" is the last push to any branch. "Language" is what GitHub detects.
`⚠` marks something not checked. The projects under *General trackers and data access* are
listed because swimmers use them; whether each one records pool or open-water swims was not
checked ⚠.

What the search did not find: a maintained FOSS app for planning an open-water swim (route,
tide window, water quality in one place), and a FOSS pool-swim logger with stroke and lap
detection outside the watch vendors' ecosystems.


## Swim tracking and analysis

| Name | License | Language | What it is | Last activity | Stars | Source |
|---|---|---|---|---|---|---|
| [GoldenCheetah](https://github.com/GoldenCheetah/GoldenCheetah) | GPL-3.0 | C++ (GitHub detects Standard ML ⚠) | Performance analysis for cyclists, runners and triathletes. | 2026-11-08 | 2257 | GitHub API |
| [ActivityLog2](https://github.com/alex-hhh/ActivityLog2) | GPL-3.0 | Racket | Analyses swim, bike and run activities. | 2026-10-06 | 370 | GitHub API |
| [trackeR](https://github.com/trackerproject/trackeR) | GPL-3 | R (GitHub detects HTML) | R infrastructure for running, cycling and swimming data from GPS devices. | 2025-08-29 | 91 | GitHub API, license from its DESCRIPTION file |
| [TrackMyIndoorWorkout](https://github.com/TrackMyIndoorWorkout/TrackMyIndoorWorkout) | Apache-2.0 | Dart | Companion app that records workouts from indoor machines, swim ergometers included. | 2026-11-12 | 75 | GitHub API |
| [swim-data-analyser](https://github.com/PeterK-end/swim-data-analyser) | GPL-3.0 | JavaScript | Edits and analyses swim data from Garmin devices. | 2026-11-03 | 58 | GitHub API |
| [formgoggles-py](https://github.com/garrickgan/formgoggles-py) | MIT | Python | Python client for FORM swim goggles, from a reverse-engineered API and BLE protocol. | 2026-10-06 | 14 | GitHub API, license from its README |
| [nadamillas](https://github.com/Baltasarq/nadamillas) | MIT | Java | Android app that counts the metres you swim. | 2026-11-04 | 5 | GitHub API |

## General trackers and data access

| Name | License | Language | What it is | Last activity | Stars | Source |
|---|---|---|---|---|---|---|
| [Gadgetbridge](https://codeberg.org/Freeyourgadget/Gadgetbridge) | AGPL-3.0 | Java | Cloudless Android companion for wearables; development moved to Codeberg. | 2026-11-11 | 4603 | Codeberg, read 2026-11-12; stars are the archived GitHub mirror's |
| [GarminDB](https://github.com/tcgoetz/GarminDB) | GPL-2.0 | Python | Downloads and parses Garmin Connect and watch data into SQLite. | 2026-11-02 | 3367 | GitHub API |
| [Endurain](https://github.com/endurain-project/endurain) | AGPL-3.0 | Python | Self-hosted fitness tracking service. | 2026-11-12 | 2374 | GitHub API |
| [OpenTracks](https://codeberg.org/OpenTracksApp/OpenTracks) | Apache-2.0 | Java | Android sport tracker; development moved to Codeberg. | 2026-11-10 | 1400 | Codeberg, read 2026-11-12; stars are the archived GitHub mirror's |
| [FitTrackee](https://github.com/SamR1/FitTrackee) | AGPL-3.0 | Python | Self-hosted outdoor activity tracker; GitHub mirrors Codeberg. | 2026-11-04 | 1177 | GitHub API |
| [python-fitparse](https://github.com/dtcooper/python-fitparse) | MIT | Python | Python parser for ANT/Garmin FIT files. | 2025-01-28 | 827 | GitHub API |

## Workouts and training plans

| Name | License | Language | What it is | Last activity | Stars | Source |
|---|---|---|---|---|---|---|
| [swiML](https://github.com/bartneck/swiML) | MIT | HTML (XML schema) | XML language for writing swimming programs. | 2026-07-23 | 13 | GitHub API |
| [zoned](https://github.com/alarboulletmarin/zoned) | MIT | TypeScript | Browser-only endurance training sessions, plans and calculators; swimming included. | 2026-11-03 | 5 | GitHub API |
| [swim-gen](https://github.com/5pirit5eal/swim-gen) | Apache-2.0 | Go | Web app that generates swim training plans. | 2026-11-02 | 4 | GitHub API |
| [swimming-workout-assistant](https://github.com/eyalsch/swimming-workout-assistant) | GPL-3.0 | Python | Helper for running a swim workout. | 2024-06-09 | 3 | GitHub API |

## Competition: meets, results, formats

| Name | License | Language | What it is | Last activity | Stars | Source |
|---|---|---|---|---|---|---|
| [hytek-parser](https://github.com/SwimComm/hytek-parser) | MIT | Python | Parser for files from Hy-Tek Meet Manager. | 2026-10-13 | 29 | GitHub API |
| [wahoo-results](https://github.com/JohnStrunk/wahoo-results) | AGPL-3.0 | Python | Scoreboard that shows results from a CTS Dolphin timing system. | 2026-11-05 | 21 | GitHub API |
| [SwimClubMeet](https://github.com/Artanemus/SCM_SwimClubMeet-R) | GPL-3.0 | Pascal | Meet manager for swimming clubs. | 2026-10-15 | 8 | GitHub API |
| [sdif](https://github.com/tdsmith/sdif) | Apache-2.0 | Python | Python tools for USA Swimming SDIF v3 (sd3) files. | 2026-01-22 | 8 | GitHub API |
| [lenex-php](https://github.com/leonverschuren/lenex-php) | MIT | PHP | Lenex 3.0 in PHP. | 2020-07-09 (archived) | 8 | GitHub API |
| [turnmark](https://github.com/Stanback/turnmark) | GPL-3.0 | Python | Swim time conversion, published standards and local swim history. | 2026-10-26 | 7 | GitHub API |
| [js-lenex](https://github.com/Tiim/js-lenex) | MIT | TypeScript | Lenex 3.0 library for Node.js and the browser. | 2021-12-06 | 7 | GitHub API, license from its package.json |
| [Swimrankings](https://github.com/MauroDruwel/Swimrankings) | MIT | Python | Python library for data from swimrankings.net. | 2026-10-19 | 5 | GitHub API |
| [SwimRankings](https://github.com/Soneritics/SwimRankings) | MIT | C# | C# downloader of swimmer data from SwimRankings. | 2026-05-27 | 4 | GitHub API |
| [lenex-java](https://github.com/Tiim/lenex-java) | MIT | Java | Lenex 3.0 library for Java. | 2018-05-29 | 3 | GitHub API |
| [swimsnap](https://github.com/swimstandards/swimsnap) | Unlicense | PHP | Turns swim meet files into web pages. | 2026-08-19 | 3 | GitHub API |
| [Microplus-Lenex](https://github.com/Slthy/Microplus-Lenex) | MIT | Python | Scrapes Microplus events and encodes them as Lenex. | 2025-12-11 | 1 | GitHub API |

## Technique and computer vision

| Name | License | Language | What it is | Last activity | Stars | Source |
|---|---|---|---|---|---|---|
| [Swimming-Stroke-Rate-Analysis](https://github.com/agvdndor/Swimming-Stroke-Rate-Analysis) | MIT | Jupyter Notebook | Stroke rate from human pose estimation. | 2021-01-18 | 30 | GitHub API, license from its README (no LICENSE file ⚠) |
| [swim-stroke-analyzer](https://github.com/veluthoor/swim-stroke-analyzer) | MIT | Python | Freestyle technique analysis from video. | 2026-02-15 | 13 | GitHub API, license from its README (no LICENSE file ⚠) |

## Pools

| Name | License | Language | What it is | Last activity | Stars | Source |
|---|---|---|---|---|---|---|
| [raspipool](https://github.com/segalion/raspipool) | MIT | Python | Pool automation with Raspberry Pi and Home Assistant. | 2021-11-26 | 452 | GitHub API |
| [nodejs-poolController](https://github.com/tagyoureit/nodejs-poolController) | AGPL-3.0 | TypeScript | Controls pool equipment from several manufacturers. | 2026-10-22 | 409 | GitHub API |
| [pool-monitor-card](https://github.com/wilsto/pool-monitor-card) | MIT | JavaScript | Home Assistant card for pool water chemistry. | 2026-10-17 | 130 | GitHub API |
| [pool-controller](https://github.com/smart-swimmingpool/pool-controller) | MIT | C++ | ESP32 pool controller. | 2026-11-09 | 25 | GitHub API |
| [poupool](https://github.com/lostcontrol/poupool) | GPL-2.0 | Python | Control software for an overflow pool. | 2026-10-25 | 8 | GitHub API |
| [endless-pools-controller](https://github.com/szsz/endless-pools-controller) | MIT | HTML | Arduino controller with a web interface for Endless Pools swim machines. | 2026-11-10 | 7 | GitHub API |
| [homepool](https://github.com/alecc08/homepool) | MIT | TypeScript | Self-hosted pool chemistry monitoring with a Home Assistant integration. | 2026-11-10 | 5 | GitHub API |

## Swim spots and water quality

| Name | License | Language | What it is | Last activity | Stars | Source |
|---|---|---|---|---|---|---|
| [opendata](https://github.com/swimdrinkfish/opendata) | MIT | - | Open data standard for exchanging recreational water quality data. | 2020-11-11 | 12 | GitHub API |
| [open-bath-map](https://github.com/oklabflensburg/open-bath-map) | CC0-1.0 | Python | Interactive map of swimming and bathing places. | 2026-04-12 | 6 | GitHub API |

## Tides and currents

| Name | License | Language | What it is | Last activity | Stars | Source |
|---|---|---|---|---|---|---|
| [OpenDrift](https://github.com/OpenDrift/opendrift) | GPL-2.0 | Python | Framework for ocean trajectory modelling. | 2026-10-26 | 335 | GitHub API |
| [pyTMD](https://github.com/pyTMD/pyTMD) | MIT | Python | Tidal prediction in Python. | 2026-11-11 | 213 | GitHub API |
| [pytides](https://github.com/sam-cox/pytides) | MIT | Python | Tide prediction and analysis in Python. | 2024-03-17 | 180 | GitHub API |
| [UTide](https://github.com/wesleybowman/UTide) | MIT | Python (GitHub detects AGS Script) | Python port of the MATLAB UTide package. | 2026-10-28 | 172 | GitHub API |
| [slackwater](https://github.com/openwatersio/slackwater) | MIT | TypeScript | Tide and current prediction engine for TypeScript and Swift. | 2026-11-12 | 38 | GitHub API |
| [slackwater-database](https://github.com/openwatersio/slackwater-database) | MIT (code), per-file (data) | HTML | Station database for tide and current predictions; code MIT, each data file carries its own licence. | 2026-11-12 | 30 | GitHub API, license from its LICENSE file |
| [xtwsd](https://github.com/joelkoz/xtwsd) | GPL-3.0 | C++ | JSON web service over XTide. | 2025-01-02 | 21 | GitHub API |
| [HA_Noaa_Tides](https://github.com/Flight-Lab/HA_Noaa_Tides) | Apache-2.0 | Python | NOAA tides integration for Home Assistant. | 2025-07-15 | 9 | GitHub API |
| [tappy](https://github.com/timcera/tappy) | BSD-3-Clause | Python | Tidal analysis from the command line and as a Python package. | 2026-11-10 | 7 | GitHub API |
| [signalk-tides](https://github.com/openwatersio/signalk-tides) | Apache-2.0 | TypeScript | SignalK plugin for offline tide predictions. | 2026-11-12 | 5 | GitHub API |
| [tides](https://github.com/ryan-lang/tides) | MIT | Go | Harmonic tide prediction in Go. | 2023-12-10 | 4 | GitHub API |
| [slackwater-ios](https://github.com/openwatersio/slackwater-ios) | GPL-3.0 | Swift | Offline tide and current predictions on iPhone. | 2026-11-12 | 4 | GitHub API |
| [noaa-marine-mcp-server](https://github.com/cyanheads/noaa-marine-mcp-server) | Apache-2.0 | TypeScript | MCP server for NOAA tide stations, predictions, currents and buoys. | 2026-10-29 | 3 | GitHub API |
| [XTide](https://flaterco.com/xtide/) | not checked ⚠ | not checked ⚠ | Harmonic tide clock and tide predictor; current stable release 2.16. | not checked ⚠ | n/a | flaterco.com/xtide/files.html, read 2026-11-12 |

## Safety

| Name | License | Language | What it is | Last activity | Stars | Source |
|---|---|---|---|---|---|---|
| [Drowning-Detection-](https://github.com/randhana/Drowning-Detection-) | MIT | Python | Detects drowning in video with OpenCV and deep learning. | 2026-11-08 | 48 | GitHub API |

## Seen and left out

| Project | Why |
|---|---|
| [RTide](https://github.com/thomasmonahan/RTide) | Business Source License, not a free licence (its LICENSE file). |
| [brunnergino/swimming-recognition-lap-counting](https://github.com/brunnergino/swimming-recognition-lap-counting) | Code and data of an ISWC 2019 paper on stroke recognition and lap counting with a smartwatch; no licence declared. |
| [Irikos/rip_currents](https://github.com/Irikos/rip_currents) | Rip current detection and segmentation; no licence declared. |
| [SwimmeR](https://github.com/cran/SwimmeR) | R package for swim results; licence not checked ⚠. |
| Garmin, Strava and Home Assistant tooling in general | Too broad; only the pieces swimmers reach for are listed. |

## Sources

- GitHub REST API, `GET /search/repositories`, read 2026-11-12: <https://docs.github.com/en/rest/search/search#search-repositories>
- Each row's own repository (the Name link), and its LICENSE, README, DESCRIPTION or package.json where the Source column says so.
- Gadgetbridge on Codeberg: <https://codeberg.org/Freeyourgadget/Gadgetbridge>
- OpenTracks on Codeberg: <https://codeberg.org/OpenTracksApp/OpenTracks>
- XTide: <https://flaterco.com/xtide/files.html>

