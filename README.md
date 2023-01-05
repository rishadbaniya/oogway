# Hyperblow - A torrent client that throws real left blow

**Currently this project is in a complete rewrite**

[![dependency status](https://deps.rs/repo/github/rishadbaniya/hyperblow/status.svg)](https://deps.rs/repo/github/rishadbaniya/hyperblow)


It's gonna take time, good things do take time

## Features checklist :
- ✅ Accepts torrent file as input
- ☐ Accepts magnet uri as input
- ✅ Support for UDP Trackers
- ☐ Support for HTTP Trackers
- ☐ Has rare piece first algorithm
- ☐ Implements Choking and Unchoking Algorithm
- ☐ Implements Fast Extension
- ☐ Implements extension for partial seeds
- ☐ Implements Extension Protocol

Supported BEP's:

- ✅ [BEP15](http://www.bittorrent.org/beps/bep_0015.html) : UDP Tracker Protocol (Implements partially, except scrape req and res)


TODO : 
- ✅ Implement the ".torrent" file parser
- ✅ Implement the MagnetURI verifier and parser
- ☐ Handle redundancy of both the tracker URL's in "announce" and "announce-list" field
- ☐ Make use of Crossbeam crate's Concurrency Primitives
- ☐ Add both Unit and Integration testing for the parsing library 
- ☐ Re architect the entire CLI application's system design

