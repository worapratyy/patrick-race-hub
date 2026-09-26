# Patrick Race Hub

Second version of the running dashboard and 10K plan, kept separate from `patrick-running-hub` so the two can be compared.

- `index.html` - the hub (Today, Progress, Plan, Race & zones)
- `data/plan.json` - sessions, zones (Garmin LTHR 172), races and checkpoints. Edit the plan here.
- `data/runs.json` - fallback snapshot only. The page reads live runs from
  `https://worapratyy.github.io/patrick-running-hub/data/runs.json`, which the original repo's Strava sync keeps current.

Preview another date: `index.html?date=2026-10-02`

## Publish
Settings > Pages > Deploy from branch > `main` / root.
Live at `https://worapratyy.github.io/patrick-race-hub/`
