# Hi, I'm Miha 👋

I'm a Python developer with a background in backend development and data engineering. I enjoy figuring out why systems aren't behaving as expected, especially when things look fine on the surface but the data tells a different story.

I'm also a keen runner and tennis enthusiast, with an interest in sports data and the technology behind fitness and training applications.

## RunWx

[RunWx](https://github.com/mifuha/runwx) is my personal project exploring race pace and weather across different editions of the same race.

[View the comparison](https://runwx-api-f6n35ol7sa-ew.a.run.app/).

It combines historical race results and hourly weather data in a Python and dbt pipeline on Google Cloud Platform (GCP). Cloud Storage holds pipeline artifacts, BigQuery stores and analyses the data, and Cloud Run runs processing jobs and serves the comparison website. Much of the work involves messy source data, timestamps and making loads repeatable.

I also built Airflow workflows to coordinate the pipeline, validating the historical workflow on Google Cloud Composer.

It's still evolving. The comparisons explore patterns rather than establish cause and effect.

## Selected open-source contributions

- [**Prefect**](https://github.com/PrefectHQ/prefect/pull/23412) · **Merged** — Added opt-in clearing of deployment schedules, preserving existing behaviour and covering CLI and SDK compatibility.
- [**Kloppy**](https://github.com/PySport/kloppy/pull/631) · **Merged** — Identified and fixed dataset filtering that unexpectedly changed player timelines and minutes played in the original dataset.
- [**python-garminconnect**](https://github.com/cyberjunky/python-garminconnect/pull/470) · **Merged** — Traced broken HTTP 404 handling to missing response details and fixed empty-result handling for gear requests.
- [**Stravalib**](https://github.com/stravalib/stravalib/pull/747) · **Merged** — Updated token revocation for Strava's new OAuth endpoint, with authentication handling and regression tests.
- [**DataBallPy**](https://github.com/Alek050/databallpy/pull/403) · **Merged** — Identified and fixed failures when saving NumPy numeric game metadata to JSON, with save/load regression tests.
- [**dlt**](https://github.com/dlt-hub/dlt/pull/4548) · **Open PR** — Identified incremental state loss when switching between dictionaries and Arrow/pandas data; proposed a fix to prevent duplicate loads.
