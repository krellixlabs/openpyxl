# Krellix openpyxl archive

This Git repository contains the source snapshot of openpyxl 3.1.5, with this provenance note and Mercurial archive metadata added.

Canonical upstream: https://foss.heptapod.net/openpyxl/openpyxl
Upstream Mercurial revision: `13627b03ca25a1a98becf40e533b955615b13429`
Original license: MIT (see LICENCE.rst).

Full upstream Mercurial history is preserved separately in the `openpyxl-history-2026-11-07.hg` asset on the `krellix-3.1.5` release. It contains 9709 changesets and was verified by restoring and comparing every changeset hash. The Git snapshot commit is a company archive commit, not an upstream commit.

Restore the original history using Mercurial:

```sh
hg init openpyxl-history
hg -R openpyxl-history unbundle openpyxl-history-2026-11-07.hg
hg -R openpyxl-history update 3.1.5
```

The same release includes the original PyPI source distribution and wheel.
