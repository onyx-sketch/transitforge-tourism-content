# Rails & Roots content model

The repository separates routes, stops and experiences so that a rail station is never mistaken for an attraction.

## Routes: `data/routes/`

A route record identifies its operator or services, the journey it represents, its status, the places confirmed by its sources, and links to those sources.

`transitforge-route.json` contains Lerato's two-leg experience. `blue-train-route.json` and `rovos-rail-route.json` describe separate operator journeys. A place appearing in one journey does not automatically become a stop on another.

## Stops: `data/stops/`

A stop record identifies a place by `id` and `name`. It explains its role in the route, gives a short sourced story, and links to separate experiences through `experienceIds`.

The five individual stop files are initial featured content records. The complete 18-station historical sequence remains in `data/routes/transitforge-route.json`. A station without a featured file must not acquire an invented story or attraction.

## Experiences: `data/experiences/`

An experience is something a person could discover beyond the train: heritage, food, nature or culture. Each entry has its own `id`, `placeId`, description and source. An experience is not automatically included in a train ticket or reachable during a train stop.

## Sources: `sources/`

`references.md` lists the research links and what they support. A link in an individual JSON record keeps the evidence close to the claim used by the prototype.

## Status language

- `operating`: an operator provides the service; check a particular departure before travel.
- `simulation_only`: the prototype represents a journey that cannot be treated as a current booking.
- `operator_listed_route`: the operator publishes the journey, but this record does not verify a date-specific departure.

Dates in these files say when information was researched, not when a traveller will take the trip.
