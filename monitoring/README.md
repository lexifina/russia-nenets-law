<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Nenets Autonomous Okrug only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-24 14:15 UTC, Nenets Autonomous Okrug: Official Internet Portal of Legal Information (region83): 9 addresses read; 15 added, 0 changed, 0 removed; changes found; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Nenets Autonomous Okrug: Official Internet Portal of Legal Information (region83)](http://publication.pravo.gov.ru/documents/block/region83) | `zakony-<year>/` | daily | 2026-11-24 14:15 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-24 14:14](checks/2026-11.md#ru-pravo-nenets-20261124t141429z) | pravo-nenets | 9 | 15 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-nenets-law/compare/bcb836966a21...663221190ab2) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
