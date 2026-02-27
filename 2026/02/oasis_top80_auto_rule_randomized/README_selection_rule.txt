Selection rule (auto, trend-based, randomized)
- Seed: 20260227
- Manual trend source: oasis_subjective_selected_by_quadrant
- Manual-selected images are INCLUDED in candidate pool.
- Exclude: practice images + keyword themes (blood/bloody/... + Lion/Nude/Carcrash/Doctor/Injury/Surgery).
- Carcrash exclusion is normalized and also matches 'Car crash'.
- For each quadrant, compute manual centroid on (Valence_mean, Arousal_mean).
- Select 20 via weighted random sampling without replacement.
