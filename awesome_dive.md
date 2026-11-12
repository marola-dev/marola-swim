# awesome_dive

Free and open source projects for scuba diving and freediving: logs, dive computer download,
decompression libraries, planners, open hardware and media tools. Surveyed on 2026-11-12 for
marola-swim. The swimming list is [awesome_swim.md](awesome_swim.md).

**Never plan a dive on software you have not validated.** A listing here says the code is open,
not that it is correct or maintained.

## Method

1. **Search.** 23 queries to GitHub's repository search API (`search/repositories`) on
   2026-11-12: the topics `scuba-diving`, `scuba`, `diving`, `dive-computer`, `dive-log`,
   `decompression`, `freediving`, `buhlmann`, `subsurface`, `underwater-photography`, and the
   keywords scuba, dive computer, dive log, dive planner, Bühlmann, VPM-B, libdivecomputer,
   UDDF, rebreather, nitrox, trimix, freediving, apnea, opendiving. Four web searches added
   projects that live outside GitHub or have no topic.
2. **Filter.** A project stays when it is about diving, its code is public, and it declares a
   licence the OSI or FSF lists as free. Homonyms went out (CISA ScubaGear, the Subnautica
   Nitrox mod, sleep apnea, `dive` the Docker tool).
3. **Verify.** Licence, language, last push, stars and archived state of each GitHub row were
   read again from the same API on 2026-11-12, one `repo:` query per group of five. Where the
   API returned no licence or `NOASSERTION`, the repository's `LICENSE`, `README` or
   `DESCRIPTION` was read; the Source column says which.
4. **Describe.** Each description paraphrases the project's own GitHub description or page.
   No project was installed or run for this survey.

"Last activity" is the last push to any branch. "Language" is what GitHub detects.
`⚠` marks something not checked.


## Dive logs

| Name | License | Language | What it is | Last activity | Stars | Source |
|---|---|---|---|---|---|---|
| [Subsurface](https://github.com/subsurface/subsurface) | GPL-2.0 | C++ | Desktop and mobile dive log and planner; downloads from dive computers through its libdivecomputer fork. | 2026-11-12 | 3221 | GitHub API |
| [Submersion](https://github.com/submersion-app/submersion) | GPL-3.0 | Dart | Cross-platform dive log (Flutter) with UDDF import and export. | 2026-11-12 | 96 | GitHub API, license from its LICENSE file |
| [diveboard-web](https://github.com/Diveboard/diveboard-web) | GPL-3.0 | JavaScript | The Rails app behind the Diveboard online logbook. | 2026-10-27 | 13 | GitHub API |
| [Bubbletrail](https://github.com/bubbletrail/bubbletrail) | EUPL-1.2 | Dart | Dive log app in Dart. | 2026-11-11 | 7 | GitHub API |
| [OpenDiving](https://github.com/opendiving/opendiving) | AGPL-3.0 | Python | Self-hosted dive logbook: multi-gas dives, dive-computer imports, trips, gear, export in open formats. Install bundle; the app is the two repos below. | 2026-11-12 | 5 | GitHub API |
| [divecmd](https://github.com/kristapsdz/divecmd) | LGPL-2.1 | C | UNIX command-line tools to download and process dive computer data. | 2018-10-29 | 5 | GitHub API |
| [opendiving-api](https://github.com/opendiving/opendiving-api) | AGPL-3.0 | Python | OpenDiving backend: FastAPI, PostgreSQL, Redis. | 2026-11-12 | 4 | GitHub API |
| [opendiving-ios](https://github.com/opendiving/opendiving-ios) | Apache-2.0 | Swift | OpenDiving SwiftUI client; early stage, nothing to install yet. | 2026-11-12 | 4 | GitHub API |
| [opendiving-web](https://github.com/opendiving/opendiving-web) | AGPL-3.0 | TypeScript | OpenDiving frontend: Next.js. | 2026-11-12 | 3 | GitHub API |
| [Pelagic](https://github.com/wyvernp/pelagic) | MIT | TypeScript | Dive logbook and photo organiser that reads dive computers through libdivecomputer. | 2026-05-30 | 0 | GitHub API, license from its README; found through waterpixels.net |

## Dive computer download and data formats

| Name | License | Language | What it is | Last activity | Stars | Source |
|---|---|---|---|---|---|---|
| [libdivecomputer](https://github.com/libdivecomputer/libdivecomputer) | LGPL-2.1 | C | C library that talks to dive computers from many manufacturers; the base most logs here build on. | 2026-11-12 | 152 | GitHub API |
| [libdc](https://github.com/subsurface/libdc) | LGPL-2.1 | C | Subsurface's fork of libdivecomputer. | 2026-11-08 | 126 | GitHub API |
| [libdc-swift](https://github.com/deepsealabs/libdc-swift) | LGPL-2.1 | Swift | libdivecomputer for Swift apps. | 2026-11-07 | 18 | GitHub API |
| [dc2uddf](https://github.com/pridkett/dc2uddf) | MIT | C | Downloads a dive computer and writes UDDF. | 2026-08-03 | 8 | GitHub API |
| [dive_computer](https://github.com/DiveNote/dive_computer) | BSD-3-Clause | Dart | Flutter plugin for talking to dive computers. | 2024-07-18 | 6 | GitHub API |
| [PyDL7](https://github.com/johnstonskj/PyDL7) | MIT | Python | Python parser for DAN DL7 dive log files. | 2021-01-26 (archived) | 6 | GitHub API |
| [DC-agent](https://github.com/Diveboard/DC-agent) | GPL-3.0 | C++ | Agent that uploads dives from dive computers to Diveboard. | 2021-09-25 | 5 | GitHub API |
| [divejson](https://github.com/divejson/divejson) | MIT | - | Interchange format for dive logs: specification, JSON Schema, fixtures and a validator CLI. | 2026-11-07 | 3 | GitHub API |
| [uddf](https://github.com/ScubaGeek/uddf) | MIT | Ruby | Ruby gem that writes Universal Dive Data Format (UDDF) files. | 2022-06-07 | 3 | GitHub API |

## Converters and exporters

| Name | License | Language | What it is | Last activity | Stars | Source |
|---|---|---|---|---|---|---|
| [deepblu-tools](https://github.com/bluppfisk/deepblu-tools) | GPL-3.0 | Python | Backs up Deepblu dive logs as UDDF. | 2024-07-06 | 17 | GitHub API |
| [awu2uddf](https://github.com/djunkins/awu2uddf) | GPL-2.0 | Swift | iOS app that exports Apple Watch Ultra dives to UDDF. | 2025-06-21 | 14 | GitHub API |
| [divessi-export](https://github.com/gerardpuig/divessi-export) | MIT | Python | Backs up dive logs from the DiveSSI app. | 2026-11-05 | 12 | GitHub API |
| [SdeToFit](https://github.com/nradov/SdeToFit) | LGPL-2.1 | Java | Converts Suunto dive logs to FIT for Garmin Connect. | 2025-11-05 | 9 | GitHub API |
| [PADI-Logbook-exporter](https://github.com/karnovnik/PADI-Logbook-exporter) | MIT | JavaScript | Chrome extension that exports dive logs from PADI. | 2026-03-26 | 5 | GitHub API |
| [macdive-swiftai-gps](https://github.com/rbollar/macdive-swiftai-gps) | MIT | Python | Fills MacDive dive-site GPS from Shearwater Swift AI transmitter data. | 2026-07-30 | 4 | GitHub API |

## Planners and decompression libraries

| Name | License | Language | What it is | Last activity | Stars | Source |
|---|---|---|---|---|---|---|
| [GasPlanner](https://github.com/jirkapok/GasPlanner) | MIT | TypeScript | Web gas and decompression planner on Bühlmann ZHL-16. | 2026-11-11 | 60 | GitHub API |
| [dive](https://github.com/nyxtom/dive) | MIT | JavaScript | JavaScript library of standard scuba formulas and algorithms. | 2020-02-06 | 55 | GitHub API |
| [libbuhlmann](https://github.com/AquaBSD/libbuhlmann) | ISC | C | C library for decompression model calculations. | 2017-01-18 | 48 | GitHub API |
| [Abysner](https://github.com/NeoTech-Software/Abysner) | AGPL-3.0 | Kotlin | Dive and decompression planner for Android and iOS (Kotlin, Compose Multiplatform). | 2026-10-29 | 43 | GitHub API |
| [pydplan](https://github.com/eianlei/pydplan) | GPL-3.0 | Python | Bühlmann dive planner with a PyQt5 GUI. | 2025-10-10 | 33 | GitHub API |
| [dipplanner](https://github.com/ThomasChiroux/dipplanner) | GPL-3.0 | Python | Dive planner and decompression calculation in Python. | 2016-07-12 | 27 | GitHub API |
| [dive-deco](https://github.com/KG32/dive-deco) | MIT | Rust | Decompression models library in Rust. | 2026-08-20 | 24 | GitHub API |
| [Gas-Blending](https://github.com/divetools/Gas-Blending) | GPL-3.0 | Python | Python apps for gas blending. | 2023-02-28 | 13 | GitHub API |
| [capra](https://github.com/the-emerald/capra) | MIT | Rust | Decompression library in Rust. | 2021-08-25 | 11 | GitHub API |
| [opendeco](https://github.com/tsegers/opendeco) | MIT-0 | C | Bühlmann ZH-L16 with gradient factors, in C. | 2023-01-07 | 8 | GitHub API, license from its LICENSE file |
| [buoyancy-calculator](https://github.com/arendvw/buoyancy-calculator) | MIT | Vue | Scuba buoyancy calculator (Vue). | 2023-12-28 | 7 | GitHub API |
| [scalc](https://github.com/eianlei/scalc) | GPL-3.0 | JavaScript | Web calculators for planning technical dives. | 2026-10-09 | 5 | GitHub API |
| [Bubbles-Dive-Planner](https://github.com/Steelstone3/Bubbles-Dive-Planner) | GPL-3.0 | Rust | Dive planner application in Rust. | 2026-06-14 | 4 | GitHub API |
| [DiveR](https://github.com/gowachin/DiveR) | CeCILL-2 | R | R package that simulates dive planning. | 2022-10-09 | 4 | GitHub API, license from its DESCRIPTION file |
| [DecoTengu](https://wrobell.dcmod.org/decotengu/) | GPL-3.0 | Python | Python library for the Bühlmann model with Erik Baker's gradient factors; version 0.14.1. | not checked ⚠ | n/a | project page, read 2026-11-12; code at git.savannah.gnu.org/cgit/decotengu.git |

## Open hardware and firmware

| Name | License | Language | What it is | Last activity | Stars | Source |
|---|---|---|---|---|---|---|
| [DiveCAN](https://github.com/QuickRecon/DiveCAN) | MIT | Python | Reverse engineering of the Shearwater rebreather control bus. | 2026-08-10 | 27 | GitHub API |
| [arduino-nitrox-analyzer](https://github.com/ejlabs/arduino-nitrox-analyzer) | GPL-3.0 | C++ | Arduino nitrox analyzer. | 2018-08-17 | 19 | GitHub API |
| [openhaldane](https://github.com/markdgray/openhaldane) | Apache-2.0 | Python | Dive computer project in Python. | 2017-03-19 | 16 | GitHub API |
| [DiveCANHead](https://github.com/QuickRecon/DiveCANHead) | MIT | C | Rebreather head controller. | 2026-11-12 | 14 | GitHub API |
| [aegir](https://github.com/magnus188/aegir) | GPL-3.0-only + CERN-OHL | C | ESP32-P4 trimix analyzer prototype; software GPL-3.0-only, hardware under a CERN Open Hardware Licence. | 2026-11-11 | 14 | GitHub API, licenses from its LICENSE.md |
| [DiveIno](https://github.com/kornel-schrenk/DiveIno) | MIT | C | DIY dive computer for makers. | 2026-06-30 | 13 | GitHub API |
| [ios-dive-computer](https://github.com/felddy/ios-dive-computer) | MIT | - | Dive computer app for the Apple Watch Ultra. | 2022-09-08 | 3 | GitHub API |

## Video, photo and species

| Name | License | Language | What it is | Last activity | Stars | Source |
|---|---|---|---|---|---|---|
| [dive-color-corrector](https://github.com/bornfree/dive-color-corrector) | GPL-3.0 | Python | Colour correction for underwater photos and video. | 2025-11-26 | 158 | GitHub API |
| [depthviz](https://github.com/noppanut15/depthviz) | Apache-2.0 | Python | Depth overlay for freediving videos, with or without a dive computer. | 2025-12-30 | 35 | GitHub API |
| [unabara](https://github.com/arnauddupuis/unabara) | GPL-2.0 | C++ | Telemetry overlay for dive videos. | 2026-11-09 | 34 | GitHub API |
| [ScubaOverlay](https://github.com/vldgeorgiev/ScubaOverlay) | GPL-3.0 | Python | Dive computer video overlay generator. | 2026-01-06 | 13 | GitHub API |
| [idguru](https://github.com/liquidguru/idguru) | AGPL-3.0 | Python | Underwater species identifier for video and photo archives. | 2026-10-07 | 6 | GitHub API |
| [wayfinder](https://github.com/deepsealabs/wayfinder) | Apache-2.0 | - | Reconstructs dive routes from dive-computer IMU data by dead reckoning. | 2026-09-04 | 3 | GitHub API |

## Dive sites and conditions

| Name | License | Language | What it is | Last activity | Stars | Source |
|---|---|---|---|---|---|---|
| [Divemap](https://github.com/kargig/divemap) | Apache-2.0 | Python | Dive site map project. | 2026-11-08 | 6 | GitHub API |
| [garmin-divesite-weather-widget](https://github.com/mikeller/garmin-divesite-weather-widget) | GPL-3.0 | Monkey C | Garmin watch widget with weather at a dive site. | 2026-11-09 | 3 | GitHub API |

## Freediving

| Name | License | Language | What it is | Last activity | Stars | Source |
|---|---|---|---|---|---|---|
| [bearth_timer](https://github.com/konyshevgmbh/bearth_timer) | MIT | Dart | Breath-hold timer for freediving and breathwork (Flutter). | 2026-05-28 | 4 | GitHub API |
| [Apno](https://github.com/guillermodotn/apno) | MIT | Python | Apnea trainer with O2 and CO2 tables and session history. | 2026-10-01 | 0 | GitHub API; found through guillermodotn.github.io/apno |

## Seen and left out

| Project | Why |
|---|---|
| [BlueDive](https://github.com/houle988/BlueDive) | "BlueDive Source Available License", not a free licence (its LICENSE file). |
| [Dive Exporter](https://simonecarletti.com/blog/2026/05/dive-exporter-release/) | Free of charge, but its author says the BLE library under it is closed source. |
| [mikeller/ostc4](https://github.com/mikeller/ostc4) | Mirror of the heinrichs weikamp OSTC4 firmware; no licence file found in the mirror, and the upstream at code.heinrichsweikamp.com was not read ⚠. |
| [bwaite/vpmb](https://github.com/bwaite/vpmb) | VPM-B in Python; no licence declared. |
| [vldgeorgiev/scuba-gas-analyzer](https://github.com/vldgeorgiev/scuba-gas-analyzer) | DIY trimix and CO analyzer; no licence declared. |
| [robinmoisson/freediving](https://github.com/robinmoisson/freediving) | O2/CO2 table trainer; no licence declared, last push 2017. |
| Kenozooid | Dive logger by DecoTengu's author; not checked ⚠. |
| Underwater image enhancement papers (FUnIE-GAN, Water-Net, UWCNN and others) | Research code, mostly without a licence; out of scope for diver tooling. |

## Sources

- GitHub REST API, `GET /search/repositories`, read 2026-11-12: <https://docs.github.com/en/rest/search/search#search-repositories>
- Each row's own repository (the Name link), and its LICENSE, README or DESCRIPTION where the Source column says so.
- DecoTengu: <https://wrobell.dcmod.org/decotengu/>
- Apno: <https://guillermodotn.github.io/apno/>
- Dive Exporter: <https://simonecarletti.com/blog/2026/05/dive-exporter-release/>
- Pelagic thread: <https://waterpixels.net/forums/topic/3458-pelagic-dive-logbook-and-photo-organiser/>
- divecmd: <https://kristaps.bsd.lv/divecmd>

