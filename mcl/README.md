# Marine Corps League

Data for Marine Corps League detachments and state departments across the United States.

| File | Records | Description |
|------|---------|-------------|
| `local-posts.csv` | 974 | Individual Marine Corps League detachments |
| `state-departments.csv` | 50 | MCL national headquarters + state departments |

Founded in 1923. The Marine Corps League is the only congressionally chartered U.S. Marine Corps-related veterans organization, with 76,000+ members preserving traditions and serving Marines.

## Data Source

Detachment data collected from the [MCL National Detachment Locator](https://www.mcleaguelibrary.org/detachment-locator-2/) via the StorePoint API. Geocoded to counties using Haversine distance matching against AVSOPS county centroid data.

## License

This data is published under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). See the repository root [LICENSE](../LICENSE) for details.
