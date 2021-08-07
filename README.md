# E3DC Power Station to openHAB

This repository contains openHAB configuration files for extracting data from the E3DC Power Station, store the data on the Synology NAS in a MariaDB, and (soon) visualise it on a dashboard.

## Done

- [x] Build dashboard
- [x] Install Grafana (or some other visualisation tool) on the Pi
  - [x] Set it up to talk to the data stored in the NAS
- [x] Add all the other KPIs
- [x] Persistence on the Synology NAS
  - [x] Setup MariaDB on the NAS
  - [x] Setup JDBC drivers on the Pi
- [x] Persistence every minute for testing
- [x] Let Pi and DB run for a week and test the persistence
