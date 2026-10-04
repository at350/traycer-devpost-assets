# Traycer Devpost assets

Images hosted for the Traycer MHacks 2026 Devpost submission, so they can be linked from the project story.

| File | What it is |
| --- | --- |
| `spacetimedb-architecture-full-detail.png` | Verified SpacetimeDB architecture: camera storage, authoritative simulation, application-level evidence bridge, and all 25 deployed tables and reducer contracts (2026-10-04). |
| `gemini-insights-card.png` | The dashboard's Insights card from a live run: a Gemini-written summary of the real counted trays, next to the dashboard's own "At a glance" figures. |
| `notability/engineering-plan.jpg` | Handwritten engineering plan in Notability: proposed architecture, event contract, impact math and safeguards, build gates, open decisions. |
| `notability/annotated-detector-test.jpg` | A real photo test of the detector, annotated by hand in Notability. |
| `notability/audio-notes-transcript.jpg` | Notability's audio recording with its live transcript beside handwritten test notes. |

Project code: the Traycer repository.

## Best Use of SpacetimeDB — architecture image

Image source: `https://raw.githubusercontent.com/at350/traycer-devpost-assets/main/spacetimedb-architecture-full-detail.png`

Alt text: Traycer architecture showing SpacetimeDB camera storage, authoritative cafeteria simulation, AI decision workers, live subscriptions, and the evidence bridge.

Caption: SpacetimeDB powers Traycer’s waste tracking and live AI cafeteria simulation. Two Maincloud modules store tray observations and JPEGs, maintain atomic waste totals, and run the authoritative simulation through scheduled reducers, durable decision jobs, and identity-gated worker views. An application-level bridge turns reviewed camera evidence into simulation tests, while WebSocket subscriptions keep the 3D dashboard synchronized.
