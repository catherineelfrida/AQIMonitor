AWMonitor
==
Routes
--
- /: contains opengraph image for sharing
- /api: global summary
- /api/og: generate a summary open graph image

# COVID-19 API

![last_cron_date](https://img.shields.io/endpoint?url=https://covid19.mathdro.id/api/statusbadge?status=last_cron_date&style=flat-square)
![og_cron_status](https://img.shields.io/endpoint?url=https://covid19.mathdro.id/api/statusbadge?status=og_cron_status&style=flat-square)
![daily_cron_status](https://img.shields.io/endpoint?url=https://covid19.mathdro.id/api/statusbadge?status=daily_cron_status&style=flat-square)

> Serving data from John Hopkins University CSSE as a [JSON API](https://covid19.mathdro.id)

[![Deploy with ZEIT Now](https://zeit.co/button)](https://zeit.co/import/project?template=https://github.com/mathdroid/covid-19-api)

## Routes

- /: contains opengraph image for sharing

- /api: global summary

- /api/og: generate a summary open graph image

- /api/confirmed: global cases per region sorted by confirmed cases

- /api/recovered: global cases per region sorted by recovered cases

- /api/deaths: global cases per region sorted by death toll

- /api/daily: global cases per day

- /api/daily/[date]: detail of updates in a [date] (e.g. /api/daily/2-14-2020)
