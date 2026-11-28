<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Nenets Autonomous Okrug only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 05:47 UTC, Nenets Autonomous Okrug: Official Internet Portal of Legal Information (region83): 9 addresses read; 0 added, 0 changed, 0 removed; no change; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Nenets Autonomous Okrug: Official Internet Portal of Legal Information (region83)](http://publication.pravo.gov.ru/documents/block/region83) | `zakony-<year>/` | daily | 2026-11-28 05:47 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 05:46](checks/2026-11.md#ru-pravo-nenets-20261128t054659z) | pravo-nenets | 9 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-27 05:39](checks/2026-11.md#ru-pravo-nenets-20261127t053916z) | pravo-nenets | 9 | 3 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-nenets-law/compare/66f324029da4...6034bd6225c7) |
| [2026-11-26 05:43](checks/2026-11.md#ru-pravo-nenets-20261126t054344z) | pravo-nenets | 9 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-25 06:17](checks/2026-11.md#ru-pravo-nenets-20261125t061740z) | pravo-nenets | 9 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 14:14](checks/2026-11.md#ru-pravo-nenets-20261124t141429z) | pravo-nenets | 9 | 15 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-nenets-law/compare/bcb836966a21...663221190ab2) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
