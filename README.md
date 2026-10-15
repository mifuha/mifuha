# Hi, I'm Miha 👋

I'm a Python developer with a background in backend development and data engineering. I enjoy figuring out why systems aren't behaving as expected, especially when things look fine on the surface but the data tells a different story.

I'm also a keen runner and tennis enthusiast, with an interest in sports data and the technology behind fitness and training applications.

## RunWx

[RunWx](https://github.com/mifuha/runwx) is my personal project exploring race pace and weather across different editions of the same race.

It combines historical race results and hourly weather data using Python, BigQuery, dbt and Cloud Run to power a small comparison website. Much of the work involves messy source data, timestamps and making loads repeatable.

It's still evolving. The comparisons explore patterns rather than establish cause and effect.

## Selected open-source contributions

- [**Kloppy**](https://github.com/PySport/kloppy/pull/631) · **Merged** — Fixed dataset filtering that unexpectedly changed player timelines and minutes played in the original dataset.
- [**Stravalib**](https://github.com/stravalib/stravalib/pull/747) · **Merged** — Updated token revocation for Strava's new OAuth endpoint, with authentication handling and regression tests.
- [**GarminDB**](https://github.com/tcgoetz/GarminDB/pull/329) · **Merged** — Added a simple progress-output mode to make imports easier to follow in Docker and captured logs.
- [**SportsDataverse**](https://github.com/sportsdataverse/sportsdataverse-py/issues/564) · **Bug report, fixed upstream** — Found a validation command reporting success when every comparison failed. Another contributor [implemented the fix](https://github.com/sportsdataverse/sportsdataverse-py/pull/711).
- [**dlt**](https://github.com/dlt-hub/dlt/pull/4548) · **Open PR** — Proposed a fix for duplicate rows in incremental loads when switching between dictionaries and Arrow/pandas data.
- [**Apache Iceberg (Python)**](https://github.com/apache/iceberg-python/pull/4024) · **Open PR** — Added regression coverage for schema changes and appended rows surviving concurrent commit retries.
