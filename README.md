# Rails & Roots by TransitForge

> **What if the place outside your train window became your next South African trip?**

Rails & Roots is TransitForge's interactive rail travel guide prototype. Follow Lerato from Pretoria on Gautrain, understand her change between the Gautrain and Johannesburg Park Station areas, and explore the stories along a simulated historic journey to Cape Town. Discover featured places, meet the smaller stops along the route and save destinations to investigate for a future domestic trip.

**Know before you go:** The Johannesburg–Cape Town Shosholoza Meyl leg in this prototype is a simulation, not a train you can book through Rails & Roots. Rovos Rail and The Blue Train are separate journey choices whose current details must be confirmed with their operators.

**Explore the content:** [Complete journey story for all 23 route points](docs/all-stops-content.md) · [All places and photographs](docs/stops-and-images.md) · [Tourism and business proposal](docs/business-proposal.md) · [Research sources](sources/references.md)

**Rails & Roots is an interactive rail travel guide that helps passengers understand the places moving past their window.** It follows a simulated journey from Pretoria to Cape Town and helps travellers understand the places passing outside the window by combining a journey map with researched stories about South Africa's history, culture, landscapes and local experiences. Along the route, commuters can follow their progress, discover researched local stories and save places they may want to visit later.

A route map can tell a traveller where they are. Rails & Roots also helps them understand why a place matters and whether they might want to explore it on this journey or return another time.

**TransitForge** is the team developing Rails & Roots. This repository holds the route research and tourism content used by the prototype. It records sources and distinguishes real services from the journey we simulate. The guide does not operate trains, sell tickets or claim a partnership with a rail operator.

## The traveller's experience

We demonstrate the product through **Lerato**, a first-time traveller beginning in Pretoria.

Before boarding, Lerato explores the Rails & Roots prototype. She can look at the available journey choices, including separate journeys published by Rovos Rail and The Blue Train. For this demonstration, she chooses the TransitForge experience connecting a Gautrain ride, a Johannesburg interchange and a simulated journey towards Cape Town, whose guide content Rails & Roots preloads before her journey.

As she travels, Rails & Roots helps her in four ways:

| What the guide does | What Lerato gets |
| --- | --- |
| **Orient** | A clear route, the current stage of the journey, station names and what comes next. |
| **Interpret** | Short, sourced stories she can read or hear about places along the route. |
| **Connect** | Researched attractions, local food, places to stay and practical visit information where those details have been verified. |
| **Remember** | The ability to save or star a place that interests her and consider it for a future domestic trip. |

The prototype is designed to keep its core route and stories useful when mobile connectivity is weak. Its moving train position on the long-distance leg is **simulated**; it is not proof that Lerato boarded a train or that a service is operating. Journey-related questions should be answered from verified guide content, with uncertainty stated when information is missing.

## Lerato's route

Rails & Roots follows Lerato on a rail journey from **Pretoria to Cape Town**, travelling through Johannesburg and a series of towns and cities along the way.

The prototype presents the route as one connected travel experience. Its purpose is not to provide ticketing, platform guidance or detailed interchange instructions. Instead, Rails & Roots uses the journey to introduce travellers to the attractions, culture, history and stories connected to the places they pass.

### Pretoria to Johannesburg

Lerato's journey begins in **Pretoria** and follows the Gautrain route towards Johannesburg:

**Pretoria → Centurion → Midrand → Sandton → Rosebank → Park**

These stations represent the first part of her journey.

Rails & Roots uses this section to establish the beginning of the Pretoria-to-Cape Town experience and show Lerato's progress towards Johannesburg. The prototype does not sell Gautrain tickets or replace Gautrain's own journey-planning services.

### Johannesburg to Cape Town

From Johannesburg, the prototype continues along the historically documented **Shosholoza Meyl Johannesburg–Cape Town corridor**.

The route used for the Rails & Roots demonstration is:

**Johannesburg Park → Krugersdorp → Potchefstroom → Klerksdorp → Bloemhof → Christiana → Warrenton → Kimberley → De Aar → Hutchinson → Beaufort West → Laingsburg → Matjiesfontein → Worcester → Wellington → Huguenot (Paarl area) → Bellville → Cape Town**

This gives the Johannesburg-to-Cape Town section **19 stops, including Johannesburg Park and Cape Town**.

Rails & Roots uses these destinations as storytelling points throughout the journey. Some locations receive more detailed featured content, while the wider route helps travellers understand the towns, landscapes, attractions and cultural stories connected to the corridor.

The Johannesburg-to-Cape Town section is presented as a **simulation based on a historically documented Shosholoza Meyl route**. The prototype does not present this section as a current timetable or active ticketing service.

## Why we chose this route

The Geekulcha Train Tourism Hackathon challenged teams to develop an interactive platform that maps and brings to life the rail journey from **Pretoria to Cape Town**, while showcasing local attractions, culture and stories and encouraging domestic tourism.

TransitForge designed Rails & Roots around that journey.

We used the Gautrain route to represent the journey from **Pretoria to Johannesburg**, before continuing from Johannesburg towards Cape Town using the historically documented Shosholoza Meyl corridor.

Johannesburg therefore acts as the point where the journey continues towards the long-distance corridor. In the prototype, however, the process of changing between rail services was **not developed as a separate interchange feature**. Rails & Roots presents the route as a connected tourism experience rather than a step-by-step transfer guide.

The Shosholoza Meyl corridor was useful for the project because it passes through major cities as well as smaller towns that travellers might otherwise pass without knowing much about them. Rails & Roots uses these locations to surface information about nearby attractions, local history, culture and experiences.

The purpose is not only to help a traveller reach Cape Town. It is to make the **journey itself part of the tourism experience**.

A passenger moving through places such as Potchefstroom, Kimberley, Beaufort West, Matjiesfontein or Worcester may discover something interesting during the trip, learn more about the area, or save a destination for a future visit.

This supports the central idea behind Rails & Roots:

> **Rail travel gives you a ticket and a seat. Rails & Roots gives you the story of the journey.**

The Johannesburg-to-Cape Town Shosholoza Meyl service used for the prototype is based on a historical route and is treated as a **simulated journey** within Rails & Roots. Features such as live intercity departures, ticket purchasing, platform information and guaranteed stop times were not part of the prototype.

Other Pretoria-to-Cape Town rail experiences, including **The Blue Train and Rovos Rail**, operate separately and are not combined with Lerato's simulated route in the Rails & Roots prototype.

## How the guide promotes domestic tourism

Rails & Roots turns a location on a route into a reason to learn more. A featured place receives a sourced arrival story and useful visitor information. A smaller supporting stop still receives accurate context, so the journey remains continuous. A place seen from the train can become a trip planned for later. The guide can introduce destinations beyond famous landmarks and let travellers save a place for a separate domestic trip.

Tourism content must distinguish between:

- **A station:** where a train historically or currently calls.
- **A pass-through place:** a location the journey passes without a confirmed passenger stop.
- **An attraction:** a separate place that requires its own access and opening information.
- **A local business:** a verified listing, never an assumed partner.

Our proposed benefit is more discovery of South African destinations and potential visibility for local tourism businesses. The hackathon prototype has **not yet measured** additional visits, bookings or spending. The Department of Tourism's Tourism Growth Partnership Plan identifies domestic marketing and the development of routes and experiences as priorities relevant to this idea.

## How this content repository will work

We are building the repository one researched file at a time. Its route records will preserve the full station order. Its stop records will give featured locations deeper stories and supporting locations concise, factual profiles. Experience records will keep attractions and businesses separate from rail stops.

Every factual claim needs a source. Each record should state when its information was checked. Changing details such as train status, fares, opening hours, accessibility and local transport must be checked again before the guide gives real travel advice. We will not describe an attraction as walkable from a station without verifying the actual route.

See [the illustrated guide to all 18 historical places](docs/stops-and-images.md) for a separate JSON record, visitor site and image for every supporting stop. The photos' creators and reuse terms are listed in [image credits](assets/images/README.md). Supporting photographs are linked from Wikimedia Commons and require an internet connection.

## Core research sources

- [Gautrain: commuter service and stations](https://www.gautrain.co.za/commuter/generalinformation)
- [Gautrain: Pretoria Station](https://www.gautrain.co.za/commuter/stationinfo?stationName=Pretoria)
- [Gautrain: Park Station and Johannesburg adjacency](https://www.gautrain.co.za/commuter/stationinfo?stationName=Park)
- [Competition Commission: final Land Based Public Passenger Transport Market Inquiry, paragraph 6.27](https://compcom.co.za/wp-content/uploads/2021/04/PTMI-Non-Confidential-14-April-2021-FINAL.pdf)
- [Department of Tourism: Tourism Growth Partnership Plan 2025–2030](https://www.tourism.gov.za/AboutNDT/Publications/ABRIDGED%20Tourism%20Growth%20Partnership%20Plan%202025-2030.pdf)
- [March 2026 reporting on PRASA's suspended long-distance services](https://groundup.org.za/article/uncertainty-surrounds-prasas-long-distance-train-plans/)
- Team route research dossier and dated Gautrain journey capture, 22 September 2026

**Research checked:** 23 September 2026.
