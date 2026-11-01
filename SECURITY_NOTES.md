2026-11-01 – Anonymous API security baseline

- [GET] /recipes → 200 OK, returns all recipes including one with "is_public": false.
- [DELETE] /recipes/2 → 204 No Content. Follow-up [GET] /recipes/2 → 404 "recipe not found" (anonymous delete works with no identity check).
