# Rails & Roots by TransitForge

Rails & Roots is a digital rail-tourism experience that helps South Africans discover the places, people and stories connected to a journey. TransitForge brings route context, station orientation and researched tourism content into one experience.

This repository contains content for a hackathon prototype. It does not sell train tickets, operate trains, display live departures or represent a partnership with a rail operator.

## The story we demonstrate

Lerato is at Pretoria Gautrain Station. She opens Rails & Roots, signs in to the prototype and selects the Pretoria–Johannesburg–Cape Town journey.

Her first leg is a real Gautrain route:

**Pretoria → Centurion → Midrand → Sandton → Rosebank → Park**

The app introduces places along the way without implying that Lerato leaves the train at every station.

At Gautrain Park Station, Rails & Roots opens a new chapter: **the Johannesburg interchange**. Lerato has completed one service and must orient herself toward the adjacent Johannesburg Park Station. The app explains the change of station context and prompts her to check current signs, staff guidance and her onward travel details.

The proposed Shosholoza Meyl leg from Johannesburg to Cape Town is **simulated**. As checked on 23 September 2026, we do not have a confirmed operating timetable for that service. The prototype must not show a purchasable ticket, a departure time, a platform or a guaranteed connection for this leg.

Rovos Rail and The Blue Train are separate Pretoria–Cape Town journey options. Their published routes must not be presented as Lerato's Johannesburg connection.

## Why domestic tourism matters

A journey can introduce a traveller to more than its final destination. Rails & Roots gives each confirmed station a place in the route, then offers deeper, researched stories where a traveller has a realistic opportunity to explore. Featured content can point people toward heritage sites, cultural experiences and, eventually, verified local tourism businesses.

The proposed value is to help South Africans discover destinations in their own country and give smaller places a chance to be considered alongside major attractions. That is a product goal, **not a claim that the prototype has already increased visits or spending**. South Africa's Tourism Growth Partnership Plan identifies domestic marketing and routes and experiences as priorities.

## Content rules

- Include every confirmed station on an operating segment, even if its record is brief.
- Give featured locations richer content backed by official sources.
- Keep train stations, nearby attractions and operator excursions distinct.
- Label a suspended or unverified service as a simulation.
- Verify operating status, stop patterns, accessibility, prices and opening hours before showing travel advice.
- Use operator names to identify their services, without implying endorsement or partnership.

## Repository files

- `data/journey.json` — the ordered Lerato demonstration and separate journey options.
- `data/experiences.json` — researched examples of domestic tourism content.
- `SOURCES.md` — evidence and checks still required.

**Status:** Hackathon prototype. **Last research check:** 23 September 2026.
