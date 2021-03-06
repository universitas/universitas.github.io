---
layout: default
---

[Universitas](http://universitas.no) Startsiden er en portal til alt du som ansatt trenger av informasjon, dokumenter og lenker til andre systemer.

## Filer
Her finner du diverse dokumenter du kanskje trenger. Alt fra timelister til sideoversikt.

- [Timeliste]({{ site.url }}/pdf/timeliste.pdf)
- [Sideoversikt]({{ site.url }}/pdf/sideoversikt.pdf)
- [Sideoversikt magasinet]({{ site.url }}/pdf/sideoversikt_magasin.pdf)

## Diverse lenker:
- [Prodsys](http://universitas.no/prodsys/)
- [Medarbeiderliste](https://docs.google.com/spreadsheets/d/1uxtmDUd8Z6PkeF9SHpDPhhEL8AxZ0yUskgcLLqDF6x4/edit?usp=sharing&authkey=CL2FxbQC)
- [USIT it-support](http://www.uio.no/tjenester/it/kontakt/lokal-it/andre-enheter/it-universitas.html)
- [Slack](https://universitas.slack.com/messages)

## Tekniske lenker universitas.no
- [google analytics](https://analytics.google.com/analytics/web/)
- [facebook developer](https://developers.facebook.com/apps/1936304073248701/dashboard/)
- [google adsense](https://www.google.com/adsense/)
- [vps hos linode.com](https://manager.linode.com/linodes/dashboard/tassen-docker) <sup>passordbeskyttet
- [feilmeldinger hos sentry.io](https://sentry.io/universitas/) <sup>passordbeskyttet
- [docker hub](https://hub.docker.com/u/universitas/)

## [universitas på github](https://github.com/universitas/)
- [kildekode universitas.no og prodsys](https://github.com/universitas/universitas.no)
- [skript for univ-desken og indesign](https://github.com/universitas/tassendesken)
- [kildekoden for startsiden](https://github.com/universitas/universitas.github.io) Denne siden :)


## Wordmaler:

{%- for file in site.static_files -%}
{% if file.extname == ".doc" %}
- [{{ file.name }}]({{ file.path }})
{%- endif -%}
{%- endfor -%}
