# Rails & Roots content model

The repository separates train route, places, things to explore and source evidence. A historical station is never automatically a bookable stop or an attraction.

## Route

`data/routes/transitforge-route.json` gives Lerato's operating Gautrain leg, the Johannesburg interchange, and the historical Johannesburg–Cape Town station order used for the simulated second leg. `blue-train-route.json` and `rovos-rail-route.json` represent separate operator journeys; do not merge their stops or tickets into Lerato's route.

## Places

`data/stops/` contains **one JSON file for each place**: five featured records (Pretoria, Johannesburg, Kimberley, Beaufort West, Cape Town) and fourteen supporting records. The 18 historical second-leg names include Johannesburg and Cape Town; Pretoria is the additional first-leg start. Supporting records give a story, history, separate visitor activity and site, image attribution, and source links. `historicalStationPosition` is zero based within leg 2, so Krugersdorp is 1 after Johannesburg at 0.

Featured records use `experienceIds` to point into `data/experiences/`. The supporting records embed one small `experience` object so each JSON can be read independently. An attraction is outside the station unless evidence proves otherwise. Hutchinson's record points to a separately planned visit in nearby Victoria West and explicitly says its image is of Victoria West.

## Images

Five featured photographs are files in `assets/images/`. Supporting records have a Wikimedia Commons `image.url`, `filePage`, `creator`, `license`, `licenseUrl`, and `alt`; these are remotely hosted pictures and require network access. Read [`assets/images/README.md`](../assets/images/README.md) for full credits. No operator or photographer endorsement is implied.

## Source and freshness

Each supporting record cites the Competition Commission for historical station order and a local tourism, museum, park, university or government page for its visitor story. `researchChecked` is the date of review, not a travel date. Check live service status, museum availability, ticketing, directions and accessibility with the relevant providers before planning a real trip. Never infer a stopover duration or a walk to a site from the historical route list.

## Status

- `operating`: the operator offers a service, subject to a departure check.
- `simulation_only`: the prototype cannot be treated as a current booking.
- `operator_listed_route`: the operator publishes a journey, but no specific departure is verified by this record.

The visual index in [`docs/stops-and-images.md`](stops-and-images.md) shows the complete sequence.
