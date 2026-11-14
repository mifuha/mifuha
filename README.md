# Hi, I'm Miha 👋

I'm a Python developer with a background in backend development and data engineering. I enjoy figuring out why things aren't working as expected, especially when the code runs but the data looks wrong.

I'm also a keen runner and tennis enthusiast, so I'm naturally drawn to sports data and the technology behind fitness apps.

## RunWx

[RunWx](https://github.com/mifuha/runwx) is my personal project comparing race pace and weather across five courses and 61 editions. [View the comparison](https://runwx-api-f6n35ol7sa-ew.a.run.app/).

It uses Python and dbt on Google Cloud (GCP): Cloud Storage for files, BigQuery for analysis, and Cloud Run for processing jobs and the read-only API behind the website.

Much of the work involves validating messy source data, avoiding duplicate loads and independently checking warehouse results. I also built Airflow workflows and tested the historical pipeline on Cloud Composer.

It's still evolving. The comparisons explore patterns rather than establish cause and effect.

## Selected open-source contributions

- [**Prefect**](https://github.com/PrefectHQ/prefect/pull/23412) · **Merged** — Added an option to clear deployment schedules while preserving the default behaviour, with CLI and SDK tests.
- [**Stravalib**](https://github.com/stravalib/stravalib/pull/758) · **Merged** — Found and fixed handling that could ignore a Strava API rate limit, while keeping custom limiters compatible.
- [**Kloppy**](https://github.com/PySport/kloppy/pull/631) · **Merged** — Found and fixed dataset filtering that changed player timelines and minutes played in the original data.
- [**dlt**](https://github.com/dlt-hub/dlt/pull/4548) · **Open PR** — Found incremental state loss when switching between dictionaries and Arrow/pandas data; proposed a fix to prevent duplicate loads.
- [**python-garminconnect**](https://github.com/cyberjunky/python-garminconnect/pull/470) · **Merged** — Traced broken HTTP 404 handling to missing response details and fixed empty-result handling for gear requests.
- [**DataBallPy**](https://github.com/Alek050/databallpy/pull/403) · **Merged** — Found and fixed failures when saving NumPy game metadata to JSON, with save/load regression tests.
