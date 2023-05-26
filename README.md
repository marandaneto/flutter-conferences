Conferences
===========

A community-curated list of conferences around the world for Flutter developers.


Adding a conference
-------------------

Send a pull-request which adds a file to the `_conferences/` directory
with a new file representing the conference. The file should be named
with the conference name, the year, and with an `.md` extension (for
example, `my-cool-conference-2016.md`).

The contents of the file should use the following template:
```
---
name: "Flutter Friends"
website: https://www.flutterfriends.dev/
location: Stockholm, Sweden
online: false

date_start: 2023-09-03
date_end:   2023-09-05

cfp:
  start: 2023-01-01
  end:   2023-06-10
  site: https://airtable.com/shrnDA3TEqc9zS5qb
---
```

*Note: Do not include the location of the conference in the name. The above conference is often referred to as "Droidcon London", but we will always render the location with the name so it is redundant.*

### Online-only events

For online only events please set `online: true` in the template. They will show up in the _Upcoming_ page as well as in the [Online-only](https://marandaneto.github.io/flutter-conferences/online.html) page.


Running locally
---------------
![Build Jekyll Pages](https://github.com/marandaneto/flutter-conferences/workflows/Build%20Jekyll%20Pages/badge.svg)

```
bundle install --path vendor/bundle
bundle exec jekyll serve
```

Once running the site can be opened at http://localhost:4000.


License
-------

All content is [CC0][1].


 [1]: https://creativecommons.org/publicdomain/zero/1.0/
