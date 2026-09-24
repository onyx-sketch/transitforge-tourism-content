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

## Lerato's route, explained for a first-time train traveller

This experience has **two rail legs and one interchange**. A *leg* is one part of the journey on a particular service. An *interchange* is where a traveller leaves one service and prepares to use another.

### Leg 1: Pretoria to Gautrain Park Station

Lerato begins at **Pretoria Gautrain Station**. She checks Gautrain's current departure information and pays Gautrain separately for this ride. Choosing a route inside Rails & Roots does not buy her a train ticket.

Her southbound Gautrain journey follows this station order:

**Pretoria → Centurion → Midrand → Sandton → Rosebank → Park**

Pretoria is where she boards. Park Station is where she gets off. The stations between them show her progress; they are not automatic sightseeing stops.

**A dated travel-time example:** In a Gautrain journey checked for our research on **22 September 2026**, a selected train was displayed as leaving Pretoria at **20:03** and reaching Park at **20:38**. That is **35 minutes for that train ride**. The displayed fare was **R82**. It does not include time waiting at Pretoria, moving between stations in Johannesburg, or travelling towards Cape Town. Lerato must check the operator's current planner for an actual trip.

### The Johannesburg interchange

When Lerato gets off at **Gautrain Park Station**, leg 1 ends. Gautrain says its underground Park Station is **adjacent to Johannesburg Park Station**, which belongs to a different station and service context.

Rails & Roots treats this as a story chapter, not a small instruction hidden between two train lines. The guide explains that Lerato has completed her Gautrain ride, shows her where the journey changes, and introduces Johannesburg through researched local stories. For a real onward trip, she would follow current station signs and staff guidance and check her next operator, ticket and boarding details.

A team map lookup between selected address pins showed approximately **500 metres and six minutes on foot**; this is an illustrative street route, not a verified platform-to-platform transfer time. We have **not established** a platform, through-ticket or guaranteed connection. Current signs, accessibility and boarding details need a fresh check.

### Leg 2: a simulated Johannesburg–Cape Town journey

After the interchange, the demonstration follows the **historically documented Shosholoza Meyl Johannesburg–Cape Town corridor**. This lets Rails & Roots demonstrate how its guide could tell stories across the country, including at places a traveller might otherwise pass without understanding.

The Competition Commission documented the following historical station order in its passenger-transport inquiry:

**Johannesburg Park → Krugersdorp → Potchefstroom → Klerksdorp → Bloemhof → Christiana → Warrenton → Kimberley → De Aar → Hutchinson → Beaufort West → Laingsburg → Matjiesfontein → Worcester → Wellington → Huguenot (Paarl area) → Bellville → Cape Town**

That is **18 station names, including Johannesburg Park and Cape Town**. We have corrected the spelling of Laingsburg and Bellville from errors in the published report.

This sequence documents a **past service pattern**. It is not a current timetable. As checked in September 2026, the Johannesburg–Cape Town Shosholoza Meyl service is suspended. Rails & Roots therefore labels this leg as a **simulation** and does not show a purchasable ticket, live departure, fare, platform, guaranteed stop duration or arrival time.

## Why we chose this route

The hackathon journey begins in **Pretoria** and ends in **Cape Town**. We chose to follow PRASA's **Shosholoza Meyl**, part of its Mainline Passenger Services, because it offered an affordable way to travel long distances. But its Johannesburg–Cape Town journey began at **Johannesburg Park Station**, leaving a gap between our starting point and the long-distance route.

**Gautrain bridges that gap.** Lerato takes Gautrain from Pretoria to Gautrain Park Station in Johannesburg. There, she leaves Gautrain and makes her way to the separate Johannesburg Park Station for the second leg of our story. This interchange is a key part of Rails & Roots: it shows how two rail services connect to make the journey possible.

The Shosholoza Meyl service between Johannesburg and Cape Town is currently suspended, so **Lerato's second leg is simulated**. Rails & Roots follows its historically documented route to introduce the stops, the places around them, and experiences travellers might choose to explore. That is how the guide uses a rail journey to spark interest in domestic tourism, even while this service is unavailable.

This choice also gives Rails & Roots a meaningful problem to solve. Someone new to rail travel may not realise that arriving at Gautrain Park Station does not mean they have already boarded the next service. The app makes the interchange understandable and keeps the traveller's story connected across it.

PRASA’s Mainline Passenger Services corridor passes through **Gauteng, North West, the Northern Cape and the Western Cape**. Its smaller towns matter to the tourism story. A passenger can learn about a place while passing through and save it for a future visit. We intend to explore a public-corridor experience that could reach a wider domestic audience; we will not claim a price advantage without current, comparable fares.

Since PRASA’s Mainline Passenger Services is still suspended, a traveller can still choose to use Rovos Rail and The Blue Train which remain valid and have **separate Pretoria–Cape Town choices**. Their routes and excursions are not combined with Lerato's Johannesburg–Cape Town simulation.

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
