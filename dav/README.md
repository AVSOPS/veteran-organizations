# Disabled American Veterans (DAV)

Data for DAV chapters, state departments, and service offices across the United States.

| File | Records | Description |
|------|---------|-------------|
| `local-chapters.csv` | 1,230 | Individual DAV chapters (1,106 active, 124 marked defunct) |
| `state-departments.csv` | 55 | DAV state departments |
| `service-offices.csv` | 89 | DAV service offices — 62 NSO (National Service Officers) + 27 TSO (Transition Service Officers) |

## About the data

**Defunct chapters** are retained in the dataset and flagged via two columns:

- `status="defunct"` — chapter no longer appears in the source-of-truth scrape
- `last_verified="YYYY-MM-DD"` — date of the scrape that confirmed absence

Future scrapes will revive these records if they reappear. The current 124 defunct chapters were last verified on 2026-04-29.

**Service offices** are split by `service_type`:

- `national-service-officer` — paid VA-claims employees, co-located with VA Regional Offices
- `transition-service-officer` — NSOs forward-deployed to military bases to help service members file claims during transition to veteran status

## About DAV

Founded in 1920 after World War I. DAV is dedicated to empowering veterans of all generations with the resources and support they need.
