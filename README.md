# Alongside

A phone-first app that helps single parents carry the load of two: a daily planner with a "lean day" mode, an emergency card, and a community time-bank for swapping help with approved neighbours.

## Files
- `index.html` — the whole app (single self-contained page: HTML, CSS and JS).

## How it runs
It was built as a Claude artifact. Shared data (members, posts, claims, check-ins, reports) uses the artifact `db` capability, and identity uses the `user` capability, so the community features only work when the page is opened inside a Claude artifact viewer. Outside that, the planner and emergency card still work and save to the browser's local storage.

## Known limits
- No SMS or push notifications; check-in buddies see a prompt in the app only.
- Approval is a person vouching, not automated ID verification.
- Credits are not tamper-proof.
- A public launch needs a hosted backend with real accounts.
