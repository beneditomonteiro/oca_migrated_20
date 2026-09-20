# oca_migrated_20

OCA modules ported to **Odoo 20** by the Maxdoo Team, for use while the official OCA
`20.0` branches are not released yet.

Layout mirrors `oca_migrated_19`: `<OCA repository name>/<module>` (the first level is the
"wrapper" directory named after the OCA repo the module comes from, e.g. `web/web_responsive`
comes from `OCA/web`).

Each ported module keeps its original authors, copyrights and license, and carries a comment in
its `__manifest__.py` stating it is a simple port and giving the upstream commit it was taken
from. Once the official OCA version for Odoo 20 exists, prefer it over the one here.

| Module | From | Upstream base | Status |
|---|---|---|---|
| `web/web_responsive` | OCA/web `19.0` | `d3748a6ea5` | Beta - runs on Odoo 20, Hoot + Python tests pass |
